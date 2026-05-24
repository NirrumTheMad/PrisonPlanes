<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<title>Plot_Notes_Midgard</title>
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
	[ <a href='./Plot_notes.html'>Prev</a> ]

	[ <span class='insen'>Index</span> ]

	[ <a href='..\Power_Plant.html'>Next</a> ]
</div>

<hr />

<!-- Wiki content -->

<div class='pages'>
	<div class='heading'>
	<h1>Plot_Notes_Midgard <a name='Nirrum's Encyclopedia of Varomar:ManaharamuMonarchy:Plot:Plot Notes Midgard'></a></h1>
	</div>

	<div class='content'>
	<p>
Created Tuesday 26 June 2018
</p>

<br>
<br>

<p>
To start, we must set up the plot<br>
The Kholirahi are prodding the outer edges of the Manarahi defences. Their recent experiment has proved that their roots can reach even the Trussari and cause madness from within. The Manarahi are oblivious to this but careful, and this care may be their downfall.
</p>

<br>

<p>
The kholirahi actions are as follows:<br>
<div style='padding-left: 30pt'>
Set up camp on the north side of mohara, disguised as a flock of Eagles. There are not many overall and all of them are elites.
</div>
<div style='padding-left: 60pt'>
Some students or travellers will go missing on the northern Mohara trail
</div>
<div style='padding-left: 30pt'>
Contact and infiltrate Kobetgan
</div>
<div style='padding-left: 60pt'>
run initiation
</div>
<div style='padding-left: 30pt'>
Destabilize Manaharamu infrastructure
</div>
<div style='padding-left: 60pt'>
Attack the pial<br>
Weaken the walls<br>
weaken the Mythals that protect Manaharamu<br>
Interrupt the northwestern Leyline<br>
sabotage the Power Plant<br>
Defeat and control the Manarahi aescetics
</div>
<div style='padding-left: 30pt'>
Destabilize the Manahararahi politically
</div>
<div style='padding-left: 60pt'>
Defame the queen<br>
Assassinate one of the lawyers<br>
Eliminate any or all of the military leaders
</div>
<div style='padding-left: 30pt'>
Infiltrate the university
</div>
<div style='padding-left: 60pt'>
They have actually already done this through the changeling cult.
</div>
</p>

<br>

<p>
The final battle will be against a small Kholirahi squadron<br>
8 rudmages<br>
5 elites<br>
1 captain
</p>

<br>

<p>
Our heroes struggle to find the location of their theif while contacting the criminal underworld. They intend to spend their money on treasure and there will be plenty of Opportunities for that, once they have it back. 
</p>

<br>

<p>
The most important people here are 
</p>

<br>
<br>
<br>
<br>

<p>
<b>Square of the spell level multiplied by 10 gp plus DOUBLE of the consumed material cost plus 10% of nonconsumed material cost.</b>
</p>

<h2>Gaius<a id="gaius" class="h_anchor"></a></h2>

<p>
Gaius is Kholirahi. A Kholirahi prince no less, spawn of the Godking. He will be tailed by the trussari and prevented from accomplishing his goals under the suspicion that more power for the Kholirahi in any way is more the Manahararahi have to deal with.<br>
<div style='padding-left: 30pt'>
<b>The Trussari has noted that Gaius is Kholirahi, and regards him with distrust, he will alert the others.</b>
</div>
</p>

<p>
<div style='padding-left: 30pt'>
<i>For being who he is and being on the quest he is on, Nirrum wishes to grant a Sword of Blighting to Gaius. It is a +2 Longsword with the mark of Urhuz Lomak on it. It does maximum damage against plants and nonmagical plants wither at its touch.</i>
</div>
</p>

<br>

<h2>Vaylen<a id="vaylen" class="h_anchor"></a></h2>

<p>
Her goal is to find her way to the looms of the college of Glamour. She is not aware that it is her cousin, Aralc, Archfey of Eyes, who runs it. Aralc is likely to oust her cousin's disguise unless she comes alone. <br>
<div style='padding-left: 30pt'>
<i>She is an archfey, and exclusively capable of wielding great powers from the feywild, and diametrically opposed to the raven queen. A cloak of Arachnida is a good choice of item for her to get from Aralc</i>
</div>
</p>

