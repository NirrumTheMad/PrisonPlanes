<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<title>Rules Augmentations</title>
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
	[ <a href='./Random_Plot_hooks/Strange_Train_Ride.html'>Prev</a> ]

	[ <span class='insen'>Index</span> ]

	[ <a href='./Weird_worldbuilding_notes.html'>Next</a> ]
</div>

<hr />

<!-- Wiki content -->

<div class='pages'>
	<div class='heading'>
	<h1>Rules Augmentations <a name='Nirrum's Encyclopedia of Varomar:Useful DM Stuff:Rules Augmentations'></a></h1>
	</div>

	<div class='content'>
	<p>
Created Thursday 13 February 2020
</p>

<br>

<p>
In Snarl, you can be anyone from anywhere. In one of the cities, you can be anyone from anywhere and <i>probably live. </i>This means that there are great magics and arts across the multiverses that can be found here, and because of the nature of getting here, they are things you are <i>likely</i> to find, even if there are fewer people here than elsewhere.
</p>

<p>
Here is a list of some of the things you <i>may</i> do without breaking the setting at all, Including classes and archetypes. If you are the one running this game, then this list is merely a list of ideas that might indicate what the setting is <i>intended</i> to feel like. This is a world of exceptions though, and there is no reason not to find something absolutely bonkers here. These are just some (arguably) balanced options. It is worth noting that many of these changes can completely change the flavour of a class to something unintended by the designers. To this idea my statement is "My ribbons are prettier"
</p>

<br>
<br>

<p>
<div style='padding-left: 30pt'>
<b>Legend:</b>
</div>
<div style='padding-left: 60pt'>
<i>Published options - </i>Official Wizards of The Coast Dungeons and Dragons Published material (in books), not including Unearthed Arcana or Plane shifts and streams<br>
<i>Unearthed Arcana - </i>Official Wizards of the coast playtest material and planeshifts such as Strixhaven and Ravinica settings.<br>
<i>Specific homebrew - </i>Certain Homebrew materials that will be usually mentioned by name<br>
<i>Setting legal - </i>They exist in the world frequently enough that a DM <i>should</i> allow them, but as always, are under no compulsion to<br>
<i>Are allowed - </i>Exist infrequently in the world, A DM may choose at their leisure to allow these, though it is assured they are not too potent<br>
<i>Banned - </i><b>Not allowed. Even if you are the DM. Ruins the fun. :Winkyface:</b>
</div>
</p>

<p>
<div style='padding-left: 60pt'>
<b>A note on Guildmaster's guide to Ravnica: </b>The subclasses are allowed, the backgrounds and items are not. Ravnica was made for a higher power setting than the rest of Dungeons and Dragons, <br>
<b>A note on Unearthed Arcana: </b>With only some noted exceptions, if a character option is published or posted in unearthed arcana after already having been in one, then the most recent version of the option is the preferred one. 
</div>
</p>

<p>
<b>All classes:</b><br>
<div style='padding-left: 30pt'>
Any racial restriction for a class or archetype has been removed. Incongruities with the lore can and will be answered with <s>bullshit</s> Advanced lore. It's a big multiverse and there are lots of opportunities.
</div>
</p>

<p>
<b>Artificer</b><br>
<div style='padding-left: 30pt'>
All published options are setting legal. Gunpowder and most explosives don't work on this plane but things like compressed air and <i>magic</i> Obviously do. Artificers often are trained at the university of Manaharamu but nothing stops anyone from tinkering.
</div>
</p>

<p>
<b>Barbarian</b><br>
<div style='padding-left: 30pt'>
All published options are setting legal, but battleragers are going to feel nerfed in comparison to other barbarians. 
</div>
</p>

<p>
<b>Bard</b><br>
<div style='padding-left: 30pt'>
All published options are setting legal. Because of their studious nature, Bards may use Intelligence as their dominant stat, reflecting then a different type of wizard, capable of learning in a different way as well as the Bard's explicit use of memory. 
</div>
</p>

