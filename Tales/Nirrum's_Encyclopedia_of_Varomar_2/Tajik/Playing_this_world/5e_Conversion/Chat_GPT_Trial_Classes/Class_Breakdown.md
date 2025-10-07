<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<title>Class Breakdown</title>
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
	[ <a href='..\Chat_GPT_Trial_Classes.html'>Prev</a> ]

	[ <span class='insen'>Index</span> ]

	[ <a href='./csv.html'>Next</a> ]
</div>

<hr />

<!-- Wiki content -->

<div class='pages'>
	<div class='heading'>
	<h1>Class Breakdown <a name='Nirrum's Encyclopedia of Varomar 2:Tajik:Playing this world:5e Conversion:Chat GPT Trial Classes:Class Breakdown'></a></h1>
	</div>

	<div class='content'>
	<p>
Created Tuesday 13 May 2025
</p>

<p>
⚔️ Point-Buy Progression Tables for Each Class<br>
<ol type="1" start="1">
<li>Barbarian</li>
</ol>
Level	Total FP	Features<br>
1	18	Hit Die (d12), Armor Proficiency, Weapon Proficiency, Saving Throws (Str, Con), Rage (2/day), Unarmored Defense<br>
2	3	Reckless Attack, Danger Sense<br>
3	4	Primal Path, Path feature<br>
4	4	Ability Score Improvement<br>
5	5	Extra Attack, Fast Movement<br>
6	4	Path feature<br>
7	5	Feral Instinct<br>
8	4	Ability Score Improvement<br>
9	5	Brutal Critical (1 die)<br>
10	4	Path feature<br>
11	5	Relentless Rage<br>
12	4	Ability Score Improvement<br>
13	5	Brutal Critical (2 dice)<br>
14	4	Path feature<br>
15	5	Persistent Rage<br>
16	4	Ability Score Improvement<br>
17	5	Brutal Critical (3 dice)<br>
18	4	Path feature<br>
19	5	Ability Score Improvement<br>
20	4	Primal Champion<br>
<ol type="1" start="2">
<li>Bard</li>
</ol>
Level	Total FP	Features<br>
1	18	Hit Die (d8), Armor Proficiency, Weapon Proficiency, Saving Throws (Dex, Cha), Spellcasting, Bardic Inspiration (d6, 1/rest)<br>
2	3	Jack of All Trades, Song of Rest (d6)<br>
3	4	Bard College, College feature<br>
4	4	Ability Score Improvement<br>
5	5	Bardic Inspiration (d8, 2/rest), Countercharm<br>
6	4	College feature<br>
7	5	Counterspell, Magical Secrets (1 spell)<br>
8	4	Ability Score Improvement<br>
9	5	Song of Rest (d8)<br>
10	4	College feature<br>
11	5	Bardic Inspiration (d10, 3/rest), Magical Secrets (2 spells)<br>
12	4	Ability Score Improvement<br>
13	5	Song of Rest (d10)<br>
14	4	College feature<br>
15	5	Bardic Inspiration (d12, 4/rest), Magical Secrets (3 spells)<br>
16	4	Ability Score Improvement<br>
17	5	Song of Rest (d12)<br>
18	4	Magical Secrets (4 spells)<br>
19	5	Ability Score Improvement<br>
20	4	Superior Inspiration<br>
<ol type="1" start="3">
<li>Cleric</li>
</ol>
Level	Total FP	Features<br>
1	18	Hit Die (d8), Armor Proficiency, Weapon Proficiency, Saving Throws (Wis, Cha), Spellcasting, Divine Domain, Domain feature<br>
2	3	Channel Divinity (1/rest), Turn Undead<br>
3	4	Channel Divinity (1/rest), Domain feature<br>
4	4	Ability Score Improvement<br>
5	5	Destroy Undead (CR 1/2), Channel Divinity (1/rest)<br>
6	4	Channel Divinity (1/rest), Domain feature<br>
7	5	Destroy Undead (CR 1), Channel Divinity (1/rest)<br>
8	4	Ability Score Improvement<br>
9	5	Destroy Undead (CR 1), Channel Divinity (1/rest)<br>
10	4	Channel Divinity (1/rest), Domain feature<br>
11	5	Destroy Undead (CR 2), Channel Divinity (1/rest)<br>
12	4	Ability Score Improvement<br>
13	5	Destroy Undead (CR 2), Channel Divinity (1/rest)<br>
14	4	Channel Divinity (1/rest), Domain feature<br>
15	5	Destroy Undead (CR 3), Channel Divinity (1/rest)<br>
16	4	Ability Score Improvement<br>
17	5	Destroy Undead (CR 3), Channel Divinity (1/rest)<br>
18	4	Channel Divinity (1/rest), Domain feature<br>
19	5	Destroy Undead (CR 4), Channel Divinity (1/rest)<br>
20	4	Divine Intervention
</p>

