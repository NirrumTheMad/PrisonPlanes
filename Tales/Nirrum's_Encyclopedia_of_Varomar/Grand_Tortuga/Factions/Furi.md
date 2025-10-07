<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<title>Furi</title>
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
	[ <a href='./Fugin.html'>Prev</a> ]

	[ <span class='insen'>Index</span> ]

	[ <a href='./Hatain.html'>Next</a> ]
</div>

<hr />

<!-- Wiki content -->

<div class='pages'>
	<div class='heading'>
	<h1>Furi <a name='Nirrum's Encyclopedia of Varomar:Grand Tortuga:Factions:Furi'></a></h1>
	</div>

	<div class='content'>
	<p>
Created Thursday 07 June 2018
</p>

<p>
Ship Furi<br>
<div style='padding-left: 30pt'>
While it is worth noting that many of the Furi on the Island are tiefling, not all of them are. On the overworld, less than 1% are tieflings. The Tieflings are rare overall, The majority of them are native and somehow related to Orsithach. The reason for the extreme concentration of them on the island is their Innate ability to access unique magic that aids them in Controlling and manipulating the pirate clans around
</div>
</p>

<p>
<div style='padding-left: 30pt'>
Leaders
</div>
<div style='padding-left: 60pt'>
Lagarach Munsa ENTP Monk
</div>
<div style='padding-left: 90pt'>
Þe Furi Family Representative is a Tiefling wiþ medium horns þat curve slightly up, running roughly parallel. He has medium lengþ silver hair in a short ponytail. His skin is Crimson and his eyes gleam Green wiþ pink streaks. He constantly has a supressed smile, as if he can barely contain it. He carries no weapon and dresses plainly in white shirts and brown pants. He Does wear an obviously magical circlet, but no one knows what it does, he is 6'0 exactly. Anyone who attunes to the circlet finds themselves capable of looking through clothing and with a bonus action, changing elements of someone's clothing to be opaque. The circlet is shrouded in hundreds of countermagical charms and is functionally indestructible, and utterly untouchable by all but the most complex magic. 
</div>
</p>

<p>
<div style='padding-left: 60pt'>
Orsithach Furi, ENTJ
</div>
<div style='padding-left: 90pt'>
The patron of the Furi Clan, Leader of the overworld mafia, probably the most duplicitous being in the world. He is 5'8. He wears white robes suitable for his desert home in Dwallat. It would require something of the highest importance for him to come to dwallat personally. He grins subtly and smugly. He is also the heir of the Native Tiefling Clan, descent of their first king, The First Red Sinner which, depending on how you pronounce it also means "the angry smiling animal", This is the origin of their namesake, Furi, Meaning first, red, angry, and animal. 
</div>
</p>

<p>
<div style='padding-left: 30pt'>
Important Members
</div>
<div style='padding-left: 60pt'>
Biero, INTJ, Battlemind
</div>
<div style='padding-left: 90pt'>
A calm and calculating human, who is scretly a psionic assassin. He is loyal to the furi. He wears a breasplate and wields a longsword and passes as a fighter
</div>
</p>

<p>
<div style='padding-left: 60pt'>
Mogora Tam ISTP
</div>
<div style='padding-left: 90pt'>
This pollaxe wielding Tiefling Paladin is actually the leader of the footmen, and is an adept footman himself. He has rage problems, wears bronze dragonscale armor, and smiles a toothy smile that clearly has poor intentions
</div>
</p>

<p>
<div style='padding-left: 60pt'>
Burthar Mangac INFJ
</div>
<div style='padding-left: 90pt'>
A winged tiefling Fighter with a flail that manages the guards for the Shivering Spine, which houses the Furi's compound. He is perpetually staring into the night with a grim and suspicious look. 
</div>
</p>

<p>
<div style='padding-left: 60pt'>
Ongrum Bonesnap ESTP
</div>
<div style='padding-left: 90pt'>
A blonde sun elf prostitute, raised by orcs, Decadent and hedonistic to an extreme, but professional when it comes to keeping her job. Entirely shameless. 
</div>
</p>

