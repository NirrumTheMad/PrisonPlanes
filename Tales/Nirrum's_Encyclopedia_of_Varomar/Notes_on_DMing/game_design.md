<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<title>game design</title>
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
	[ <a href='./Eldritch_Blasts.html'>Prev</a> ]

	[ <span class='insen'>Index</span> ]

	[ <a href='./game_design/5_room.html'>Next</a> ]
</div>

<hr />

<!-- Wiki content -->

<div class='pages'>
	<div class='heading'>
	<h1>game design <a name='Nirrum's Encyclopedia of Varomar:Notes on DMing:game design'></a></h1>
	</div>

	<div class='content'>
	<p>
Created Friday 23 November 2018<br>
<a href="./game_design/My_game.html" title="+My_game" class="page">+My_game</a><br>
<a href="./game_design/5_room.html" title="+5_room" class="page">+5_room</a>
</p>

<br>

<p>
Movement should feel uninterruptable and with enough skill, should be exactly that<br>
you honestly shouldn't notice that you're playing a game<br>
LEvel flow should be simple, <br>
Unconver next chapter if you use a hubworld<br>
Lower numbers<br>
<b>SLOW, ULTRA BAD</b><br>
<b>INERTIA GOOD</b><br>
Need reward for filler mechanics<br>
Telegraph upcoming challenges<br>
Enemies should always have purpose and be compelling<br>
LEvels should be linked by mechanics more than theme<br>
openness vs focus. Open world vs rails. <br>
USe open as hub, rails as spoke<br>
<b>Cutscenes are wait time. Only for exposition. GIve it a timer</b><br>
Rewards should be rewarding <br>
Figure out what is the most rewarding reward and what its value is.<br>
when the level changes or a new area is revealed. of the player says "I did that" then you've done well<br>
No getting kicked out of the level after obtaining an objective.<br>
<b>don't stop a player from making their own fun</b><br>
<ul>
<li>Make movement sweet</li>
<li>make environment sweet</li>
<li>Let'em loose</li>
</ul>
Sound Design<br>
BIG IMPACT <br>
Realistic =/=Immersive<br>
The difference between reality and your in-game representation of it is a representation of how you interpret the world. <br>
Directions and goals matter<br>
Environmental immersion vs mechanics
</p>

<p>
<b>If I can forget the controller, then it's a good day</b><br>
sweet flow state<br>
<div style='padding-left: 30pt'>
High difficulty &amp; low skill is anxiety<br>
High skill and low difficulty is boredome<br>
Fuse the two
</div>
</p>

<p>
really, players want a seamless flow between their information and their ability to react to it
</p>

<p>
See but can't access<br>
players need to think that if they look somewhere they'll be rewarded for their effort
</p>

<p>
If you go with a skill tree, make it a build, make it so that choices matter
</p>

<br>
<br>

<p>
Hubworlds serve as a training ground, teaching basic concepts as <b>Part of the tutorial</b><br>
Communicate themes and story elements <br>
*repeated central theme of the story* ala chorus<br>
hubworld keeps people playing by providing low-stakes pacing<br>
HALO WAS REALLY GOOD AT PACING compared with toom 2016<br>
have things to do in the hub world<br>
change the hub to change the tone *recontextualizing ideas and opinions*<br>
Conceptual foundation<br>
Emulsification showcase
</p>

<h3>Balance<a id="balance" class="h_anchor"></a></h3>

<p>
Balance between luck and skill for audience
</p>

<h3>vs BAd sequels<a id="vs-bad-sequels" class="h_anchor"></a></h3>

<p>
big empty worlds, too little over too much<br>
doesn't know what game it is<br>
<div style='padding-left: 30pt'>
see "design by subtraction"
</div>
</p>

<p>
NON(Unique and interesting NPCs)
</p>

<h4>Bad design choice<a id="bad-design-choice" class="h_anchor"></a></h4>

<p>
Test and see how <b>little</b> 
</p>

<br>

<p>
PUT NOTES ON MAP
</p>

<h3>Level design and story<a id="level-design-and-story" class="h_anchor"></a></h3>

<br>

<p>
Set dressing Environmental storytelling. <br>
Staging player-space with environmentla properties that can be interpreted as a meaningful whole, furthing the narrative of the game<br>
Requires a level of deductive reasoning<br>
<div style='padding-left: 30pt'>
Archaeological skills
</div>
<div style='padding-left: 60pt'>
determine relationships<br>
cause-and effect<br>
history
</div>
<div style='padding-left: 30pt'>
Makes the person an active participant in the narrative instead of passive<br>
doesn't get in the way of gameplay
</div>
overheard conversations<br>
item descriptions<br>
scans, notes, emails<br>
animations <br>
graffiti
</p>

<p>
usually describes what happened before you got there, sometimes describes how you have effected the world
</p>

<p>
can be used for tutorial or mechanic hints
</p>

<br>

<p>
Sets also matter.<br>
<div style='padding-left: 30pt'>
Level design<br>
Architecture, layout, materials, scale,<br>
Opulence, verticality (metaphor, poor under rich)
</div>
 believable spaces allow people to intuit procedure<br>
<div style='padding-left: 30pt'>
necessary things like bedrooms bathrooms, lore stuff<br>
Maybe difficult, might not make sense.
</div>
</p>

<p>
Overall setting of the world, worldbuilding, lore<br>
<div style='padding-left: 30pt'>
timeline, factions, history, 
</div>
</p>

<p>
Every level of representation should be referring to the same thing<br>
Make sure teams come together to make sure vision is shared
</p>

<p>
setting can be used to create emotion (such as caves or crevices causing feelings of pressure)<br>
<div style='padding-left: 30pt'>
Very much analogous to art design and composition. <br>
Colors make a massive difference
</div>
</p>

<p>
Emotion charts and intensity charts<br>
<div style='padding-left: 30pt'>
Emotion charts
</div>
<div style='padding-left: 60pt'>
Break a level down into sections (based on events or progress)<br>
determine the theme for each secion<br>
Match the theme with the intended emotion<br>
Use environment design to evoke those emotions<br>
"In the __<u> you should feel</u>_ so your senses reveal____"
</div>
<div style='padding-left: 30pt'>
Has to gel with the game mechanics. Darkness for horror might be scary or safe in stealth games
</div>
</p>

<p>
<div style='padding-left: 30pt'>
"__<u> evokes</u>_ by making you ____"<br>
Intensity charts
</div>
<div style='padding-left: 60pt'>
find desired intensity levels per section (as above) 	Hoping for low in story, high in combat<br>
Check against playtesters<br>
Perhaps use tradition story structures
</div>
</p>

<p>
Journey is an excellent example of environment storytelling
</p>

<br>

<p>
For stealth public and privated spaces<br>
separated from vague rules to strict rules (societal expectations)
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
