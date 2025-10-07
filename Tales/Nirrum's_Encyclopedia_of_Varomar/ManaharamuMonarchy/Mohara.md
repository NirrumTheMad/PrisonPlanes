<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<title>Mohara</title>
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
	[ <a href='./Mickery.html'>Prev</a> ]

	[ <span class='insen'>Index</span> ]

	[ <a href='./Mohara/Power_Plant.html'>Next</a> ]
</div>

<hr />

<!-- Wiki content -->

<div class='pages'>
	<div class='heading'>
	<h1>Mohara <a name='Nirrum's Encyclopedia of Varomar:ManaharamuMonarchy:Mohara'></a></h1>
	</div>

	<div class='content'>
	<p>
Created Thursday 09 August 2018
</p>

<p>
<div style='padding-left: 30pt'>
Mohara, Manahara, the home of the Manahararahi. This wide and imposing mountain range (of one) has a comparatively low peak in comparison to the aegis mountains. Dumohara, the northern peak is the tallest in the range and is where Sylvanus stood when he corrupted the work of Pelor. Mohara is an ancient place, the oldest mountain on the plane, composed of foreign Quartzite. 
</div>
</p>

<p>
<div style='padding-left: 30pt'>
The Surprise here is that the Mohara Mountain is a puzzle Dungeon, built by the world spirit in co-ordination with the fey. Landing on and taking off from Mohara is easy enough via Airship, the magic breaks enough, but walking along its surface is what  triggers the magic the most. Mohara's journey will tend to begin from a mountain trail, frequently <b>the</b> Mohara mountain trail inside the university walls. 
</div>
</p>

<p>
<div style='padding-left: 30pt'>
<b>Remains largely Unaffected during the siege of Manaharamu. </b>
</div>
</p>

<br>

<h4>Mohara Mountain Trail Ascent,<a id="mohara-mountain-trail-ascent" class="h_anchor"></a></h4>

<p>
<div style='padding-left: 30pt'>
The party has the option of taking a guide up the mountain but only if they show up early in the morning before the circle of the mountain druids have left. This makes the trail up to the druid "grove" spectacularly easy, such that it should be a DC13 constitution save made with advantage to avoid exhaustion. Exhaustion gained this way can be removed with a short rest. The journey with a guide takes half an hour, an hour if someone fails the constitution check. The guides take the time to tell the party to watch for aerial predators. The druid circle is ten level 3 druids and the head of the circle of the mountain.
</div>
</p>

<p>
<div style='padding-left: 30pt'>
For those who don't  take the guide, the journey is an hour, and the constitution save made without advantage.  The air is hot but becomes slightly breezy once they climb for half of it. If the group has less than five people, Two wyverns attack. If the group has more than five people, once the Wyverns are down, three Griffons attack immediately following the most recent initative. These encounters only occur if they do not go up with the druids, who otherwise ward them off and send a message to the rangers to take care of them.
</div>
</p>

<p>
<div style='padding-left: 30pt'>
This section functions as an antechamber, letting the party know that aerial enemies are going to be prevalent. The trail is marked by posts driven into the ground and is well worn, Steps occasionally allow navigation over the more impassable rock obstacles.
</div>
</p>

<br>

<h4>Grove of the Circle of the mountain.<a id="grove-of-the-circle-of-the-mountain" class="h_anchor"></a></h4>

<p>
<div style='padding-left: 30pt'>
This druid grove is less of a grove and more of a platform, Situated some three hudred feet above Manaharamu's tallest buildings. The trail continues upward past this refuge but this is a safe spot to rest. Small mountain plants, Scraggly pines, and small bushes line this clean stone circle, in the middle of which is a standing stone inscribed in Manar. Those who know manar will be able to translate the poem, people learning Manar might be able to read aloud the script. 
</div>
</p>

