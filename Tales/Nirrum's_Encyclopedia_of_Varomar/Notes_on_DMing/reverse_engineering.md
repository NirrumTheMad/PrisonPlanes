<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<title>reverse_engineering</title>
	<meta name='Generator' content='Zim 0.74.2'>
	<style type='text/css'>
		a          { text-decoration: none      }
		a:hover    { text-decoration: underline }
		a:active   { text-decoration: underline }
		strike     { color: grey                }
		u          { text-decoration: none;
					 background-color: yellow   }
		tt         { color: #2e3436;            }
		pre        { color: #2e3436;
					 margin-left: 20px          }
		h1         { text-decoration: underline;
					 color: #4e9a06; margin-bottom: 0 }
		h2         { color: #4e9a06; margin-bottom: 0 }
		h3         { color: #4e9a06; margin-bottom: 0 }
		h4         { color: #4e9a06; margin-bottom: 0 }
		h5         { color: #4e9a06; margin-bottom: 0 }
		p          { margin-top: 0              }
		span.zim-tag {
			color: #ce5c00;
		}
		div.zim-object {
			border-style:solid;
			border-width:1px;
		}
		.checked-box {list-style-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAANOgAADMQBiN+4gQAAAAd0SU1FB9gKGQ8sMEGsKGkAAAAZdEVYdENvbW1lbnQAQ3JlYXRlZCB3aXRoIEdJTVBXgQ4XAAAEBUlEQVRIx62V22tdRRTGf7Nn73P2ybntnNOe3NqkPTGgLTVUUZF6QatSLOKTPgqCIqLgQ0H/A1sQQbBYCBb1QfAxiC8tSO1FqHkwJVKtjdTGNraUmObsc9nXmfGh7cGYpM1D5nHWzPetteZb3wg2eB2YqYm4zSadsMtoboiNBH/3TE0awx6j+MRoxoTg/IYRvP19TQrJS0bzhdHGSyKFkLTtjSKwMjyiEz43ynhtP6bdjBCWyFobAf7eT7VhNF/q1FRbjYjmUohlCVPwnB+6FUxMTJipqSmUUhhjEGKd3bMT4ks/Y6oLBK2Yth8hHYtCJXOix7Nf7xLMzc0xOzvLzp078TyPNE3viW3QJPXzhNWbxFFKHCmMhoLn/FHodd48vGfhapdAacXQlkFK5dL6wIUm6fuTZPuvqDQhaMUYYyiVyuQr6rXDexYuAdi3tSv1ZJNs/R/CaszzT+1na88uXFnCEnJVgivBNN8uTJKmHQI/ptOOcXNZzMz9mOqFs90OHpipWcYwlo5P4ebnuOkrvr5wgrH+h3im7y36MzuwRXYZeKha/OhP0EkadFoxQSdGSotedR/+XwMc2XvKdNUFOFqZx6LKZWIiwjgkikNmLp/hm8sH+K1zjFTHXfBYdTi+eJArzXM0GxFxoBDCopLvo/fqEwi1XPkWkGqjFo2TgB1jOYZUKZTS/D1/ncmLh7jon0IbRWoiTi59ymzzJEEQE3cStNZsGxqlfPE57MBbOR8fP3hDGalOO9fq2DlBvmZw8xa2IxACGn6TydlD/O6f5OzSV/zif0cYhLQaEXGkKBbz7Ov/AOlXV1cxgBJRI3fuSTrpTawt18kWIZN1CFuaONI0w0WOXfsI43YIggh/KUSlhqxrMz74AkOZcWBm9QkH+Gw8NDLuITi+m0yzhluSyJzBLcpblUhFxywSRAEtPwQjsKVN30CNh0uvYuOubSHLtN3J0TO1j0pmBNuFbFWRK0gyPRZpktL2I5JQkclKakNlnh54g6ocvevUr/Ai2a7wineEkcJupA3S1Wg0nVZM2E6wbEF5U5G9Q++wI7sfR7h3N8HVNstykBfzH+KJEZwiWD0aIwxCgJ0R1Mu7GXOeJSuK93bZtQIle4D9pUNU5DC5jEsu55AvZakM5NicGyEj8uuz8bUCQgj67QfY671P3vEoeC69gy695U1U7NG7XV0pUwBjDJa1/JJlWWxzHuflzQe5FJ/GsgUVuZ2t8lEkTvfc0aNHb72flBhjVicQQqCUuvM3/M+WDVguWBrMVdDXEGZlBVEUrVCU9d9s5+fnaTQa2PZyPxEIhJaI1EEoZwX4ncynp6fXrmB4eJjR0VFarRbNZnP9P9rt9gohqNVq1Ov1ZbF/AZGev3hLJ2/zAAAAAElFTkSuQmCC)}
		.xchecked-box {list-style-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAANOgAADMQBiN+4gQAAAAd0SU1FB9gKGQ8bDYnDxEwAAAAZdEVYdENvbW1lbnQAQ3JlYXRlZCB3aXRoIEdJTVBXgQ4XAAAEK0lEQVRIx9WVS2hTWRjHf/eR3CY1nbxMH2YiZRQS6qO13YlMVxY3SnVcuNIBFezGpSADLoQqLu1sHJCqdCFSXFpw4YOCSH3BtFqttTNamabX3DS5bfO6uffMoglja3RGcDMHzuac7/z/53++//cd+L8P6VuCPQYZ8ADNgBd4J31DcDcQs+GnHByRocEDv0kfBSjAOlYCs11Q+gpwDegS8LMJ+3QIK0ATzEhV8Odnz5bzw8P4dJ25aJQ/WlvJ1df/K7hSLtOcTNI+Pk69rpMTgqIQhCDvh1/VSpw79+gRrRMTmLZNezLJJsPg+a5dmOEwQlFqg1sWG16/Jv7sGWXDwBACFQjC9HcwIMONKkGp4PGAJGEDS0IQmZlhnWnye3c3eiyGo6qr3WHbrJ+dJf7gAXI6zSIr72T7/fgzmT4FHnTBsgrQBfYvTU0km5vxz86iADnAm0rRPTWFt7cXZccOJJcLAGHb2K9ekT93jmwmwwdAAFpjI6Ntbfxw5879ag7l6o1sr5eHHR3IsRgeQK/M4sQE+YEB7JcvEY6zAj45SWFgAPPxYwzHoQxIkQjTPT0kIxE+Noj8sexFn4/xnh58iQTeSpHkHAdrbIzi0BCOrmNPTpK/eJHM3bt8sCyKQCiR4NWePWSiUZw1+ZLXJm4pFKLhzBlCsRh2RUXacVgeGaF47RrL58+zcP8+RrmMkCQinZ1EL1zAjERqmkH+tLYl1G3bCJw4QUjT0IA0MJfLMX/5MqmHD0nZNiUgtGULG/r7ccXjINWuWbnmqsuFu7sb/4EDNLlcBIEioNs2KUAFGmMxmk6dQm1tRZI+3xBqEkiShBQOox05Ql1nJ26gvuIUAWiKQnj/ftStW5Fk+YuF+NldsbBA4cYN9KdPmaso8Fc62ZJtk7l1C2t0FGdxESHE1xE4hkHh6lX0oSHSpRIewC/LrPf7CSgKNpCamkI/fZr8pUuIZBIcpyaBunahPp1mub+fDyMjGKUSChCsq6Nh717q9u2jbnSU0uAgRrFIwTThyhUCqRS+hgZKLS1fJvDm87SNjZGcnsYUAjcQ8vsJ9/Xh7u1FDgRQN20iks3iDA+zZFmYhQLqzZtsj8WY3L0baY2Sf55ICCKpFHUzM2SEQAJCHg+hY8fQDh5EDgRWDoRC1J88SePRo2geD0XAcBy8b98Sv3ePYDZbbf2rFQjLIphMsmDbaEBQVQkePox26BCSz7e6i4bDrDt+nGYhmBscpFAskheC4Js3bPR4qHphFYEnlcI7P4/jdqNpGu8TCe4oCsXr1z//F2ga3+/cSfTJE0qmSVYIsKzaOZDcbjKyzFIiwfvt21kMBLA07YsetzWNd+3tLLW0sH5igvT8PH9Go/z44kX+E4LGjg7GDYOcy4XlOEgLC//5P/5LCFzxOPLmzWyIx+m6fduu7v0NVGqyTSycKksAAAAASUVORK5CYII=)}
		.unchecked-box {list-style-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAANOgAADMQBiN+4gQAAAAd0SU1FB9gKGQ8qAt8h3m8AAAAZdEVYdENvbW1lbnQAQ3JlYXRlZCB3aXRoIEdJTVBXgQ4XAAAA60lEQVRIx+2VsQqDMBRF70sCLg5OLoKgjk7+lJ/hh+STXBwcnRz8ArMEkrxOFktbaC3tULzTg5e8k5vADXDq70VbobXmvu/hvQczg4heHrJfXxQFuq67blZbMc8zpmlCXddIkgTOuZcBUko45zCOI6y1Nz2xFSEEZFmGOI7fGg4A3nsQEZqmuXOu9jallACAtm3fvmutNaIoAjM/dkBECCF89KCbk4eAb+kEnIAT8EsAM0OIz3hSyrssUvss8t5fg+uIrLXPs0gIgWVZYIyBUurQyYdheO4gz3NUVQVjDNZ1PfSjpWmKsixvehfB9GBZ3NndrgAAAABJRU5ErkJggg==)}
		.migrated-box {list-style-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAABGdBTUEAALGPC/xhBQAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAANOgAADMQBiN+4gQAAAAd0SU1FB+AKHREFA8vJSnkAAAAZdEVYdENvbW1lbnQAQ3JlYXRlZCB3aXRoIEdJTVBXgQ4XAAAC1klEQVRIx+2VT0hUURTGf/e958w4Tc3TYowMw1GyEgwr1MqsFmbZIrIWQZsWJUjbdoHQpl3Qps0swnCRECQFYkR/TC1iKkqmfzAKTo2Vf8hoRsfR995tkRMT87RRWkUHHhy495zvnvvu933wP/75EKkkEAjIYDCIaZpIKRFCZN0kfX9xcTGtra2/irVUEolECIfDlJeXo+s6hmFkDaCqKoZhEAqFSCaTv60pqcSyLAoLC/F4PEtqDmCaJkIIKisrMybX0sdUVRWA5ubmPzdNjjI1cpXkZC/O1fV03PXgdDqRUtpPIITAsqxsDz0Z/3CZQv8uqo4N4C8/Tp2/DdM0MiZQlvk41OTkI/LW1SGtCVb5drD3eCc71wcA+VcAHA5vDd8+3UGakxiJV7i9pdQevU5T1R35pJ3MV5QW1pf+0kWBheJ2SWua8EQXZXsu4fVVYEz1sEKvof5EuxjoPvzpcRvrdp9C2gGMx6cpOHBmbImMesds7BZubwMVDTfXDnQ3vQfK7AC8wLfExMX5whyQc3q2OEnjGm5vE76SQxsfBLr77a7CNf+n0r/l6sSMtsBSnurckiIILCobAtVZhpF4gZF4jubaymj4Ch/fd380LE7bAnjc0NPxk2yqpmEuwGxF0ag+0k5uTpzZeBeaazvj0We8fXojainsb2xh2BZgbe0gSIllzSIUh63wfQ6dZ/O2fbjcKlOj58jJ3cVENESw5yErc9nf2MLQ4jwQAkV1Lqiq37/cZ9WaahJjF9AcmxiPDhLs7ePe23oOnmUwg2hSShQle96tKDjA2HAniusgo9FxnvY9Jxw7RWzGYy92QghM00x5g53qp9sHmtB58/o2umOI2NwGolMnMYUHIb7aAyiKwsjICLqu2/qBEIKUUAohMaSHSLyBSMoPTINQ6CX5+fn2AEVFRZSUlBCPx4nFYhl3L4RESjF/GEgX3pSj+Xw+/H7/b3U/AEOZFnp7O5+5AAAAAElFTkSuQmCC)}
		ul {list-style-image: none}
		/* ul rule needed to reset style for sub-bullets */
	</style>
</head>
<body>

<!-- Header -->
<div class='header'>
	[ <a href='./Power_dynamics.html'>Prev</a> ]

	[ <span class='insen'>Index</span> ]

	[ <a href='./Sights_Rights_Fights_Lights.html'>Next</a> ]
</div>

<hr />

<!-- Wiki content -->

<div class='pages'>
	<div class='heading'>
	<h1>reverse_engineering <a name='Nirrum's Encyclopedia of Varomar:Notes on DMing:reverse engineering'></a></h1>
	</div>

	<div class='content'>
	<p>
Created Friday 05 October 2018
</p>

<p>
/u/dwizKhalifa<br>
TL;DR: The Player's Handbook gives you a list of challenges for your players that you didn't realize. I included it at the bottom.
</p>

<p>
How do you plan a list of encounters? How do you think of problems for the heroes to overcome? Do you just pick a stat block out of the Monster Manual and put that monster in the next room? Pretty easy, but I think most of us are here because we agree that a great DM puts a little more effort in than that.
</p>

<p>
What if I told you that you were thinking about this all backwards? Like, literally backwards. Maybe you should be starting at the other end.
</p>

<p>
Reverse Engineering Challenges
</p>

<p>
Now obviously this isn't the be-all, end-all way to brainstorm problem-solving obstacles to throw at your players. It probably isn't even my main method. But I think that it grants you a very important insight into the nature of the relationship between Players and the game. And I also needed a sensationalist hook for my intro.
</p>

<p>
The Dungeon Master's Guide explains pretty well how you build an encounter. It's very much focused on combat encounters, but tries to say, "by the way, you should give XP for other types of challenges, too. Combat is just the most fleshed-out component of this game, so it needs more explanation." And in that explanation it frames encounter-building as a pretty abstract game of calculating generalist-measures of challenge. Assign CR values/XP budgets based on a few universal factors, like HP and average damage output per round and such. But the reality when in play is that any given scenario gets complicated by a lot of factors very quickly. Which is why it's understandable that the DMG would abstract things so much. It's relying on you to be smart enough to know when the challenge of an encounter changes because of contextual factors. The CR number might go down when everyone happens to be carrying acid flasks at the moment of the trolls' appearance.
</p>

<p>
But what about Thieves' Cant?
</p>

<p>
My Eureka
</p>

<p>
Hear me out. This actually started when I was discussing character-building options for a potential campaign of a more-obscure RPG called Fantasy Craft (which most DMs would probably do well to at least check out, by the way). Fantasy Craft uses different classes than in D&amp;D, and it specifically aims to offer more types of in-depth problem-solving than just combat stuff. The classes can be categorized in roles like "Talker" and "Solver" and "Specialist," for example. Contrast this with 4th Edition D&amp;D, where every class is defined by its role exclusively within combat encounters (Defender, Striker, Leader, and Controller). So the classes and their abilities are kinda interesting. One of their classes is just "Courtier," which is like the ultimate Talker but the worst Combatant.
</p>

<p>
The class I was interested in is called the "Explorer," and is supposed to be a way for you to play as Indiana Jones or Nathan Drake. You get abilities that let you dodge traps or have a cool contact or refer to a notebook you carry around to solve puzzles and stuff. And classes have some abilities that get better and better as you level up. Well the Explorer has an ability called "Bookworm" that comes in three levels. Here's the description:
</p>

<p>
You can ‘walk up to the right part of a library’ or ‘flip open a book to the right page’ with eerie accuracy. At Level 2, you make Research checks in 1/2 the usual time (rounded up).
</p>

<p>
At Level 11 it becomes 1/4 the usual time, and at Level 19 it becomes 1/10.
</p>

<p>
I thought this was a really cool ability. Definitely makes me feel like Indiana Jones. But my potential GM for this game was telling me a bit about what he had in mind for this adventure (something about escaping imprisonment from ogres or something, I dunno). And I got worried. Because I realized already that my ability would be irrelevant. And, in fact, I realized that it would probably almost always be irrelevant. Here's why:
</p>

<p>
In order for this ability to be useful at all, the adventure in which it is used would need three qualities: 1) There is an opportunity to make Research checks, 2) There is a consequence to making Research checks, and 3) There is a consequence to the amount of time consumed by Research checks (with the degrees of consequences measurable down to gradations 1/10th in length to the normal time). Firstly, a lot of adventures just don't have room for research. You're stuck underground. You're out at sea. You're protecting a caravan. You're holding out during a siege. When, in the natural course of these stories, will the heroes have an opportunity to halt everything and go read at the library for a few hours? Secondly, you might not get anything out of research. Okay, so before you protect the caravan, there's an opportunity for you to research the route ahead of time and any potential dangers. And you discover that... you'll be going through the woods. Pretty normal. You find bears, deer, highwaymen, etc. The DM didn't really know what to tell you when you asked for useful information to be better prepared. Thirdly, even when the adventure was perfect for you to do some research ahead of time, like if you're hunting vampires/werewolves or you're about to excavate a legendary old dungeon or something, it might be simple enough that... you'll get the information you need just by looking for it at all. It's not like it was gunna take you four weeks to read the bestiary entry on werewolves. You'll pick up the useful stuff easily enough. Or maybe it just wasn't time-sensitive to begin with. The dungeon will be sitting there waiting for you whenever you feel ready to delve in. Take your time researching.
</p>

<p>
All of these problems come from the DM not preparing the adventure to specifically address them. Now, a lot of class abilities you can rely on being relevant without needing to put any effort in or a reminder to yourself to address. Fighters and their combat maneuvers will pretty much inevitably get to use them. Druids and their shapeshifting will constantly be thinking of ways to take advantage of their miscellaneous animal forms. But Research checks are not inevitable. They almost certainly won't occur naturally. They are difficult to improvise. You almost definitely need to make it a point to include provisions for a Research check when writing your adventure, because otherwise it probably won't come up. To fit the three requirements, you'd have to 1) set aside an opportunity for the players to research that doesn't seem like a stretch, 2) have useful (but probably not vital) information prepared as a result of the research, and 3) create a cost for the activity (specifically attached to time as a resource) in order to make it a real decision instead of just a given on the part of the players. If there's no cost and only reward to researching, the players will always say, "oh yeah, sure, we also do research first. Might as well." In order for there to be a meaning to the idea of "this guy is better at researching than that guy is," there needs to be multiple degrees of success in this activity in order to define what "better" could mean in this context.
</p>