<p>
<div style='padding-left: 30pt'>
Trump:
</div>
<div style='padding-left: 60pt'>
The panic switch. A lever in Lagarach's personal quarters that, if pulled, summons the Furi Army. 
</div>
</p>

<p>
The Shivering spine<br>
<div style='padding-left: 30pt'>
-NO WARFORGED, SHARDMINDS, IF YOU DON'T NEED TO EAT YOU'RE NOT ALLOWED IN- <br>
Low south, a large building with Hobgoblin Architecture (Japanese), well lit by paper lanterns, It has wide windows that function as displays for their wares, prostitutes and drugs, and as rooms that are available should anyone want an audience. The building is supported by concrete, and the walls on the outside that aren't glass are mirrored (and reflect magic). It has one entrance from which the smell of incense wafts. Two wide sliding doors that are guarded by two Furi Footmen. Just inside the door is a small room that contains a Furi Mobster as backup. There is a short hallway that is bifurcated by a triangular desk, behind which is an entirely naked attendant (choose their gender and race by rolling or something) The attendant gets incomers to sign their name on a large tome nearby the desk. It is enchanted so that someone cannot lie about their name. The large, well-worn hallway to the left is plaster walled and has red floors worn away to show time-polished wood. Six footmen demand that everyone leaves their weapon in a weapon check. Then, two doors that swing in open up to reveal a large, square room. All around, patrons, prostitutes, Drugs, drinks. The center the room is an open set of steps and booths that lead down into a large pool of what is clearly wine. The walls are more private booths that are separated by bead curtains. There are even more private rooms in behind where prudish patrons can partake in the vices offered. Patrons are offered food, drugs, and drink on the same menu by perceptive attendants who attempt to discern their animal tastes. There are occasional pickpockets, some of them house-employed, who try to lift weapon checks. Anyone who gets caught gets dragged into a specific room and isn't seen from again. The Red and beige paint and bright yellow light from the incandescent bulbs mounted in the ceiling give a cozy feeling to the fairly large room. There are usually about 30 patrons, and about 14 staff.
</div>
</p>

<p>
<div style='padding-left: 60pt'>
MENU
</div>
<div style='padding-left: 90pt'>
Meats
</div>
<div style='padding-left: 120pt'>
Beef<br>
Pork<br>
"phoenix"<br>
Chicken<br>
Crab<br>
Elk
</div>
</p>

<p>
<div style='padding-left: 90pt'>
Sauces
</div>
<div style='padding-left: 120pt'>
Pineapple reduction (sweet and sour sauce!)<br>
Coconut and butter<br>
Honey<br>
Chocolate<br>
Gravy<br>
Mokoijo sugar (an extremely savoury spice from the east that when warmed is liquid, but very rapidly takes on a brittle crystaline consistency as it cools. Despite its name, it is not sweet)<br>
Sweet Ghost Pepper (Con saves of 13 are required to not succumb to the poisoned condition for ten minutes, being resistant or immune to poison negates this effect)<br>
Dry Ghost Pepper (Con saves of 13 are required to not succumb to the poisoned condition for ten minutes, Being resistant or immune to poison negates this effect)<br>
Wraith pepper (upon eating this sauce, the patron takes 1d6 damage every bite unless they are resistant or immune to poison, or have a constitution score over 15)<br>
Whale Cheese Sauce<br>
Fish Sauce<br>
Tamarind sauce
</div>
</p>