<p>
<div style='padding-left: 60pt'>
<i>Naba'ti</i><br>
<i>oonwa'ta olopi</i><br>
<i>Sho ba'ti</i><br>
<i>Meikalo dal mish </i><br>
<i>Dalo ra'i ranoru'ta Hara ra</i><br>
<i>Newa'u'lo wanwilo  wa mishlia'u'lo		</i><br>
<i>Wa'u'lo wanwilo newa mishlia'u'lo	</i><br>
<i>Wanwilo Newa'ti tira  Wa'ta Hara ra </i><br>
<i>Wanwilo Newa'ta Hara, wilo Newa'ti'lo tira?</i><br>
<i>Nabrekao'ti netira'i </i>
</div>
</p>

<p>
<div style='padding-left: 60pt'>
<i>It is quiet </i><br>
<i>the sun rises</i><br>
<i>Then It is loud</i><br>
<i>The Mountain shows us </i><br>
<i>The dichotomy of change</i><br>
<i>Do when you should not</i><br>
<i>Do not when you should.</i><br>
<i>The mountain stays when everything moves</i><br>
<i>When the mountain moves, will everything stay?</i><br>
<i>Not all things are certain</i>
</div>
</p>

<p>
<div style='padding-left: 30pt'>
The view is astounding, as the Kavir'e-namak and Grass Road stretch off to the horizon, while the great civilization of Manaharamu  is dwarfed by the mountain from which it gets its name. 
</div>
</p>

<p>
<div style='padding-left: 30pt'>
Classes for the circle of the mountain take place here, and depending on when the party leaves, there might be a class ongoing. The Druid Acolytes and novices are willing to cast a version of "Ceremony" called "Walkabout" that grants the party advantage on survival checks to forage for 72 hours.
</div>
</p>

<br>
<br>

<h4>Power plant Trail<a id="power-plant-trail" class="h_anchor"></a></h4>

<p>
<div style='padding-left: 30pt'>
Druid Guides won't accompany anyone past the grove, but the trail is still well maintained, as it leads to the <a href="./Power_Plant.txt" title="Power Plant and Monastery." class="file">Power Plant and Monastery.</a> The gate to the monastery is guarded by two Androsphinxes, Og and Maj. Passing either ones test allows entry into the Monastery. Attacking either one results in a one-way trip to the Awl Inn, where the attacker must remain for a day before reappearing at the bottom of the mohara trail. Manaharamu police are frequently called in to deal with such people. Og and Maj require a quest for someone to enter the Monastery. Og Requires a Scroll on a turqoise roller that is currently In the ruins of Font in Ganglegrove. Maj requires a bell of masterful beauty that has been dipped in the waters of the secret river Acheron.
</div>
</p>

<br>
<br>

<h4>Mohara Summit trail (Lvl 7 Area)<a id="mohara-summit-trail-lvl-7-area" class="h_anchor"></a></h4>

<p>
<div style='padding-left: 30pt'>
This is where the fun begins, about twenty minutes walk away from the powerplant. 
</div>
</p>

<p>
<div style='padding-left: 30pt'>
There is very little vegetation on the summit of Mohara. Assuming it is still daylight on the first day, then the sky is pale blue and the sun is fierce. <br>
At night the stars are awe-inspiring, the moon visible becoming slowly more distant in the north sky. 
</div>
<div style='padding-left: 60pt'>
<b>This is the time for the DM to do some hot bullshit with spirit journeys, sudden reclassing and prophetic dreams.</b>
</div>
<div style='padding-left: 30pt'>
The trail winds up one small peak that serves as the beginning of the summit trail, where the party is now above the toroids that make up the power plant, and the ground is mostly rock. The wind here is extreme and it makes travel difficult, slowing the party considerably. 
</div>
<div style='padding-left: 60pt'>
<b>This disguises the fact that the summit of Mohara doesn't seem to be getting any closer, and it is considerably poweful magic that is having this effect. Trying to move off the side of the mountain seems entirely unsuccessful, as after descending, one will have to conquer a small rise that leads them back to the trail. If someone is flying, they'll always seem to get turned around, distracted from their careful measures to not have this happen. The party is in a part of the world that is very close to the shadowfell,  the border between the planes is weak along this stretch.</b>
</div>
<div style='padding-left: 30pt'>
When the party realizes this, a laughing creature, a Korred, makes its presence known. 
</div>
<div style='padding-left: 60pt'>
<i>Of course the mountaintop isn't getting any closer. You're not asking it to stay put! [greenDick voice, Idubbz]</i>
</div>
<div style='padding-left: 30pt'>
If the party tries asking the mountain to stay put, the korred laughs again
</div>
<div style='padding-left: 60pt'>
<i>Fool! Idiot! You don't speak mountain, only mountains do! Maybe it will be more willing tomorrow! </i>
</div>
<div style='padding-left: 30pt'>
The Korred disappears and party has the option of wandering around for a bit. As they wander, fog rolls in from the east, Tainted beige by the desert light. This gives the fog a sickly look and dims the light. Darkvision isn't needed to see but the sunlight sensitivity of Drow, Kobolds, and other creatures loses its potency and they are no longer at disadvantage. No creature can see past 120ft without truesight as the fog begins to obscure the landscape. The wind remains extremely high blowing from north to south, forcing creatures to spend 3ft of movement for every 1 normally spent if they move against it. Creatures moving with the wind gain an additional 10ft of movement provided they are on foot. 
</div>
</p>