<br>

<h2>Tala<a id="tala" class="h_anchor"></a></h2>

<p>
Tala seeks her brother and her life of luxury, she will be able to find him somewhere in the library, but getting in is going to be a problem for a fighter. Only her ranger skills will be of value here. Tala has the most money but her companions will be jealous of her wealth when faced with the magic items they can buy<br>
<div style='padding-left: 30pt'>
 <b>2840 for clone, x2 is 5680, 490 for Regenerate which takes 2 minutes to heal the clone effects</b><br>
Advertised as 3330 for one, costs 6170 for two
</div>
</p>

<br>
<br>

<h2>Sparkles<a id="sparkles" class="h_anchor"></a></h2>

<p>
The Fairy's goals are shrouded in mystery, and by mystery I mean unengaged player attitude. Loves causing shit though and there's plenty of opportunity for that. <br>
<div style='padding-left: 30pt'>
<b>Abby Has been having fun with less people in the group. </b>
</div>
</p>

<p>
<div style='padding-left: 30pt'>
<i> The Evocation head, Ridicully Cosades had a set of Mithral Efreeti chain made as a joke that's just small enough for sparkles. It's value would be astronomical if it worked for anyone else.</i>
</div>
</p>

<br>

<h2>Henry<a id="henry" class="h_anchor"></a></h2>

<p>
He just wants a pet. Let him find a griffon or something.
</p>

<h2>Zul<a id="zul" class="h_anchor"></a></h2>

<p>
The cleric of pelor seeks his god's radiance in all things, This will probably be the largest hook for plot. Between him and Gaius, the beginning of a Kholirahi insurgency is an easy bet. 
</p>

<h2>Barnable<a id="barnable" class="h_anchor"></a></h2>

<p>
A Joke character is hard to write for
</p>

<br>

<p>
All together we have two, likely three, possibly four members of the party all getting into a distinct conflict, <br>
Talen, Sparkles and Henry are all up in the air, I cannot do much for them
</p>

<br>

<h2>Plot Uncertain<a id="plot-uncertain" class="h_anchor"></a></h2>

<p>
<div style='padding-left: 30pt'>
The party on arriving in Manaharamu is given a day or so to figure out their own personal problems and intentions before Volpe rex makes it into town<br>
***<b>//Begin the next session with a mini-session zero, where we talk about the last session for about fifteen minutes, and consider eachother's thoughts and misgivings</b>***//<br>
<b>THE PARTY HAS MADE IT THROUGH THE GATE AND TO THE INN</b><br>
Vaylen has spent the night at the local Xanarans<br>
Tala has become imprisoned under suspicion of gang activity after contacting a tiefling. The tiefling was asked to assassinate a fox with a decent sized treasure. <br>
Sparkles, zul, and Barnable all made contact with the local fairy clan.<br>
Daniel's Character exists<br>
The party has done a dungeon crawl at the behest of Deloch.<br>
<b>Vaylen has headed toward the University, begin the next session with her.</b>
</div>
</p>

<p>
<b>After a few sessions of Random bullshit Such as a full session preparing for two rounds of combat</b><br>
<div style='padding-left: 30pt'>
Parts of the party have made their way into the university of Manaharamu.<br>
Gaius has left the university<br>
Tala is about to leave the plane and be replaced with Beatrix, Gaius' sister
</div>
<div style='padding-left: 60pt'>
<b>I want Moseie to stop in to say hello to Gaius</b>
</div>
<div style='padding-left: 90pt'>
Moseie is in town to pick up a specific Focus. A Large golden ring of fertility. "Gotta keep my crops growin"<br>
Moseie isn't particularly well disguised, a brown fine linen hood, Kobold-made sunglasses, his signature black-and-silver pants, Anyone looking into his hood would be able to see his face and his sky blue skin is visible on his hands, Even to those who don't know that he is the god-king, his roots identify him as Kholirahi. He wears gold bangles
</div>
</p>