<p>
<b>Blood Hunter</b><br>
<div style='padding-left: 30pt'>
Matt Mercer's Blood Hunter Class is setting legal. Please use the most up-to-date version.
</div>
</p>

<p>
<b>Cleric</b><br>
<div style='padding-left: 30pt'>
All published options are setting legal. While it is not suitable for <i>this</i> particular prison plane, the Specific Homebrew for The Magitech Templar (and thus gear domain) is allowed in the prison planes as well.
</div>
<ul style='padding-left: 30pt'>
<li>Not all gods hate undead so the destroy and turn undead features can also pick from fey, fiends, celestials, abberations, and elementals, though there is a dearth of some of these. A cleric may change what type of creature this feature targets at the end of a long rest. It should be assumed that clerics act in accordance with their god's wishes and a god may choose to <i>not</i> change a channel divinity or choose for the cleric, should there be need to keep it a certain type. </li>
</ul>
<div style='padding-left: 60pt'>
<b>DM's Note: </b>Or if a DM knows that the dungeon they're going into is absolutely packed with mephits or sprites as an example.
</div>
<ul style='padding-left: 30pt'>
<li>Chill Touch, Lightning Lure, Primal savagery, and create bonfire are all Cleric cantrips</li>
</ul>
</p>

<p>
<b>Druid</b><br>
<div style='padding-left: 30pt'>
All Published options are setting legal. Druids of the Circle of Spores are known as Circle of Parasites/symbiosis, a set of much more robust names.
</div>
<ul style='padding-left: 30pt'>
<li>The wild shape feature can become swarms of beasts, though the components of the swarm must remain closely packed together or the wildshape ends with the druid reappearing at the location of the centermost creature. </li>
<li>If a Circle of swarms druid becomes available, then that will be used instead. (maybe add circle of stars, seasons, or sun)</li>
<li>Certain Monstrosities are now considered beasts (see monsters)</li>
<li>Druids can wear metal, in fact, they frequently do. Turns out that metal is just as natural as wood, especially when some trees on these planes have thought it in their best interest to lace their lignin with aluminum. This was clarified in a sage advice to be cultural and not mechanical, but I felt the need to be explicit here</li>
<li>Druidic is strangely universal, Any creature that can communicate in druidic can be understood and can understand any other</li>
</ul>
</p>

<p>
<b>Fighter</b><br>
<div style='padding-left: 30pt'>
All published options are setting legal. 
</div>
<ul style='padding-left: 30pt'>
<li><b>Brute Fighter</b> from the Three subclasses Unearthed arcana, (also containing the original spore druid) is allowed.</li>
<li>Eldritch knight can choose any two schools of magic and instead of just the wizard list, they can also choose from either Bard, Sorcerer, Druid, or Cleric, Using that class' Casting ability as appropriate. They may only pick from one spell list.</li>
</ul>
</p>

<p>
<b>Monk</b><br>
<div style='padding-left: 30pt'>
All published options are setting legal except the Way of Four Elements, which is allowed (see below). 
</div>
<ul style='padding-left: 30pt'>
<li>The Unearthed Arcana for way of the astral soul is allowed</li>
<li>For the Class features variants for monk and for the Official <b>Kensei, </b>The restriction on two-handed weapons has been modified. Any melee weapon that is two-handed has a non-heavy variant at 3/4 the listed weights (see <b>Weapons </b>further down for more clarification), both 2d6 and 1d12 weapons drop to 1d10, 1d10 weapons drop to 1d8, and Greatclub is worse than a staff presently anyway. These versions of each weapon can be used a monk weapon for the purposes of those features.</li>
<li>The Way of Four Elements Remastered by <a href="file:///C:/u/spiketaildrake" title="/u/spiketaildrake" class="file">/u/spiketaildrake</a> is setting legal and preferred.</li>
</ul>
</p>