<br>

<p>
<div style='padding-left: 30pt'>
Each group of the party is attacked. A separate encounter for each group if they are split, just the one if they are not.
</div>
<div style='padding-left: 60pt'>
<i>Two cow skulls are visible at the edge of the fog, green light shimmers against the fog. A wisp of cloud passes to reveal that the skulls are attached to their skeletons still, which are roughly humanoid. They weild massive Ornate dane axes. </i>
</div>
<div style='padding-left: 90pt'>
They are so large that they have a reach of 10ft and Multiattack 2, 80 hp all other stats remain<br>
<b>The Minotaur Skeletons attack quickly and try to throw the party off a small cliff that is 60 feet high. When they are defeated, their bodies fall to the ground far too quickly and slam to the rock with such force that a small cloud of dust is kicked up. When the dust clears 1d4 rounds later, A flat relief carving of half of a pathway lies where the bones should be. With both minotaurs dead, the carving should resemble a complete section, though it is obviously incomplete</b>
</div>
<div style='padding-left: 60pt'>
<i>Simultaneously (either the one group or one of the other groups) the pitter patter of running bare feet is heard. From the fog near </i><b>you </b><i>runs a Lost Sorrowsworn</i>
</div>
<div style='padding-left: 90pt'>
<b>when defeated, the sorrowsworn becomes a relief carving of the Sun but with a somewhat round chunk of it missing. </b>
</div>
<div style='padding-left: 30pt'>
If the party tries to return to the main trail, the Korred has set up a bit of a gate across it made of thin Mithril. The gate is a thin web that fits the carvings. <br>
Players need to search for puzzle pieces<br>
Everything has to make the players feel small<br>
The area has four notable features. On the south east side there is a hidden spring with purple smoke issuing from it, on the north east there is a ruined camp, on the south west side there is a small temple and on the east, a craggy crater arena.<br>
In each area the players fight something that gives them part of the mosaic. But at the end they need to put the springwater in a bowl from the temple, place it in a stand from the camp and put a crystal from the fight pits inside the bowl
</div>
<div style='padding-left: 60pt'>
In the spring they fight a <b>Marid that looks like</b> most other <b>water elementals</b> and two <b>Air Myrmidons. </b> After they beat the elementals, then a <b>Lonely Sorrowsworn</b> shows up to pull them back
</div>
<div style='padding-left: 90pt'>
They leave corner pieces of the carving that contain parts of the sky, including clouds and 
</div>
<div style='padding-left: 60pt'>
In the camp they Fight Four <b>Shadar-Kai Gloomdancer Skeletons</b> (immue to poison, blind, charm, deaf, exhaustion, frighten, poisoned, stun, Unconscious, <i>Resist Cold, necro, and nonmag Physical)</i> and another <b>Lost Sorrowsworn</b>.
</div>
<div style='padding-left: 90pt'>
They leave the carvings of the central mountain the bottom of which is missing
</div>
<div style='padding-left: 60pt'>
In the Temple they fight an <b>Eidolon With two Sacred Statues</b>, one of which <i>Grapples</i>, the other of which Breathes a cone of <i>fuckin ghosts that works a lot like an Adult Dragon's Breath.</i>
</div>
<div style='padding-left: 90pt'>
The sacred statues leave each of the bottom corners showing the mountain on each side of the pathway
</div>
<div style='padding-left: 60pt'>
In the Crater They fight one <b>Hungry Sorrowsworn and 6 Wretched Sorrowsworn</b>
</div>
<div style='padding-left: 90pt'>
These leave only tiny fragments, an Image of the part in extreme detail as well as an image of the whole gate, which yes, contiains an image of the whole gate, though the second image of the gate lacks the adventurers, magic only goes so far guys.
</div>
<div style='padding-left: 60pt'>
Each attempt at a long rest prompts a 75% Random encounter with an <b>Angry Sorrowsworn, and by 75% I mean the first two attempts are Automatic. Punish that shit</b>
</div>
<div style='padding-left: 30pt'>
When the gate is completed, there is a small flash of light  vertically along the center of the carving, which slides apart, as it does, the fog clears, revealing the summit, beckoning in the pale morning light. Looking around, the party will notice they really aren't far at all from the power plant, the two sphinxes clearly visible as they wander around the sides, A DC12 survival check reminds them that it is a long way to the summit. A Kirin Crosses the trail, stops for a moment to look at them, and then darts away across the sky, granting everyone present a Charm of heroism as described on DMG228. The gate fades and the Korred appears briefly behind the party to laugh a bit as it too fades. In a matter of seconds, it's as if the whole thing never happened though the land features such as the camp are still there. At each one, if the party goes back to look, are single large Gemstones. 
</div>
</p>