<p>
<ol type="1" start="4">
<li>Druid</li>
</ol>
Level	Total FP	Features<br>
1	18	Hit Die (d8), Armor Proficiency, Weapon Proficiency, Saving Throws (Int, Wis), Spellcasting, Druid Circle, Circle feature<br>
2	3	Wild Shape (2 uses), Wild Shape feature<br>
3	4	Druid Circle feature<br>
4	4	Ability Score Improvement<br>
5	5	Wild Shape (CR 1/4), Wild Shape feature<br>
6	4	Druid Circle feature<br>
7	5	Wild Shape (CR 1/2), Wild Shape feature<br>
8	4	Ability Score Improvement<br>
9	5	Wild Shape (CR 1), Wild Shape feature<br>
10	4	Druid Circle feature<br>
11	5	Wild Shape (CR 1), Wild Shape improvement<br>
12	4	Ability Score Improvement<br>
13	5	Additional spell slots and higher-level spells<br>
14	4	Druid Circle feature<br>
15	5	Timeless Body<br>
16	4	Ability Score Improvement<br>
17	5	Beast Spells<br>
18	4	Archdruid (unlimited Wild Shape, Circle feature)<br>
19	5	Ability Score Improvement<br>
20	4	Archdruid (capstone)<br>
<ol type="1" start="5">
<li>Fighter</li>
</ol>
Level	Total FP	Features<br>
1	18	Hit Die (d10), Proficiencies, Second Wind<br>
2	3	Action Surge<br>
3	4	Martial Archetype, Archetype feature<br>
4	4	Ability Score Improvement<br>
5	5	Extra Attack<br>
6	4	Ability Score Improvement<br>
7	5	Archetype feature<br>
8	4	Ability Score Improvement<br>
9	5	Indomitable (1 use)<br>
10	4	Ability Score Improvement<br>
11	5	Extra Attack (2)<br>
12	4	Ability Score Improvement<br>
13	5	Indomitable (2 uses)<br>
14	4	Ability Score Improvement<br>
15	5	Archetype feature<br>
16	4	Ability Score Improvement<br>
17	5	Action Surge (2 uses), Indomitable (3 uses)<br>
18	4	Ability Score Improvement<br>
19	5	Ability Score Improvement<br>
20	4	Extra Attack (3)<br>
<ol type="1" start="6">
<li>Monk</li>
</ol>
Level	Total FP	Features<br>
1	18	Martial Arts, Unarmored Defense, Proficiencies<br>
2	3	Ki (2 pts), Flurry of Blows, Step of the Wind, Patient Defense<br>
3	4	Monastic Tradition, Deflect Missiles, Martial Arts improvement<br>
4	4	Ability Score Improvement<br>
5	5	Extra Attack, Stunning Strike<br>
6	4	Ki improvement, Monastic Tradition feature<br>
7	5	Evasion, Stillness of Mind<br>
8	4	Ability Score Improvement<br>
9	5	Unarmored Movement +15 ft<br>
10	4	Purity of Body<br>
11	5	Monastic Tradition feature, Ki (11 pts)<br>
12	4	Ability Score Improvement<br>
13	5	Tongue of the Sun and Moon<br>
14	4	Diamond Soul (proficiency in all saves)<br>
15	5	Timeless Body, Ki (15 pts)<br>
16	4	Ability Score Improvement<br>
17	5	Monastic Tradition feature, Ki (17 pts)<br>
18	4	Empty Body<br>
19	5	Ability Score Improvement<br>
20	4	Perfect Self<br>
<ol type="1" start="7">
<li>Paladin</li>
</ol>
Level	Total FP	Features<br>
1	18	Divine Sense, Lay on Hands, Proficiencies<br>
2	3	Spellcasting, Divine Smite<br>
3	4	Sacred Oath, Oath Feature<br>
4	4	Ability Score Improvement<br>
5	5	Extra Attack, Aura of Protection (10 ft)<br>
6	4	Aura of Protection extension<br>
7	5	Oath feature<br>
8	4	Ability Score Improvement<br>
9	5	Improved Divine Smite<br>
10	4	Aura of Courage<br>
11	5	Cleansing Touch<br>
12	4	Ability Score Improvement<br>
13	5	Oath feature<br>
14	4	Divine Health upgrade<br>
15	5	Aura improvements<br>
16	4	Ability Score Improvement<br>
17	5	Oath feature<br>
18	4	Aura range becomes 30 ft<br>
19	5	Ability Score Improvement<br>
20	4	Sacred Oath capstone
</p>