<p>
<div style='padding-left: 30pt'>
<b>Vaylen wishes to have tea with Edgar Frottenhammer then to head to the Artificery</b>
</div>
<div style='padding-left: 60pt'>
The Artificery first. 
</div>
<div style='padding-left: 90pt'>
Entering the Artificery is an awe inspiring thing. The large drop-bar door is reinforced metal and opens outward. Inside there is a Gigantic domed hall with a long, flattened-oval outline. Underneath the glass dome are sheets, quiet, and the bustle of hospital workers and Medicars as they work between cloth-set rooms on seven floors of scaffold-like workspace. The rest of the workshop is a single floor with a layer of Gantries just above  the workspace. Well-Illuminated workspaces under magical light are filled with magical circles, sigils, and enchanting runes. Charts line the walls, Several bookshelves stand with over half of their books absent, spread along the desks instead. Scaffold wraps around larger projects and An Arcanoloth works furiously at a ledger as it tries to keep up with Student Demand. A long line extends from the  desk. Above, an angel, a Deva, bald and purple-skinned, surveys the work of the entire workshop, occasionally flying to a location in the workship to teach. <br>
<b>Yalali, Angel of Oghma, </b>is delighted to meet the Fey Fashonista
</div>
<div style='padding-left: 120pt'>
<i>Oghma smiles on our meeting,Vaylen. It is not often one of your kind walks into a hall so far removed from the stylings of your power. What is it you have come for?</i>
</div>
<div style='padding-left: 90pt'>
Yalali has almost everything required for the robe, but some ingredients are absent. Octarine pigment is hard to find, as the people who don't notice it don't notice it, and those that do can't tell it's octarine. Balhannoth spinal fluid is another hard-to-get ingredient, and it is highly recommended to use fibre from a corpse flower, the harvesting of which would be <b>extremely illegal within Manaharamu</b>.
</div>
</p>

<br>

<h3>Let's talk about plot<a id="lets-talk-about-plot" class="h_anchor"></a></h3>

<p>
<div style='padding-left: 30pt'>
So at this point, with the introduction of Beatrix, Gaius and the Final expenditure of funds, I want to drive the party northward. I want to FUCK them with the real ramifications of the Kholirahi war. so let's examine the current plan
</div>
<div style='padding-left: 60pt'>
I want to have the Kholirahi Contingent lead by one of the God-King's Sons. For that I'll grant a party member something cool probably the Gáe Bulg.<br>
I want them to experience military defeat and to grow to hate and despise the godking all while the godking makes himself look aloof and unconcerned.<br>
I intend to send them up over Mohara where barnable will experience a vision of the Hammer of thunderbolts
</div>
<div style='padding-left: 90pt'>
Mohara should be cold and a puzzle to defeat. This is the walkabout mountain, the spiritual journey of many young manahararahi. It has themes of a barren feywild, puzzles that set back progress for thematic amounts of time.
</div>
<div style='padding-left: 60pt'>
the north slopes of Mohara should be steep and the encounters there should be difficult.<br>
The options they face going northward all involve the aegis mountains, and thus, I must prepare for Mokoi Tha'am, Stalwark, The aegis mountains, Konia,  and probably Jianok Sio
</div>
</p>

<br>
<br>
<br>

<h5>Let's Talk about Buddhism.<a id="lets-talk-about-buddhism" class="h_anchor"></a></h5>

<p>
<div style='padding-left: 30pt'>
They're going to Mana Ulla instead. What. I have to prepare Kavir-e'namak instead. 
</div>
</p>

<br>
<br>
<br>
<br>
<br>
<br>

<p>
INITIATIVE
</p>

	</div>

	<br />

	<div class='page-footer'>
		<b>Backlinks:</b>

		<a href='..\Plot.html'>Nirrum's Encyclopedia of Varomar:ManaharamuMonarchy:Plot</a>

		<br /><br />

	</div>

	

</div>

</body>
</html>