<p>
I know this might all sound like, "well, duh" but it honestly doesn't cross the minds of most DMs. It might be simple but it's also something you need to be actively aware of.
</p>

<p>
Do you need to include all of this in every adventure you write? Absolutely not. The rogue doesn't get a chance to sneak attack every session, just because of the way things play out sometimes. But do you need to include it occasionally? Definitely. Because otherwise your player is not able to play their character to their full capacity. An ability is only as useful as its use. And soon you realize that a Player Character's strength is defined by the application of their class features and almost nothing else. NPC commoners have six ability scores, too. Lower, but they have them. Yet they can't be adventurers delving dungeons and fighting monsters. Why? Well the main reason why a commoner isn't able to delve the dungeon and you are, the main thing separating NPCs from PCs, are class features. And if class features are never used, then the PC becomes functionally indistinguishable from an NPC. They may as well have been playing a classless commoner who just happened to have some high ability scores. I'm sorry Laozi, but a bowl is not most useful when it is empty. A bowl is most useful when it is being used.
</p>

<p>
Writing Around Class Features
</p>

<p>
Thieves' Cant has become something of a running joke in D&amp;D. It's been around since pretty much the beginning of the game and is now iconic. It's based on a very real thing, too. It isn't just a way of saying, "oh well you know, criminals have their own sort of urban lingo." Thieves' Cant was real, had a lot of variation, and was a pretty fully-developed code of communication. It's a really cool, atmospheric, flavorful, and unique non-combat ability for rogues to have. Every time you get a first-time player making their first ever character and they pick rogue and they start going through the character creation and reading through abilities, you get to tell them about their secret thief language and they say, "Oh that's so cool! It's like Shadowmarks in Skyrim! I can't wait to learn all sorts of exclusive thief-y information that the other players won't know!"
</p>

