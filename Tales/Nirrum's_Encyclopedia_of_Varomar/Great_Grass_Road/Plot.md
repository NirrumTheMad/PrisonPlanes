<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<title>Plot</title>
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
	[ <a href='..\Great_Grass_Road.html'>Prev</a> ]

	[ <span class='insen'>Index</span> ]

	[ <a href='..\Group_Patrons.html'>Next</a> ]
</div>

<hr />

<!-- Wiki content -->

<div class='pages'>
	<div class='heading'>
	<h1>Plot <a name='Nirrum's Encyclopedia of Varomar:Great Grass Road:Plot'></a></h1>
	</div>

	<div class='content'>
	<p>
Created Friday 01 June 2018
</p>

<p>
<b>This is a place to put plot, in one story it was intended to look like this:</b>
</p>

<p>
Travelling east from Xia Ochiko in search of the thief that stole from them, the party ends up travelling through the great grass road. La Volpe Rex is an expert at hiding and has no difficulty making her way through the grass unseen by most creatures. She does sleep at night, but lightly, and she disguises herself under a mound of earth.
</p>

<p>
It is worth noting that if there is a ranger in the party, that 13-19 will show up about 1/2 the time if they're concentrating for a minute and they can detect Humanoids. The sounds, magical semblance, and otherwise uninterrupted line of sight is explanation enough for this. Flip a coin, and if the flip is in party's favour, roll a D8, 1-4 for gnolls, 5-7 for Orcs, 8 for halfling ramishi. (Or roll a d16 and ignore any result over 8, your choice)
</p>

<p>
Travel is taken by the hour<br>
Because the Region is so dense with life, the random encounter table looks like this<br>
1d20:<br>
1-5: A random herbivore herd:  10 Horses, 10 Elk, 3 camels, or 6 elephants,  All of these are wary of but nonaggressive to the party<br>
6:  5 Axebeaks which are assertive of their space but won't attack if the party backs off or goes around<br>
7: 2 Ankheg<br>
8: 2 Griffons<br>
9: 1 manticore<br>
10: 2 Cockatrices<br>
11: 1 death dog or 1 rhino<br>
12: 8 hyenas or 3 Lions<br>
13-16: 8 Gnolls and 1 Gnoll Pack lord<br>
17-18: 6 Orcs, 2 warcheifs <br>
19: A Ramishi scout party of 2 scouts, which are friendly to the party, guiding them to the camp<br>
20: Young Blue Dragon
</p>

<p>
Roll this  once per six miles if the party's travel pace is slow, Once per three miles if they move at a normal pace, and twice per three miles if they are moving fast adding the two encounters together. If a 12 and a 13-16 are rolled together, the 12 will always be hyenas which are friendly to the Gnolls. Any creature killed in that combat gets eaten by a hyena, turning that hyena into a fresh gnoll at the end of the turn.<br>
<ul>
<li>Survival checks for food are easy 10 to get enough food for one creature in an hour, 15 to get enough for a party of four. nearly all plants in this area are edible, though the grains all require processing, usually by grinding or boiling. </li>
<li>Survival checks for water are hard. A DC 15 check is enough to find water for one person for a day from plants, a DC 25 check to find a water source. </li>
</ul>
<div style='padding-left: 30pt'>
   Both sets of checks are reduced by 10 if the party has a map with notes, a guide, or someone native to the region. A worshipper of Pelor or a god of agriculture has advantage on these checks.
</div>
Roll on the random encounter table once per watch <i> 1-6, 8, 10 and 12 on the encounter table are replaced with nothing when it is nighttime, as those animals tend to be asleep or occupied with other things. . </i><br>
<ul>
<li>Roll twice per watch if they have a fire. That light draws attention. Soft Orange against the pale blue of staggering night</li>
<li>The survival check for having a fire that doesn't cause a flashfire is a DC12, and everyone can make that check. If the party does start a flashfire, they take 2d10 damage for each round they stand in or pass through flames. Flames burn out after two rounds but also spread 15 more feet. Most flash fires will diminish in minutes if there is no wind, but may sweep far if there is wind. The grassland will survive, it always does. Building a sufficiently wide trench or having a metal pot or similar containment can keep the fire from spreading at all.</li>
</ul>
Night on the steppe depends on the weather. It is usually cold but not cold enough to need checks if they have at least one blanket. The sky is frequently Amazingly clear, Showing the stars in all their glory and malevolence. If you keep track of the moon phases, on nights when there is no moon, strange but beautiful singing can be heard across the steppe. The Lyrics are in Orcish, describing the mighty weight of the sky, and how heavy it must be, and how tired that must make it. The sky should stay up for a while, so the great gruumsh can defeat it standing, not laying down. If the moon is visible, creatures with darkvision can see as far as they'd be able to see in the daylight. Roll a d6 and on a 5-6, the moon is not visible.<br>
<ul>
<li>Creatures would do well to not look at the moon. If it is full, then staring at the moon will force a DC25 Wisdom save. On a failed save, the creature is stunned until its view of the moon is broken, even for only an instant. Staring at the moon with a telescope or similar device forces a DC20 constitution save as well, doing 2d10 psychic damage on a failed one, nothing on a success. See Notes on cosmology. </li>
</ul>
</p>