<p>
<b>Paladin</b><br>
<div style='padding-left: 30pt'>
All published options are setting legal. There is a reminder that a Paladin's Oath is the source of their power. They do <b>Not </b>require gods or sugar daddies to use their abilities, which is why their casting ability is charisma. They are powered by sheer determination.
</div>
<ul style='padding-left: 30pt'>
<li>The Divine Sense feature allows a paladin to choose three creature types selected from fey, fiends, celestials, abberations, elementals, constructs, undead, and monstrosities. Some creatures listed as monstrosities are no longer considered such (see monsters below). </li>
<li>The Divine smite feature allows a Paladin to choose Undead and one other, selected from fey, fiends, celestials, abberations, and elementals, constructs, and monstrosities. A paladin can change which creature type  other than undead is affected by this feature when at the end of a long rest. This reflects a Paladin's determination to combat certain forces, though undead are always weak to this sort of power. This list is longer than others because Constructs and Monstrosities rarely have the extraplanar or extremely magical properties that the others do. The difference is subtle but noteworthy, though in some cases, such as modrons, Exceptions can be made at a DM's Discretion. Unless Specified, assume that discretion is <i>not</i> in favour of such a ruling.</li>
<li>The Lay on Hands feature can affect any creature. </li>
<li>The cleansing touch feature works on Magical effects that are not spells, such as Ghost posession</li>
<li>The Channel Divinity options that list a creature type now allow a paladin to pick two creature types when they obtain this class feature. A paladin may choose Fey, fiends, celestials, abberations, elementals, and undead. When Obtaining a new level in this class, a Paladin may change one type of creature that this feature targets.</li>
<li>Divine smite can be used on fists, despite what the Sage Advice Says</li>
<li>Undying sentinel technically makes you immortal, as one of the drawbacks of old age is the breakdown of processes which eventually leads you to death.</li>
</ul>
</p>

<p>
<b>Psions, Mystics, and other such things</b><br>
<div style='padding-left: 30pt'>
So far, no published options or unearthed arcana are setting legal, The Mystic Unearthed arcanas are <b>banned</b>. That said, There <i>are</i> psions and other psychically powered people in this world, and it would not break the setting to include homebrew that a DM judged as fair
</div>
</p>

<p>
<b>Ranger</b><br>
<div style='padding-left: 30pt'>
The unearthed arcana for the most recent revised ranger or the class feature variants are both setting legal. The Player's Handbook Ranger and subclasses are  allowed, though nearly every feature they get is underpowered for its level and something that another class gets much much earlier. All other published subclasses are setting legal.
</div>
<ul style='padding-left: 30pt'>
<li>Certain monstrosities are now considered beasts, and are thus available for beast companions (see monsters)</li>
</ul>
</p>

<p>
<b>Rogue</b><br>
<div style='padding-left: 30pt'>
All Published options are setting legal
</div>
<ul style='padding-left: 60pt'>
<li>The Unearthed Arcana version of the Swashbuckler is allowed</li>
</ul>
</p>

<p>
<b>Sorcerer</b><br>
<div style='padding-left: 30pt'>
All published options are setting legal. 
</div>
<ul style='padding-left: 30pt'>
<li>Lightning bolt, call lightning, storm of vengeance are added to the sorcerer's spell list.</li>
<li>A metamagic option exists that allows a sorcerer to change the damage type of a spell for two sorcery points. There are unearthed arcana that offer this but this is <i>explicitly</i> something they can do. </li>
<li>Similarly, when a sorcerer learns a sorcerer spell (from the sorcerer spell list) they can choose the types of damage dealt by that spell. This decision cannot be changed later.</li>
<li>Whenever a wild magic sorcerer casts a spell <i>at all, </i>Roll 1d4, on a 4, a wild magic surge occurs. There is no need for DM participation here, we have enough on our plates</li>
</ul>
</p>