<p>
No DM ever fucking uses Thieves' Cant.
</p>

<p>
I mean, some do. Obviously some do. But most of them use it because they agree that it's cool and they think it's a waste to see it go unused. They specifically plant opportunities for it to come up in their adventures because they want it to come up. But if there were a hypothetical "default game of D&amp;D" implied by the rules, then apparently Thieves' Cant would just be flavor text because the designers were comfortable packaging that into the rogue's set of 1st level abilities like it costs 0 points.
</p>

<p>
But I imagine you could write an entire plot around using Thieves' Cant. A sort of investigation into the criminal underworld where you need a guide or cypher that can help you follow the right symbols and phrases to get your answers. And it wouldn't require any combat.
</p>

<p>
Now don't get me wrong. I like D&amp;D combat. I think there should be a healthy amount of it. And D&amp;D, including 5E, is very much built for action stories. But even with that being said, a lot of DMs spend a lot of time trying to figure out other ways they can challenge their players without it being about beating someone else in a fight. And you can only have so many traps, puzzles, and riddles before it begins to seem formulaic. The secret is that, this whole time, you were given a list of obstacles to throw at your players that's guaranteed to be relevant and fits into the pre-established framework of the game. This sentence is important:
</p>

<p>
"Any ability or feature that a character has at their disposal is a potential challenge for them. Conversely, any ability or feature they don't have is a potential challenge as well."
</p>