<br>
<br>
<br>

<h4>Mohara Summit<a id="mohara-summit" class="h_anchor"></a></h4>

<p>
<div style='padding-left: 30pt'>
The trail past the gate is remarkable only in its view, As the summit draws closer and manaharamu moves further away,  the party will need to find  ways to procure water and food as there is none of it on top of the mountain. The weather is extremel cold though snow does not tend to build up until a few days up the trail. If a creature does not have a way to stay warm, they require a DC 10 constitution check every <b>hour</b> in order to avoid levels of exhaustion. Creatures who are resistant or immune to cold automatically succeed this check, as do creatures wearing cold weather gear. In Most cases, Heavy armor is considered cold weather gear. Ask your player to describe what their armor looks like and judge fairly. Three uses of prestidigitation is enough to sustain the warmth of one creature.
</div>
</p>

<p>
<div style='padding-left: 30pt'>
On the way over the top, the Party will run into a pack of 6 wolves. Whenever a wolf reaches 0hp, it turns into a Kholirahi Elite Rudmage.
</div>
</p>

<p>
<div style='padding-left: 30pt'>
<b>Mohara Summit is of course the nesting ground of a Roc, which has built its nest but hasn't found a mate yet, but that journey is days of walking and camping away. If the party is above level 13, then this Roc is an Ancient Red Dragon instead. Good luck. When either is defeated if the party returns they will find am Ancient Silver Dragon roosting there instead.</b>
</div>
</p>

<br>
<br>

<h4>Mohara Trail North<a id="mohara-trail-north" class="h_anchor"></a></h4>

<p>
<div style='padding-left: 30pt'>
The Trail on the north side of Mohara is easily one of the most gruelling trails in the world on the way up and one of the most pleasant on the way down. Descent from the peak side of the Mohara Range takes about two hours.
</div>
</p>

	</div>

	<br />

	<div class='page-footer'>
		<b>Backlinks:</b>

		<a href='..\ManaharamuMonarchy.html'>Nirrum's Encyclopedia of Varomar:ManaharamuMonarchy</a>

		<br /><br />

	</div>

	

</div>

</body>
</html>