<p>
<b>Warlock</b><br>
<div style='padding-left: 30pt'>
All published options are setting-legal
</div>
<ul style='padding-left: 30pt'>
<li>Warlocks may use intelligence as their casting ability modifier. They were designed to be Intelligence-based for this edition anyway. This reflects the methods of studying that some warlocks use to gain their power, in the writing or obtaining of their pact, in fulfilling the conditions of that pact or avoiding their patron to the same effect.</li>
<li>Find Familiar for warlocks can summon any tiny fey, fiend, celestial, elemental, or construct, of CR 1 or lower, abiding by the usual restrictions. Some of these things do not exist in the monster manual, but should they be added, then they would be allowed.</li>
<li>Awakened mind gives one-way telepathy, despite the poor wording</li>
<li>The Unearthed Arcana Option for "The Seeker" Patron is setting Legal.</li>
<li>A reminder is necessary that a warlock earns their power and it cannot be removed unless that is part of the terms of the pact. </li>
<li>Agonizing blast can add either your Charisma <i>or</i> your intelligence modifier to damage</li>
<li>Hex Warrior allows Charisma <i>or</i> Intelligence to be used in place of Strength or Dexterity</li>
<li>Any time a warlock class feature says "Charisma", replace it (non-recursively) with "Charisma or intelligence"</li>
</ul>
</p>

<p>
<b>Wizard</b><br>
<ul style='padding-left: 30pt'>
<li>All published options are setting-legal. </li>
<li>In this setting, there are vast congregations of mages, in particular at the university of Manaharamu. At these locations, all non-enchantment spells cost a quarter of the resources and half the time to write in a spellbook. For characters who got their first level in wizard, artificer, or a warlock on this plane also only need to spend a quarter of the time, as Manar-Standard spell notation has been around for thousands of years with only minor changes. Enchatnment spells are the exception to this which follow the normal rules unless the player is somehow <i>presently enrolled at or employed by the university of manaharamu in theraputic enchantmnet courses or programs, and has obtained their Enchantment License from the Department of Pacts. Necromancy spells like Animate dead also require a license but you are not required to be enrolled to obtain access to learn the spells.</i></li>
<li>Transmutation wizards of the 14th level or higher can use their Major Transformation option from Master Transmuter to alter the size and mass (though technically just the density) of an object by 10% at a time. The result object must be made of materials and of a form that fit these criteria. The result must be within these bounds for 90% of the objects's resultant volume. No Turning a pile of sand into a cube of aerogel with a gold coin at the top allowed.  There is a chart in the golden tower which allows wizards to follow chains of materials to achieve other ones over the course of days to months. </li>
</ul>
</p>

<p>
<b>Casting Classes and classes with abilities that reproduce spells</b><br>
<ul style='padding-left: 30pt'>
<li>Some spells have had their school of magic changed, see <b>Spells</b> below</li>
<li>A casting focus for any class that has the Arcane or Druidic focuses feature, can be anything that is "sufficiently mystical," Including decks of cards, jewelled hair pins, bowls made out of turtle shells, <s>or copies of the player's handbook.</s></li>
<li>Verbal components are always audible unless stated specifically in the spell or a feature that reproduces it or unless the Subtle Spell metamagic is used</li>
<li>Somatic components are always very visible unless stated specifically in the spell or a feature that reproduces it or unless the Subtle Spell metamagic is used</li>
</ul>
</p>

<p>
<b>Backgrounds</b><br>
<ul style='padding-left: 30pt'>
<li>All published options are allowed except those from Guildmaster's guide to ravnica. </li>
<li>A reminder that Rules as written, backgrounds are customizable, and features and proficiencies from them can be changed around to suit the character.</li>
</ul>
</p>