<p>
If the rules enumerate to your player an ability, the implication is that this is something a person couldn't have been able to do otherwise. You have to be a rogue to know Thieves' Cant. You have to be a cleric to use Turn Undead. Which means that when writing your adventure, you could make a list of character abilities and key your encounters to one or several of them. You have a handful of players, so you can have a lot of variety in your encounters, and you can give everyone a day in the spotlight. And when you want to figure out a way to really challenge them, you look at abilities that aren't at their disposal and throw that at them. In some cases they'll have to solve it by thinking outside the box. In other cases, it can act as a straight-up invisible wall. Look, at 13th Level, a monk completely eliminates the language barrier. No way around it. If the party has a monk, when they hit 13th Level you better give up any plans you had to restrict information based on language proficiency. But if you know there aren't any monks on the party, then you can still use the language barrier as a real barrier. And yeah, oftentimes "there's a spell for that," and most spellcasters get a pretty wide variety of spells, but... not all at once, usually. Knock is a second-level spell for bards, sorcerers, and wizards. Pretty likely you'll have at least one of those three classes in the party, but you can still use locks during those early adventures before your players can cast second-level spells. And even if they can cast the spell, there's a good while when those second-level spell slots are few and valuable enough that they can't afford to use knock to automatically unlock more than a couple doors.
</p>