<p>
Would you like the remaining classes (Ranger to Wizard)? I can provide those next in the same format.<br>
You said:<br>
yes<br>
ChatGPT said:
</p>

<p>
Here’s the Point-Buy Progression Table for the remaining core 5e classes: Ranger, Rogue, Sorcerer, Warlock, and Wizard. This continues the same structure, estimating the FP (Feature Point) value of each level's abilities based on our earlier system.<br>
<ol type="1" start="8">
<li>Ranger</li>
</ol>
Level	Total FP	Features<br>
1	18	Hit Die (d10), Proficiencies, Favored Enemy, Natural Explorer<br>
2	3	Fighting Style, Spellcasting (half-caster)<br>
3	4	Ranger Archetype, Archetype feature<br>
4	4	Ability Score Improvement<br>
5	5	Extra Attack<br>
6	4	Favored Enemy improvement, Natural Explorer improvement<br>
7	5	Ranger Archetype feature<br>
8	4	Ability Score Improvement, Land’s Stride<br>
9	5	Natural Explorer improvement<br>
10	4	Hide in Plain Sight<br>
11	5	Ranger Archetype feature<br>
12	4	Ability Score Improvement<br>
13	5	Favored Enemy improvement<br>
14	4	Vanish<br>
15	5	Ranger Archetype feature<br>
16	4	Ability Score Improvement<br>
17	5	Greater Favored Enemy<br>
18	4	Feral Senses<br>
19	5	Ability Score Improvement<br>
20	4	Foe Slayer<br>
<ol type="1" start="9">
<li>Rogue</li>
</ol>
Level	Total FP	Features<br>
1	18	Hit Die (d8), Sneak Attack (1d6), Expertise (2), Thieves’ Cant<br>
2	3	Cunning Action<br>
3	4	Roguish Archetype, Sneak Attack +1d6, Archetype feature<br>
4	4	Ability Score Improvement<br>
5	5	Uncanny Dodge, Sneak Attack +1d6<br>
6	4	Expertise (2), Sneak Attack +1d6<br>
7	5	Evasion, Sneak Attack +1d6<br>
8	4	Ability Score Improvement<br>
9	5	Archetype feature, Sneak Attack +1d6<br>
10	4	Ability Score Improvement, Sneak Attack +1d6<br>
11	5	Reliable Talent, Sneak Attack +1d6<br>
12	4	Ability Score Improvement<br>
13	5	Sneak Attack +1d6, Archetype feature<br>
14	4	Blindsense<br>
15	5	Slippery Mind, Sneak Attack +1d6<br>
16	4	Ability Score Improvement<br>
17	5	Sneak Attack +1d6, Archetype feature<br>
18	4	Elusive<br>
19	5	Ability Score Improvement<br>
20	4	Stroke of Luck, Sneak Attack +1d6<br>
<ol type="1" start="10">
<li>Sorcerer</li>
</ol>
Level	Total FP	Features<br>
1	18	Spellcasting (full), Sorcerous Origin<br>
2	3	Font of Magic (sorcery points)<br>
3	4	Metamagic (2 options)<br>
4	4	Ability Score Improvement<br>
5	5	Spellcasting improvement<br>
6	4	Sorcerous Origin feature<br>
7	5	Metamagic improvement, spell slot gains<br>
8	4	Ability Score Improvement<br>
9	5	Font of Magic improvement<br>
10	4	Metamagic (3rd option)<br>
11	5	Spellcasting improvement<br>
12	4	Ability Score Improvement<br>
13	5	Spellcasting improvement<br>
14	4	Sorcerous Origin feature<br>
15	5	Font of Magic improvement<br>
16	4	Ability Score Improvement<br>
17	5	Metamagic Mastery, 9th-level spells<br>
18	4	Sorcerous Origin feature<br>
19	5	Ability Score Improvement<br>
20	4	Sorcerous Restoration (capstone)<br>
<ol type="1" start="11">
<li>Warlock</li>
</ol>
Level	Total FP	Features<br>
1	18	Pact Magic, Otherworldly Patron<br>
2	3	Eldritch Invocations (2)<br>
3	4	Pact Boon, Patron feature<br>
4	4	Ability Score Improvement<br>
5	5	Eldritch Invocations (+1), Pact Magic scaling<br>
6	4	Patron feature<br>
7	5	Invocations (+1), Pact Magic scaling<br>
8	4	Ability Score Improvement<br>
9	5	Patron feature<br>
10	4	Eldritch Mastery, Invocations (+1)<br>
11	5	Mystic Arcanum (6th level)<br>
12	4	Ability Score Improvement<br>
13	5	Mystic Arcanum (7th level)<br>
14	4	Patron feature<br>
15	5	Mystic Arcanum (8th level)<br>
16	4	Ability Score Improvement<br>
17	5	Mystic Arcanum (9th level)<br>
18	4	Invocations (+1)<br>
19	5	Ability Score Improvement<br>
20	4	Eldritch Master<br>
<ol type="1" start="12">
<li>Wizard</li>
</ol>
Level	Total FP	Features<br>
1	18	Spellcasting (full), Arcane Recovery, Arcane Tradition<br>
2	3	Arcane Tradition feature<br>
3	4	Spellcasting improvement<br>
4	4	Ability Score Improvement<br>
5	5	Spellcasting improvement<br>
6	4	Arcane Tradition feature<br>
7	5	Spellcasting improvement<br>
8	4	Ability Score Improvement<br>
9	5	Spellcasting improvement<br>
10	4	Arcane Tradition feature<br>
11	5	Spellcasting improvement<br>
12	4	Ability Score Improvement<br>
13	5	Spellcasting improvement<br>
14	4	Arcane Tradition feature<br>
15	5	Spellcasting improvement<br>
16	4	Ability Score Improvement<br>
17	5	Spellcasting (9th level)<br>
18	4	Spell Mastery<br>
19	5	Ability Score Improvement<br>
20	4	Signature Spells<br>
✅ What You Can Do with This System
</p>

<p>
<div style='padding-left: 30pt'>
Reconstruct any class using the FP costs.
</div>
</p>

<p>
<div style='padding-left: 30pt'>
Customize multiclass or hybrid classes based on point budgets.
</div>
</p>

<p>
<div style='padding-left: 30pt'>
Homebrew balanced new classes or subclasses using the same economy.
</div>
</p>

	</div>

	<br />

	<div class='page-footer'>
		<b>Backlinks:</b>

		<a href='..\Chat_GPT_Trial_Classes.html'>Nirrum's Encyclopedia of Varomar 2:Tajik:Playing this world:5e Conversion:Chat GPT Trial Classes</a>

		<br /><br />

	</div>

	

</div>

</body>
</html>