<p>
<b>Multiclassing</b><br>
<ul style='padding-left: 30pt'>
<li>Muticlassing Paladin, Ranger, And Artificer now follows a different chart. Add together all levels you have in these classes and consult the spell slot table of one of them (as they have the same progression). If you have multiclassed into another class with the spell casting feature, then add the levels you have in these classes together before dividing and rounding.</li>
<li>Multiclassing Eldritch knight and Arcane trickster now follows a different chart. Add together all levels you have in these classes and consult the spell slot table of one of them (as they have the same progression). If you have multiclassed into another class with the spell casting feature, then add the levels you have in these classes together before dividing and rounding.</li>
</ul>
<b>Feats</b><br>
<div style='padding-left: 30pt'>
All published feats are setting legal. All Unearthed Arcana Feats are allowed
</div>
<ul style='padding-left: 30pt'>
<li>The First bullet of the shield master feat has been changed to "when you take the attack action, you may replace one of the attacks  with an attempt to try to shove a creature within 5 feet of you with your shield  and make another single melee attack as a bonus action. Alternately you may take a  bonus action to try to shove a creature within 5 feet of you with your shield after taking the attack action on your turn. "</li>
</ul>
</p>

<p>
<b>Races: </b><br>
<div style='padding-left: 30pt'>
All published races except centaur are allowed. Centaurs are <b>hard banned</b>. They get eaten by the sun. This includes cervitaurs and similar races. Minotaurs are fine.
</div>
<ul style='padding-left: 30pt'>
<li>Firbolg are considered large in this setting as they have been in every previous edition. </li>
</ul>
</p>

<p>
<b>Weapons and Armor</b><br>
<ul style='padding-left: 30pt'>
<li>The restriction on two-handed weapons has been modified. Any melee weapon that is two-handed and heavy has a non-heavy variant at 3/4 the listed weights. both 2d6 and 1d12 weapons drop to 1d10, 1d10 weapons drop to 1d8. If a weapon has different types of Damage dice, all relevant dice drop.</li>
<li>Sleeping in armor has no negative effects and is quite comfortable but the smell starts to stand out after a while</li>
<li>Bucklers are available to all classes capable of using medium armour, as well as swashbucklers (for them to swash, as is tradition), they function as a shield, take a bonus action to draw, and provide a +1 bonus to AC instead of a +2. They weigh 1lb. </li>
<li>Unarmed strikes count as natural weapons for the purposes of making Melee weapon attacks</li>
<li>Improvised weapons count as weapons for weapon attacks. </li>
<li>Because Damage types were poorly written in 5e, and because I am including things that change their function in this setting, weapons now are capable of doing the following damage types in addition to their usual types. They can only use one at a time. Also included are other modifications. Apologies for the increased complexity
<ul>
<li>Maces, Sickles and light hammers can do 1 piercing damage</li>
<li>Some Greatclubs (though not all)  can do 1d6 piercing</li>
<li>Spears can do 1d6 bludgeoning, 1d8 versatile, and 1 slashing. </li>
<li>Some Quarterstaves (though not all) can do 1d4 piercing</li>
<li>Spears and quarterstaffs both have reach while held in two hands</li>
<li>Battle axes can do 1d6 versatile. Some battle axes (though not all)  can do 1d8 piercing, 1d10 versatile.</li>
<li>Glaives and halberds can do 1d8 piercing damage. Some halberds (though not all) can do 1d10 bludgeoning damage</li>
<li>Greataxes can do 1d6 bludgeoning, 1d8 versatile</li>
<li>Greatswords, longswords, and shortswords can all do equal amounts of slashing and piercing. Greatswords and longswords can do 1d6 bludgeoning. Greatswords are now 5lb</li>
<li>Pikes and lances (while wielded two-handed) can do 1d6 bludgeoning. </li>
<li>Pikes have a 15ft reach and have the <b>unweildy</b> property, which is <b>loading</b> but for Melee weapons instead. They also now only weigh 7lb like a sane person would expect</li>
<li>Scimitars can do 1d6 piercing, effectively making them identical to shortswords. </li>
<li>Tridents now do 1d8 piercing damage by default and 2d4 while versatile</li>
<li>(most) War hammers can do 1d8 piercing damage, 1d10 versatile. </li>
<li>There is a rapier variant, the Sabre, which can do 1d8 slashing damage or 1d4 piercing damage, finesse. A rapier can do 1d4 slashing damage</li>
<li>There is a  halberd/Glaive variant, Pollaxe, which can do 1d10 bludgeoning damage or 1d8 piercing damage and has reach. Some but not all can do 1d8 slashing damage. </li>
<li>There is another halberd/glaive variant, Longspear,  that can do 1d10 piercing damage or 1d8 slashing damage and has reach. (taking up the place of the pike)</li>
</ul>
</li>
<li><b>Special weapons</b> exist in this world and can complicate things. At a DM's discretion, a player can be allowed to have these
<ul>
<li>Lochaber axes, Kamayari, Fauchards and many such polearms have <b>hooked</b> as a property, and allow a player to, as a bonus action attempt to pull a target that is no more than one size larger up to 5 feet or prone them as part of a Melee weapon attack made on their turn. Hookswords are a shortsword that have this property. There are very few other forms of weapon that have this sort of feature because of the inconvenience of wearing or carrying them.</li>
<li>Atlatl, Amenta (amentum), and other spear-throwers can be used to double the range of Javelins, spears, tridents and darts. Drawing one follows the same rules as other weapons (so get it out beforehand). They weigh two pounds and usually cost 2 silver</li>
</ul></li>
</ul>
</p>