<p>
Any ability that can be possessed through multiple different paths is better suited for being something that empowers your players. You can feel safe throwing poison damage at your players knowing that it's fairly likely they've acquired some ability that makes them resistant to poison damage. It's a "this will make them feel good for choosing this option" challenge. An easy win that validates their decisions when building their character. Conversely, making your encounter specific to a rare ability or benefit makes it more likely to be a serious obstacle for the party. It's unlikely that someone had "just the right thing" for this challenge. And even if they did, it was probably only one of them. Even if someone is immune to mind-control, if their five friends aren't then they can still be pretty screwed when the rest of the party gets mind-controlled.
</p>

<p>
Where This Can be Hard to Implement
</p>

<p>
For starters, if you're writing your adventure for a specific audience, then it's easy enough to write it around their specific abilities. But if you were writing your adventure for publication, then you'd have to make sure it provides opportunities for any combination of all the classes, and you'd have to make sure none of these things were really vital. The party might not have a rogue, so you can't make knowing Thieves' Cant a requirement for beating the adventure (unless you offer an alternative in-story method to get the heroes through that obstacle). And of course there's always the issue of trying to make these opportunities to use your abilities not feel forced and shoe-horned in.
</p>

<p>
It can also be hard for the DMs who don't deliberate on these sorts of things, exactly. My reasoning so far assumes that you write your adventures and plan them out. You plan an outline of the plot and the encounters and have an idea of what direction it'll go. Not every DM does that. A lot of DMs nowadays make use out of elements of emergent gameplay and emergent story, borrowing from procedural-generated games like Rogue and Nethack. Games whose preparation is instead just the setting up and integration of a number of mechanical systems that run through scripts and are prone to affecting each other when they interact (go ahead and watch this video if you find this approach to gameplay and storytelling interesting). But you can still build those systems to target specific character abilities. You can, instead of shoe-horning an opportunity for Thieves' Cant, create a system that generates patterns of how and where Thieves' Cant shows up and what causes it, and then working it into the plot as the system tells you it appears.
</p>