<p>
There are many Ramishi camps around the steppe. When the party is found the nearest one is just far enough away for the time to auto-set to dusk, or an hour away after dusk. They have a small fire inside of a yurt with approximately ten Ramishi inside, There is not much extra room. If the party needs to cook, they must do it in here, but there is only room for one more person. But the party must also sleep outside, as there is no more room in the yurt. The party should be relieved at this point to not have to keep watch over night, as the scouts do so themselves. The first night with the ramishi is clear, so clear that <b>even though it is night, the stars and moon cast dim light. </b><i>The party might wake up once or twice to the sound of fighting if the Ramishi get a random encounter.  1-6, 8, 10 and 12 on the encounter table are replaced with nothing, as those animals tend to be asleep. The ramishi will tend to encounter things farther out from the camp, and two scouts and an outrider with a horse will be in on the fight, the outrider being as close to the yurt as he can (range 600ft)</i>
</p>

<p>
The Ramishi will ask the party to help them deal with the Orcs and gnolls and they will guide them to Manaharamu. They also offer to keep an ear out for the thief.
</p>

<p>
<b>If the party Causes trouble for Broomb and she escapes, She reconvenes and calls her coven to use their ultimate weapon. In a dark ritual, held in deep secret under a hillock at the edge of Kavir-e-namak, they summon Yeehongu, the beast of butchery (MToF,154). They cast him onto the surface above him and banish him after a week. They put a curse on those they hate that acts like a mosquito to Yeehongu's attention, drawing him toward them. This is usually enough to deal with their threats or at least scare them out of the region but it invariably ends up creating a new army of gnolls, Double gnoll encounter size for two months thereafter.  At the end of each week, roll a d20, and on a 20, 'Neatsumiku from the university of Manaharamu shows up to deal with this problem himself.</b>
</p>

<p>
Upon meeting the Ramishi, Deloch is greeted in Manar<br>
 Cheva! n<i>ekao'u, Prabraha.  Manakemarahi Dal Kaolat Nnelyss'tilo</i><br>
<b>Lisrau, Ramishi. Dala Newa brekao'a. Rau sho Rati Ramishi Skalmirthon Lata'a, Kaolat Manaharamu  shalti ra'a</b><br>
 <i>Shet Pinralisraha Persephone...</i>  <br>
<b>Shora'i'ab, Mishali Lyssrahita'ab, Bata, shet lyssrahita</b><br>
  <i>Pinralisraha Deloch, wa'u sho kao'u. Betganra Manaharamu'ti, sho mishali ta rahi dal kaolat dalu doolat kaobeti'lo. manakemarahi Kholiti'ab tab </i><br>
<b>Shet-</b><br>
 <i>WAU! Dal Manaharamu Kemahirahiu, Prabraha, dal ra N'ara'ab... wanlo.... Ta Rahi Wira0i?</i><br>
<u>Deloch Grins</u><br>
Ta<b>Parmishi'ti </b><br>
 CHEVA! <i>Ta</i> <i>Draparhi'ti dal Rau! Parmis-</i><br>
<b>Dala newa Brekao'a! Sholo, Mananwa'a'lo </b>(He stops if he notices the party listening)<br>
 <i>Mananw</i>- Agh! <i>Nawabeu</i>'ab! <i>Mishali Alabetu'ab!</i><br>
<b>pffffft Neeeeeeeeeeeeeeeeeeeeeeeeeee</b><br>
 <i>Wa! RA!</i>
</p>

<p>
Near the end of the Grass Road, A single sick man can be heard from the side of a slightly more well-worn cart trail. When he sees the party, he attacks. It is an <a href="./NPCs/Wandering_Bosses.txt" title="Ensorcelled Trussari" class="file">Ensorcelled Trussari</a>
</p>

<br>

<p>
<b>What has actually taken place</b><br>
The great grass road proves to be a bit of a <b>slog</b> with the only notable features being random encounters, between the ranger and the cleric they are good on food and water. Tala, the tortle ranger has heard the orcish singing in the night, so hopefully this is going to be more interesting with someone taking charge.  I will increase the number of powerful orcs in Broomb's camp
</p>

<br>

<p>
<a href="..\ManaharamuMonarchy\Plot.html" title="ManaharamuMonarchy:Plot" class="page">ManaharamuMonarchy:Plot</a><br>
0
</p>

	</div>

	<br />

	<div class='page-footer'>
		<b>Backlinks:</b>

		<a href='..\Great_Grass_Road.html'>Nirrum's Encyclopedia of Varomar:Great Grass Road</a>

		<br /><br />

	</div>

	

</div>

</body>
</html>