<p>
<div style='padding-left: 90pt'>
Side Dishes
</div>
<div style='padding-left: 120pt'>
Infernal Curry (Clove oil, Chili peppers, walnuts, Cured Porkbelly, Cardamom, black pepper, Melted Chocolate, allspice, Oregano, Toasted lemon)<br>
Coconut Curry <br>
Surf Curry (green Sea Turtle meat and a special type of seaweed starch, butter, shrimp, Corriander, Cardamom, Cumin, and Mango Vinegar) <br>
French Fries (the attendants will not respond if anyone asks what a french is)<br>
Pickled Mango snacker (pieces of pickled mango in oil, salt, vinegar, with a mix of spices<br>
Pork Scrunchions<br>
Fruit bowl (Mango, Honeydew melon, Dates, Pineapple slices)<br>
Onion rings<br>
Savoury Dressing<br>
Poutine
</div>
</p>

<p>
<div style='padding-left: 90pt'>
Drinks (+5g laced with something mindboggling)
</div>
<div style='padding-left: 150pt'>
Furi Select (red) 10g bottle<br>
Vi'Namak (merlot)					<br>
Ilfea blend			
</div>
</p>

<br>

<p>
<div style='padding-left: 120pt'>
Braided Mead 12g bottle
</div>
<div style='padding-left: 150pt'>
Mystic Metheglin (Rhododendron, Hallucinogenic)<br>
Melomel<br>
Cyser<br>
Dry<br>
Spiced<br>
Marijuana Metheglin
</div>
<div style='padding-left: 90pt'>
Substance
</div>
<div style='padding-left: 120pt'>
Cocaine 10g/gram<br>
Psilocybin 5g/gram<br>
Shaman Suicide Dust 6g/gram 				<br>
Tobacco/Marijuana 4g/kilogram<br>
Fisher's Tobacco 4.6g/kilogram<br>
Farsight Pollen 2g/dose (actually made from a frog, gives prophetic visions of the best possible future but is extremely addicting (con save 25) so the second dose mostly just shows how to get the next dose. The Furi keep a tight grip on its production and thus all of the addicts to this drug end up working for the furi.
</div>
<div style='padding-left: 90pt'>
Enchantment
</div>
<div style='padding-left: 120pt'>
10g/hour
</div>
<div style='padding-left: 90pt'>
Other serivces
</div>
<div style='padding-left: 120pt'>
5g/hour
</div>
</p>

<br>

<p>
<div style='padding-left: 30pt'>
The Right hallway from the front desk leads directly to private rooms with the same amenities. Rooms are 10 gold a night, and most services are 5 gold an hour, and strict tabs are kept, although not always accurately (and never against the favor of the establishment), people unable to pay are blackmailed, beaten, killed, or on occasion, hired. The Furi offices are underground behind the secret wall panel of one of the rooms, which only one prostitute uses, as she is the only trusted one. Ongrum Bonesnap is always within arms reach of a hidden poisoned dagger Ready to assassinate the customer that is unlucky enough to be in the room when the Furi Enter or Leave, they rarely use that entrance, only for deals that need to be made quickly. For their protection there is a Curtain drawn across the wall-mounted bunk that obscures the rest of the room. Most of the thugs get their assignments at the door and the Higher-ups get teleported in by attendants who know the spell. At the end of the right hallway is a staircase leading up to the furi Dorms, and another leading to the kitchens. The furi dorms have a back entrance that leads into Remesari circus and it is constantly bustling with Various mobsters and footmen of all races, each passes a check at the door by a hedge-mage who uses detect thoughts on them. 
</div>
</p>

<p>
<div style='padding-left: 30pt'>
The Furi offices are a network of tunnels that run deep, and, at one point, hitting the underdark, where the Furi Railway carries their members back and forth to Dwallat. The tunnels are collapsible, and were built specifically to trap enemies. The Offices contain slaves doing paperwork, A few high-level magic items, Weapon stores, and running drugs. They also contain the "panic switch" which is hit if the Furi Presence on the island is in danger. 
</div>
</p>

<br>

<p>
<div style='padding-left: 30pt'>
sorry frugbach
</div>
</p>

	</div>

	<br />

	<div class='page-footer'>
		<b>Backlinks:</b>

		<a href='..\Factions.html'>Nirrum's Encyclopedia of Varomar:Grand Tortuga:Factions</a>

		<br /><br />

	</div>

	

</div>

</body>
</html>