<p>
A Handy Dandy Steal-able List
</p>

<p>
I went through the 5th Edition Player's Handbook and made a list of abilities and features. I specifically only included things that I felt, based on my experience as a DM, were not necessarily going to show up in adventures on their own inevitably. They'd have to be deliberately planted in order to see use, most likely. Which means that almost all combat abilities didn't get included. Something that did get included were damage types, since I feel like it's easy for too many DMs to have their players fight even more humanoids with mundane swords instead of thinking of enemies that deal poison damage every now and then. But obviously some of these abilities remain more specific and rare of use than others. I also haven't gotten around to applying this exact same process to the spell list yet, because it's pretty daunting. But technically every single spell in the game is a class feature that can solve a potential problem. And then there are features specific to some archetypes but not to the whole class. I included those but I didn't delineate the stuff that's exclusive to an archetype. You can go read the class entry yourself to figure that out. You'll soon realize that the power to read minds is something only Knowledge Domain clerics get, not all clerics. And of course, this was all just a big judgment call. You don't need to agree on what I should have included or not included here. This is my list of conflicts that can be inferred from powers enumerated to the players through the rules.
</p>

<p>
Racial Conflicts:
</p>

<p>
Darkvision<br>
Dwarf/Halfling: Poison resistance<br>
Dwarf: Smithing, Brewing, Masonry<br>
Dwarf: History checks based on stonework<br>
Elf: Charm resistance<br>
Elf: Magic sleep resistance<br>
Elf: “Mask of the Wild: You can attempt to hide even when you are only lightly obscured by foliage, heavy rain, falling snow, mist, and other natural phenomena.”<br>
Halfling: Frightened resistance<br>
Gnome: History checks based on magic items, alchemical objects, technological devices<br>
Gnome: Clockwork devices<br>
Class Conflicts:
</p>