<p>
<b>Equipment</b><br>
<ul style='padding-left: 30pt'>
<li>Acid costs 5 gold.</li>
<li>Alchemist's fire costs 10 gold and does 2d6 fire damage. </li>
<li>Poison costs 1 gold. Not 100. </li>
<li>Holy water can be applied to weapons with the same rules as poison</li>
<li>Popular gaming sets also include Go (5s) .5lb, Reversi (5s) .5lb,, and Coup 1g - </li>
<li>Tinker's kits now include a set of screwdrivers, rivets, pliers, and other tools for modifying machinery. The skillset includes use of lathes, drifts, punches, and things for milling metal, as well as basic electronic components </li>
</ul>
</p>

<p>
<b>Machinery and Technology</b><br>
<div style='padding-left: 30pt'>
The rough technological level of the plane is similar to that of the late renaissance, just at the beginning of one of the industrial revolutions that marks the early modern era in europe
</div>
<ul style='padding-left: 30pt'>
<li>The Bessmer process and blast furnaces have been largely bypassed due to the use of magic. Firebolt is hot enough to smith with to give you an idea.
<ul>
<li>Metal refining is a fairly well understood science, as is casting and forging</li>
</ul>
</li>
<li>Lens Grinding is an ancient practice that is both practiced by hand and with magic. 
<ul>
<li>The level of refinement is enough for optical microscopes and telescopes that are equivalent to the early 1900s to function without magic</li>
</ul>
</li>
<li>Steam, internal combustion, and other thermal engines have been invented and are approximately 500 years old. They have not gotten much more efficient
<ul>
<li>while wood stoves and oil still burn normally, more efficient forms of combustible fuel often have alchemical interactions that make them useless</li>
<li>Petroleum exists but is a significant rarity, the plane lacks many of the tectonic and geologic forces necessary to form oil beds on significant scales. The Majority of the plane's oil is located in offshore sedimentary deposits that are mere thousands of years old</li>
</ul>
</li>
<li>Vulcanized rubber is a recent developement, being only about 100 years old and a well-kept secret by the Fugin Pirates</li>
<li>The Electric Motor and Alternator are in their most primitive stages and are at most 30 years old
<ul>
<li>Pressure-based and mechanically reset single-stroke motors are currently the standard. These are extremely inefficient and simply involve a large mass of metal moving (usually by being dropped) through a coil of copper wire. Most of the fuel involved in the process is for resetting the mass so it can be dropped again.</li>
<li>No one has thought to make it go in a circle yet</li>
</ul>
</li>
<li>Electric Inventions are currently limited to:
<ul>
<li>Nonmagical refrigeration which was previously made with the same concept but magical, and was much more expensive to produce</li>
<li>Incandescent Lightbulbs, Vacuum sealing and replacement gasses are far far easier with transmutation wizards. These are ineffecient but surprisngly long lasting.</li>
<li>Nonmagical electric stove ranges (these require a large battery bank to run properly, but often the battery banks themselves are sold in bags of holding)</li>
<li>Solar panels, invented shortly after the single-stroke motor, increasingly more efficient</li>
<li>Pumps driven by the single-action motors</li>
<li>Batteries - Ineffcient copper zinc, and sulfuric acid affairs</li>
<li>Capacitors - Honestly not too different from the batteries, largely used for electroplating and refridgeration</li>
<li>Dehumidifiers, If you've got a fridge, you've got a dehumidifier, remember to not let the ice build up too much</li>
<li>Induction forges</li>
<li>Electromagnets</li>
</ul>
</li>
<li>Ferromagnetism is well known and reproducible but not well understood</li>
<li>Electric field theory is in its barest infancy</li>
</ul>
</p>

