<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<title>Plot_notes</title>
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
	[ <a href='./Future_hooks.html'>Prev</a> ]

	[ <span class='insen'>Index</span> ]

	[ <a href='./Plot_Notes_Midgard.html'>Next</a> ]
</div>

<hr />

<!-- Wiki content -->

<div class='pages'>
	<div class='heading'>
	<h1>Plot_notes <a name='Nirrum's Encyclopedia of Varomar:ManaharamuMonarchy:Plot:Plot notes'></a></h1>
	</div>

	<div class='content'>
	<p>
Created Sunday 25 February 2018
</p>

<br>

<h2>Xundrin<a id="xundrin" class="h_anchor"></a></h2>

<p>
<div style='padding-left: 30pt'>
Has hidden magic items WIS save vs Spell DC<br>
known as Renthil
</div>
</p>

<br>

<h2>Soleanna<a id="soleanna" class="h_anchor"></a></h2>

<p>
<div style='padding-left: 30pt'>
signed in as Krishta sparrow
</div>
</p>

<br>

<h2>Ridicully<a id="ridicully" class="h_anchor"></a></h2>

<p>
<div style='padding-left: 30pt'>
Amulet of fuck off scrying<br>
known as saiid or Pyuwalo Badulo
</div>
</p>

<br>
<br>

<p>
Going after grom ambershore<br>
<ul style='padding-left: 30pt'>
<li>party is at Xanaran's  with Clerics and Paladins of Tempus</li>
<li>They have made themselves conspicuous but grom</li>
</ul>
mentioned memory's sister at the table<br>
40 paladins and clerics of tempus are told to find changelings and doppelgangers<br>
coatl arrive at noon the next day<br>
find itir
</p>

<br>

<p>
Met Kosti Kemadumana'ab<br>
Met and offended Persephone <br>
Cosades presence announced **<b>Loudly</b>**<br>
Found rime, allowed to stay<br>
MET TETRAGRAMMATON<br>
Coatl emerged<br>
allowed to stay on the mountain<br>
Quanahriin left<br>
frog with cosades
</p>

<h4>grom's fucked yo<a id="groms-fucked-yo" class="h_anchor"></a></h4>

<p>
They have confronted alawabreolsh <br>
Itir wants to talk,
</p>

<p>
Initiative<br>
<div style='padding-left: 30pt'>
Itir critical <br>
Soleanna 16<br>
Tetragrammaton<br>
cosades 13<br>
Gale 12<br>
Skoofy<br>
Alawabreolsh
</div>
</p>

<p>
Wau!xorauch is hunted<br>
The sorcery head has been mentioned to be being imitated by a Changeling.<br>
After the first day, the cult gets their shit together, any deaths, banishments, expulsions of any kind that remove their power from the university.
</p>

<br>

<h3>Ridcully is the war mage<a id="ridcully-is-the-war-mage" class="h_anchor"></a></h3>

<p>
Kotsi, Nirrum and Karagan, Chillin in the Konia Crater<br>
Sillig, Tulkas, Keenan,  have left to alert the queen and rally the Trussari and army
</p>

<p>
pimish off to spy on the kholirahi
</p>

<br>

<p>
The Cult's movements now support the Kholirahi, They count on Nirrum to defend his library with every inch of his cunning (and he fucking will)
</p>

<p>
Pimish has set up planar Relays for the Kholirahi air fleet to arrive in manaharamu<br>
Metwiki has been sent to Kara'ite to help marshall their defenses.<br>
Ukog &amp; imok have been sent to thunder island on the thunder coast
</p>

<h5>Pimish Attacks and isolates ridicully<a id="pimish-attacks-and-isolates-ridicully" class="h_anchor"></a></h5>

<p>
This takes 30 days to set up, 27 remaining<br>
The setup is this <br>
Demiplane-&gt;Forbiddance-&gt; sleep darts-&gt; dimensional shackles
</p>

<p>
<b>Frog is confronted by the queen of Manaharamu asking why she is here and why she has brought so many coatl. At a certain point in the conversation, Tarn Ravora begins interrogating the coatl. The coatl cannot lie but will avoid the truth of their visit for as long as possible</b>
</p>

<p>
When Checking the astral plane, Soleanna is visited by the vengeful ghost of Moin Matur, the previous Archmage who was poisoned  by mundane poisons (which he finds rather offensive. She is told to check the library for books on Nerull, for the "tomb of dead gods" as a good spot to go.
</p>

<p>
The cult acts agains the queen once she knows about their existence, or they begin to, until she joins their side
</p>

<p>
The Queen is still intrinsically opposed to the Kholirahi, as they are sexist slavers and religously exclusive in their devotion to their godking, and will fight against them to her last breath.
</p>

<p>
The second anything threatens the library, Nirrum pulls the plug and disappears with the library and the majority of the college of lore. 
</p>

<p>
<b>Garhun Ten-Cages Acts if the cult does anything fishy.</b> Garhun (the first one the real one) <i>HATES the cult as it interferes frequently with his work.</i> He acts in the best interests of anyone who intends to fight the cult, despite still being an ass. He has True Resurrection prepped in case ridicully dies outright.
</p>

<p>
<b>Xundrin is targetted with Banish-wielding students from the school of Abjuration.</b>
</p>

<p>
Itir and Gale are asked to leave by a wounded and tired Alawabreolsh Ravora, it is not safe for them here, to take Rime with them.
</p>

<br>

<p>
With Rime, Itir, Gale, and Ridicully out of the way, The last real end to tie up is Soleanna. If she remembers Moin's advice, she will head to the library to learn about the tomb of dead gods. Hopefully, this will convince her to leave, her time on this plane has not been a waste.
</p>

<p>
This Leaves Tetragrammaton. Let him stay should he want to.
</p>

<br>

<p>
The Kholirahi army arrives in Manaharamu in two more days via teleport. They are met with resistance, of course, but their airships have force fields around them to limit the initial onslaught. The library disappears, who knows to where. The Students scatter as they are slain by Rudmages, trained and viscious.
</p>

<p>
The Queen joins up with the cult and puts her family into hiding. Tarn Ravora leaves for the underdark. The Trussari fight, and likely die. 
</p>

<p>
The Kholirahi use their ultimate weapon, starting with storm of vengeance in a couple of locations, Higher airships begin to unveil their great magical lens. They Strike on the Full moon, while the moon, Allabar, opener of the way, is directly above Manaharamu.
</p>

<p>
Looking at Allabar, opener of the way forces a creature to make a DC25 wisdom save to not be stunned until their line of sight to allabar is blocked, even for a split second.  Anyone stunned by Allabar must then, on their turn, make a DC 20 con save, or have take 20 damage, save ends
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