<p>
Barbarian: Can’t be frightened/charmed, can frighten others, vulnerable to psychic damage, can lift/pull/push/break stuff, see far, track and travel stealthily quickly<br>
Bard: Can block frightened/charmed<br>
Cleric: Can turn undead, can get divine intervention, can read minds, can read the past, can charm plants/beasts<br>
Druid: Age slowly (maybe this isn’t so important), can move quickly/safely through difficult terrain/non-magical plants, can’t be charmed by elementals/fey, immune to poison/disease<br>
Fighter: Can make long jumps, can get artisan’s tools, can teleport within sight<br>
Monk: Can move along vertical surfaces/across water, won’t take falling damage, immune to disease and poison, can completely remove the language barrier, won’t age, can turn invisible, can astral project, teleport within the dark<br>
Paladin: Can detect presence of celestials, fiends, undead, consecrated areas, and unconsecrated areas, extra damage to undead, fey, and fiends, can’t be diseased, frightened, charmed, protected from aberrations, celestials, elementals, fey, fiends, and undead, can make light, can fly<br>
Ranger: Can track favored enemy, recall info about them, and know their language, they need 1 hour of travel in their favored terrain for their benefits to count, can move through difficult terrain quicker, can’t get lost (except by magic), remain alert to danger while traveling, move stealthily at a normal pace, really good at foraging, can sense presence of aberrations, celestials, dragons, elementals, fey, fiends, and undead within 1-6 miles, can’t be slowed/hurt by non magical plant hazard terrain, can camouflage, can’t be tracked<br>
Rogue: Can sense presence of invisible beings, can disarm traps and open locks, can climb and make running jumps well, can spend a week creating a false identity, can mimic others<br>
Sorcerer: Can get powers related to Acid, Lightning, Fire, Poison, and Cold, can fly<br>
Warlock: Can charm and frighten, turn invisible and teleport within sight, immune to charm, resistance to psychic, telepath<br>
Wizard: A spellbook can get lost or destroyed (meaning it is a smart thing for an enemy to target) [EDIT: I do not recommend doing this to low-level wizards. This can be a potentially crippling challenge, and thus an appropriately dramatic setback for an experienced wizard who always took their spellbook for granted], learn spells by finding their formulas in the world, can see into the Ethereal Plane, can read any language, can see invisible creatures, can protect allies from their Evocation spells to an extent, can transform one material into another (including wood, stone, iron, copper, or silver)<br>
Background Conflicts:
</p>

<p>
Acolyte: Can find shelter/support/healing at establishments sharing your religion<br>
Charlatan: Second identity (disguise, documents, contacts)+forgery skills<br>
Criminal: Criminal contact that can always be contacted<br>
Entertainer: Can find shelter in exchange for performance/gladiation<br>
Folk Hero: Support among common people<br>
Guild Artisan: Guild membership<br>
Hermit: An important discovery (might have to be worked into the plot to be relevant)<br>
Noble: Welcome in high society, can gain audience with local nobles, or have retainers<br>
Outlander: Can always recall general layout of geography, and can find plentiful food/water<br>
Sage: Can always recall where/from whom to acquire lore<br>
Sailor: Can always secure free passage on a ship, or people are afraid of your reputation<br>
Soldier: Support of military<br>
Urchin: Can travel twice as fast in a city<br>
Language Conflicts:
</p>

<p>
(5E characters can, through their features, gain access to the following list of languages somehow. You can either use these or make alternatives, and you can use languages not on this list as major barriers)
</p>

<p>
Common, Dwarfish, Elvish, Halfling, Draconic, Gnomish, Speaking with small animals (Gnome), Orc, Infernal, Druidic, Thieves’ Cant (4x as long to communicate)
</p>

<p>
Equipment Conflicts:
</p>