<br>

<p>
<b>Magical goods and services</b>
</p>

<p>
<ul style='padding-left: 30pt'>
<li>All magical weapons native to the plane have the property of returning if thrown, it's just a holdover baked into the process for making magic items that survived since fourth edi-I mean... the dawn war. On occasion this applies to other magical items, Frequently Tea Sets, A few local legal documents, and the odd sandal</li>
<li>Spells may be purchased at a rate equal to the spell's level squared, multiplied by 10 gp, then add twice the cost of the consumed material cost, plus 10% of nonconsumed material cost for purchasing casted spells.</li>
</ul>
</p>

<p>
<div style='padding-left: 30pt'>
In general, to purchase magic items on this plane one can expect to pay these amounts. Most places do not produce cursed items for sale 
</div>
<ul style='padding-left: 30pt'>
<li><b>Common</b> 300</li>
<li><b>Uncommon</b> 3k</li>
<li><b>Rare</b> 15k</li>
<li><b>Very rare</b> 75k</li>
<li><b>Legendary</b> 200k</li>
</ul>
<div style='padding-left: 60pt'>
Many legendary items and a few very rare items are either unique (or of a limited set) or not producable at the university, one will have to construct them on their own or find them. Such legendary items include
</div>
<ul style='padding-left: 60pt'>
<li>Armor of invulnerability - hard to produce</li>
<li>Cubic Gate - extremely unlikely to function</li>
<li>Deck of many things - Illegal to produce</li>
<li>Hammer of Thunderbolts - Unique so far</li>
<li>Holy Avengers - Hard to produce</li>
<li>Luck blades can be made but the wishes must be paid for separately and waivers must be signed.</li>
<li>Manuals of Bodily health, Gainful exercise, Quickness of action, Tomes of Clear Thought, Leadership and Influence, and Understanding - <b>Upgraded to legendary, university buys copies for 75k on recharging copies, 100k for unused ones. There is a waitlist to use these items.</b></li>
<li>Rings of Djinni summoning and elemental command - Illegal to produce</li>
<li>Rods of Lordly Might - Surprisingly difficult to produce. Only two are known of on the plane</li>
<li>Spheres of Annihilation - Illegal to produce</li>
<li>Staffs of Charming - illegal to produce</li>
<li>Swords of Answering - Nearly impossible to produce, though it has been done</li>
<li>Talismans of pure good and ultimate evil - Hard to produce in <i>Manaharamu </i>though Danzuishan has had some success.</li>
<li>Talisman of the sphere - illegal to produce</li>
<li>Tomes of the stilled tongue - Uniques</li>
<li>Well of Many Worlds - Extremely unlikely to function</li>
</ul>
</p>

<br>

<p>
<div style='padding-left: 30pt'>
<b>Artifacts and sentient magic items are not allowed to be owned in Manaharamu legally, Sentient magic items are illegal to buy or sell in Danzuishan and Skalmirthon. Artifacts become property of the government. Sentient Magic Items have rights in Skalmirthon, Manaharamu, and Danzuishan.</b>
</div>
</p>