<p>
Carrying capacity and space to store stuff is an obstacle<br>
If a spellcaster loses their focus then they will have a lot more trouble casting spells.<br>
Weapons can be silvered in case that is more effective against some enemies<br>
A disguise kit<br>
Gambling (earning money+reputation)<br>
Games (earning money+reputation)<br>
The favor of an admirer, trinket, letter of introduction, etc. (valuable pawnable item or something to form a social connection)<br>
A shovel (have to dig a path or dig to find something)<br>
A forgery kit<br>
Thieves’ tools (pick locks, pick manacles, disable traps)<br>
An herbalism kit (can help create antitoxin and potions of healing)<br>
A winter blanket (have weather-related hazards)<br>
Traps (have opportunities for PCs to set traps)<br>
Navigator’s tools<br>
Rope (climbing, holding a prisoner, hoisting, etc.)<br>
An insignia of rank (have several established militaries that will recognize this)<br>
Map of the city you grew up in (has bits of world lore on it, might have a clue for a puzzle or something by coincidence)<br>
Antitoxin (protects against poison damage)<br>
A book (advantage on a related check)<br>
A spyglass (have situations in which seeing far in detail would be helpful)<br>
A tent (make an attack less likely but a burglary more likely)<br>
Vehicles (cuts down on travel time+add safety+carry plenty of stuff. More convenient as a DM and consistent as a challenge to only offer temporary services but discourage permanent purchases)<br>
Skill Conflicts:
</p>

<p>
These are all examples specifically named in the book. Obviously it isn't hard to brainstorm more and more and more uses for these. But why not have these all in one place anyway, right?
</p>

<p>
Contests (most commonly a contest of bluffing/insight or stealth/perception, but examples include two people going for a dropped item on the ground, or a PC holding shut a door that a monster is trying to force open)<br>
Strength: Lifting, pushing, pulling, breaking things<br>
Strength: Force body through a tight space<br>
Strength: Force open something stuck, tip something over, break free of bonds<br>
Strength: Carrying capacity<br>
Strength (Athletics): Climb a cliff (add slipperiness), avoid hazards while climbing, cling and avoid being knocked off<br>
Strength (Athletics): Long jumps, platforming<br>
Strength (Athletics): Stay afloat in dangerous currents, chaotic waves, or dense waters<br>
Strength (Athletics): Resist being pulled under the water<br>
Dexterity: Steer a vehicle, pick a lock, disable a trap<br>
Dexterity: Tie something up securely, wriggle free from bonds<br>
Dexterity: Swing across a pit, cross a rickety bridge, go across monkey bars<br>
Dexterity (Acrobatics): Run across slippery or unstable surface, balance on a tightrope, stay upright on moving ground, platforming<br>
Dexterity (Sleight of Hand): Pickpocket someone or steal something<br>
Dexterity (Stealth): Sneak past something unfightable<br>
Constitution: Hold breath (from poison or smoke or something?), fight a choke hold<br>
Constitution: Survive without food or water, go without sleep, march or labor for hours on end<br>
Intelligence: Communicate with a being without words<br>
Intelligence (Knowledges): Interpret Lore, identify important combat traits of beings, anticipate how something will behave (a storm, a source of magic, a divine ritual, etc)<br>
Intelligence (Investigate): Deduce weak points in architecture, what caused certain mysterious things, piece together clues<br>
Intelligence (Investigate): Research and gain knowledge<br>
Wisdom: Detect if a seemingly living creature is actually undead (or a seemingly dead creature, for that matter)<br>
Wisdom (Animal Handling): Deal with animals in their natural habitats (or maybe domesticated hostile animals)<br>
Wisdom (Insight): Detect a lie or get a hint as to what will happen next<br>
Wisdom (Medicine): Diagnose an illness<br>
Wisdom (Perception): Hear secret conversations, find hiding enemies, detect secret passages<br>
Wisdom (Survival): Follow tracks, navigate through unfamiliar areas, get hints about surroundings (like if there are owlbears living in the area)<br>
Charisma (Deception): Wear a disguise, gamble, keep someone in the dark<br>
Charisma (Intimidation/Persuasion): Interrogation, talking down someone hostile, get your way<br>
Charisma (Performance): Perform for money or to impress someone threatening<br>
Skipping the three "classic" ability saving throws, here are the three that can be less intuitive to think of uses for:
</p>

<p>
Strength Saves: Keep from being crushed, avoid being knocked prone<br>
Intelligence Saves: Avoid psychic damage, figure out direction after being disoriented, realize false information or a scam<br>
Charisma Saves: Avoid fear, maintain a bluff in an emergency, avoid temptation, keep face and composure<br>
-
</p>

	</div>

	<br />

	<div class='page-footer'>
		<b>Backlinks:</b>

		<a href='..\Notes_on_DMing.html'>Nirrum's Encyclopedia of Varomar:Notes on DMing</a>

		<br /><br />

	</div>

	

</div>

</body>
</html>