<br>
<br>
<br>

<p>
<b>Services</b><br>
<ul style='padding-left: 30pt'>
<li>Hiring coach is not a thing on this plane. Journeys between towns are long and arduous processes and the fact that there are roads is a literal miracle, often one guided by a group of clerics or paladins. A group may be allowed to join a caravan at similar prices <i>if</i> one is heading in the same direction anyway. </li>
</ul>
</p>

<p>
<b>Spells</b><br>
<ul style='padding-left: 30pt'>
<li>For the purposes of Shillelagh, Druids can target staves, greatclubs, clubs, and really anything that was grown first.</li>
<li>Water breathing now also includes protections from the water and its salinity, though not necessarily pressure.</li>
<li>Teleport, if cast at 8th level can open a portal up to 100 feet across</li>
<li>a creature being targeted by gentle repose does not need to have eyes but in fact just needs to be in contact with the two copper pieces. The denizens of the plane often carry a wristlet with two mounted copper pieces in them for just such an occasion,  but industrial versions of these bands tend to be made from wool.</li>
<li>Conjure woodland creatures and conjure animals now require the player to choose the animal, despite the sage advice stating otherwise.</li>
<li>The coefficient of friction on almost all force spells is negligible for almost all purposes, but if it comes up, say that it is variable but by default mimics glass. Allowing certain spells to be held and not, for example, for those same spells to achieve superluminal velocity</li>
<li>Ottiluke's Resilient sphere is no longer weightless. It weighs a negligiable amount. Any similar text that uses the term weightless means "a negligible amount."</li>
<li>Multiple casts of Antimagic field that end up encircling or fully encompasing an area or volume that is outside the effects of antimagic fields will cause wild magic surges if a spell is cast within 30ft of the zone, plus an additional 25ft per level of the spell.</li>
<li>Catapult can target objects that weigh less than 1lb</li>
<li>Plant growth only targets multicellular plants and only plants that are outside of a creature. </li>
<li>Saliva, tears, hair, outer epidermis and similar nonliving matter is considered to be part of a living creature for the purposes of targetting. No casting Prestidigitation on people's spit while it's still in their mouths.</li>
<li>Plane shift and banishment and other planar travel spells are limited in their function. While the Feywild, Astral plane, and the Shadowfell connect to the greater feywild and shadowfell across the multiverses. The Elemental planes here are extremely small in comparsion. Other Planes such as various heavens, mount celestia, the hells, the abyss, and Mechanus are all extremely difficult to reach due to the magic of the plane. Things being summoned might not notice a time difference between their summoning and their banishment but creatures who are here for longer than approximately a year (It's rather specific to the individual and has been as short as a week for some while others might never notice the effect) are likely to be stuck here, regardless of their power, except Gnomes who seem to be able to avoid this effect entirely. Gods are also able to come and go as they please but even they have to deal with the distance between planes as they come and go from this place.</li>
<li>Demiplane and Mordenkainen's Magnificent mansion have extraplanar spaces that function <i>differently</i> than Bags of holding, handy haversacks, and similar items. Rope trick does not. </li>
<li><b>Simulacrum is banned. The Villains win if it is not.</b></li>
<li>Unconcious people automatically grant consent <b>for the purposes of magic targetting.</b> Legally, this is not the case and using magic against an unconcious person may be seen as quite heinous.</li>
</ul>
</p>


	</div>

	<br />

	<div class='page-footer'>
		<b>Backlinks:</b>

		<a href='..\..\Nirrum's_Encyclopedia_of_Varomar.html'>Nirrum's Encyclopedia of Varomar</a>

		
		

		<a href='..\Useful_DM_Stuff.html'>Nirrum's Encyclopedia of Varomar:Useful DM Stuff</a>

		<br /><br />

	</div>

	

</div>

</body>
</html>
