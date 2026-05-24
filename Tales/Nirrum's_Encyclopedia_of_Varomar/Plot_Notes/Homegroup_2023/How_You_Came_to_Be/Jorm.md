<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<title>Jorm</title>
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
	[ <a href='./Clara/Spoiler-ideas.html'>Prev</a> ]

	[ <span class='insen'>Index</span> ]

	[ <a href='./Jorm/Spoiler_Ideas.html'>Next</a> ]
</div>

<hr />

<!-- Wiki content -->

<div class='pages'>
	<div class='heading'>
	<h1>Jorm <a name='Nirrum's Encyclopedia of Varomar:Plot Notes:Homegroup 2023:How You Came to Be:Jorm'></a></h1>
	</div>

	<div class='content'>
	<p>
Created Monday 23 September 2024
</p>

<br>
<br>

<p>
<a href="./Jorm/Spoiler_Ideas.html" title="+Spoiler_Ideas" class="page">+Spoiler_Ideas</a> 
</p>

<p>
BEGINNING<br>
Skalmirthon
</p>

<p>
You awake in amongst the pile of beds that serves you and your younger kin. Six dwarves, one goliath that needs three beds, and you, who uses two. Most often, your parent's cat, Tozör (slug) sleeps under your neck but this morning, they sit on your chest. As they are rather large, bordering on the size of a small dwarf, you find it hard to breathe, and it is likely this that caused you to awake. It will take effort to pry the creature from its perch, 
</p>

<p>
Today is an important day, the first day of university at the brand new (impromptu) Skalmirthon U. Currently being constructed out of the old Gambling dens. You want to get in early, as the dwarf slots are free, but fill up quickly. Tell me how your morning goes before you head out
</p>

<br>
<br>
<br>

<p>
PARENT CREATURE <br>
<div style='padding-left: 30pt'>
Armogo Tellarshorn, who insists you call her Moggy, is your mother. She picked you off the street  when you were a wee child as if you were hers to begin with. You were neither the first nor the last, nor did you ever feel like she didn't have time for you. You rarely had time to feel that. She talks and works fast, and there might be three people on the plane who have ever used a draw knife or a spokeshave with the proficiency she has, and one is Otokadon, god of craft. The other is a legendary dwarf from an age past who she sometimes asks for help in the form of a grotesque, carved into a beam in the workshop they use. 
</div>
<div style='padding-left: 60pt'>
Philo! Good. Breakfast is scrambled eggs, you're a bit late so yours might be a little brown, and I had to move your hot sauce from the table again last night because Tozor was about to knock it over it's on the high shelf. AMOT those better not be those socks I told you to throw out last week I see you wearing.
</div>
</p>

<br>

<p>
PARENT CREATURE<br>
<div style='padding-left: 30pt'>
Dalthin Marehatchet, Daggy, who has a perpetually harrowed, angry stare, and has gotten into much trouble because of it. He just looks that way, and has never wanted to change it. He was instrumental (haha) in helping you come to terms with who you are, and not who other people want you to be. Despite his appearance he is a great prankster, has an amazing sense of humour, and cares deeply for skilled work. He has an immense fear of slugs, hence your mother naming your cat, Slug. He is far more detail oriented than your mother, and by their powers combined, they are quite the sought after duo.
</div>
<ul style='padding-left: 60pt'>
<li>He once re-arranged every bed in your sibling-room and then short-sheeted each one. </li>
<li>Frequently re-labels ingredients in the kitchen</li>
<li>Hands people bits of trash and rubbish without explanation by simply holding his clenched hand toward them, then walking away</li>
<li>Draws on the faces of sleeping people </li>
</ul>
</p>

<p>
AUNTING<br>
<div style='padding-left: 30pt'>
Derriah Madge is a human who has occupied the attic of your house for as long as anyone can remember. She seems middle aged, a grey frizz cascading down her long chestnut bangs. She's a mage of some sort, from Konia she says. Where your parents are great powers of responsibility, Derriah has been a perpetual source of bad ideas, covering your ass when you're in trouble, and coming to see you when you can't get out of trouble. Her attic has always been a place where you can get away from your family. 
</div>
</p>

<p>
SIBLING<br>
<div style='padding-left: 30pt'>
Amot. There are few more dwarfly dwarfs than Amot. A scrollcarver for both stone and wood when he's not doing military training. He has your father's face but little of his humour, half his talent, and not nearly as fine of a beard as either of your parents should provide. He is annoying and awful and snores and broke your violin that one time when he was seven, but you've bonded over some trouble you managed to avoid
</div>
</p>

<p>
SIBLING<br>
<div style='padding-left: 30pt'>
Scabla Shearbutter. Scabla has been involved cooking the family meals since she was three, and has only lost one finger in the process, and not even one of her own! Your parents both agreed that it was more trouble than it was worth to keep her out of the kitchen so she was apprenticed in the mason's dining hall when she was seven. Not that that's legal but again, more trouble than it was worth to stop her.<br>
She shares a quiet kinship with you over a connection you helped her make for a rare ingredient. You get more than a dwarf sized bowl, Though not as much as Galost
</div>
</p>

<p>
SIBLING<br>
<div style='padding-left: 30pt'>
Dargi Shanbottle is the third oldest sibling. By far he is the most talkative, and couldn't stop talking if he had been been dead for ten years. This is a shame because he runs out of anything substantive to say around lunchtime each day. He looks remarkably like your mother, who occasionally calls your grandfather's epithet "Goggy!", if she turns the corner too fast and gets frightened by him. Before she passed, your grandmother would look on him very fondly (and give him more treats than you)
</div>
</p>

<p>
SIBLING<br>
<div style='padding-left: 30pt'>
Bukko Badcattlethorn the oldest dwarf sibling, only slightly younger than you, you were both in diapers at the same time, but you found your words far earlier. Bukko is an eternal confidant, and takes after your father in personality, save for the schock of red that your mother's extended family sometimes has. Bukko helps your parents make instruments, mostly by stringing, polishing, tuning, and rough shaping wood. 
</div>
</p>

<p>
SIBLING
</p>

<p>
SIBLING
</p>

<p>
SIBLEST<br>
<div style='padding-left: 30pt'>
Galost
</div>
CAT<br>
<div style='padding-left: 30pt'>
Tozör is a Skal Verminkat. He is the size of a small child and
</div>
</p>

<p>
The University line is shorter than you imagined. In front of you are a few Manarahi expats, a stunning number of Drow, a few dwarves, and some stone booths containing signups for the classes.<br>
Basic Magic, Druid Studies, all the basics shuffled into one. The line moves... slowly. Very slowly. Time seems to slow and stop. Something.... is odd.<br>
<div style='padding-left: 30pt'>
The perspective of the connecting streets seems to stretch on too long.<br>
Other People's faces seem to be hard to remember, Hard to think about.<br>
There is a rhythmic thumping, which doesn't seem to be your heartbeat, but perhaps the heartbeats of everyone around you... in time.<br>
You can smell the inside of your own nose, which is odd because you hadn't noticed it before.<br>
You are dehydrated<br>
Most importantly you are surrounded by a lot of unfamiliar faces, competing for a spot in what will be one of the great learning institutions of the world. You are surrounded by your competitors. You are surrounded by things that want to take your place from you.<br>
There is a rock in your shoe that stabs you when you step<br>
There is a hair in your eye, it doesn't appear to be yours<br>
Somebody's button just flashed sunlight from the oculus into your eye<br>
Everyone... has turned... to look at you. All of them stopped, one of them smiling.
</div>
<div style='padding-left: 60pt'>
"A fresh face, Goot, You wish to enroll? 1 gold, 3 Silver," A dwarf says. No, not a dwarf, a little shorter than that but taller than a gnome. It is quite hairy, furry even, Quite furry, like some cats, or even the foreign horses that you see sometimes. The more you look the more you realise this creature is definitely neither a dwarf gnor a gnome as it also has a long lion's tail... and antlers, how did you... not... notice those antlers. They jump down from their stone table at the... entirely empty plaza. "Instrument maker. Tell me a story as we walk." 
</div>
</p>

<p>
<b>Anoo, Archfey of Hidden Beasts, Archbard of Terror</b><br>
<div style='padding-left: 30pt'>
The Small creature walks you around the square, pausing briefly to speak with several mice, who you notice have started a small pitroast over a candle, upon which they have several cockroaches and most of a strawberry, nearby another mouse tends to a thimble that is filled with water and what appear to be dandelion seeds over a fire of their own. 
</div>
</p>

<br>
<br>

<p>
<div style='padding-left: 30pt'>
<b>Where'd everyone go?</b>
</div>
<div style='padding-left: 60pt'>
They von't be hea until tomorho. Hyor a day Early, Most of my students are.
</div>
<div style='padding-left: 30pt'>
<b>Who are you</b>
</div>
<div style='padding-left: 60pt'>
Anoo, though be careful vit zat name, Unlike Mooooost names, it has.... teeth
</div>
<div style='padding-left: 90pt'>
Anoo's grin is unreasonably sharp, and indeed, as you think on the name, you feel something slither along with the thought, watching, waiting. She clacks her teeth together
</div>
<div style='padding-left: 60pt'>
<b>CLACK CLACK</b> Best not to use it. Call me, The Cat-She, It's not accurate but it will do, and the wrong crowd will certainly know the right person when you use that. Less blood, more magic. Good deal. 
</div>
<div style='padding-left: 30pt'>
<b>What are you</b>
</div>
<div style='padding-left: 60pt'>
I am eh, ve have a word for it that hyu do not, Fey? Fey. Archfey. Archbard. I teach people ze aht of <i>setting, <b>vit a focus on uncomfortable settings.</b></i>
</div>
<div style='padding-left: 30pt'>
<b>A strange choice</b>
</div>
<div style='padding-left: 60pt'>
No choice. Born zis vay. Not Zat I'd trade it in.
</div>
<div style='padding-left: 30pt'>
<b>Uncomfortable bad</b>
</div>
<div style='padding-left: 60pt'>
Zere are many Moral lessons one can draw from any creature's disposition. Maybe I am ze enemy of complacency in philosophical position. Maybe I am ze AVATAH OF AVARENESS. In trus, I draw my strength and magic from hidden threats. Almost half my magic comes from ze threats themselves, but all of ze rest? Hiding zose threat vile making zem still... known. <br>
Maybe I'm just a bad person Hm? Not many tutors meet zeir students a day early. Do hyo know any illusions? Great, hyoa ozzer classmates are inside of zat bench, go join zem, and remember ze script, hyor next classmate is on zeir vay.
</div>
</p>

<br>
<br>
<br>
<br>

<p>
MIDDLE<br>
<div style='padding-left: 30pt'>
Kholira is a cold and bitter land, and it is the coldest, bitterest time of year. You were sent by anoo to the city nestled in the valley of the ualakomara range four years ago. In that time, Manaharamu has fallen which was a Shock, Konia was utterly destroyed, which was surprising in that it was considered news, Skalmirthon has one or two new city states, you don't care too much about those, save for the abundance of tea and honey you will be able to purchase when you return home. Your younger brother, Amot, died in the Kholirahi seige of the ushlubarel the year after you left, and here you sit, On A kholirahi stage in a kholirahi Kwastulat, where unblinking, emotionless faces turn to you as you play a violin for your brother's killers. Not for much longer though. You've been told to go on an errand in a much more hospitable climate for you... the feywild. 
</div>
<div style='padding-left: 60pt'>
Roll a performance check. Read results from top to bottom, as if the song takes a while to get good. 
</div>
<div style='padding-left: 90pt'>
Poor. The room falls flat, most people look away as you play, and begin to talk
</div>
<div style='padding-left: 120pt'>
 Perception (wis) 20 gives you their conversations. The orcs are beginning to build boats along the ushlubarel, the Starseers still complain about tasteless food, and some still start fights with Aton's troops. 
</div>
<div style='padding-left: 90pt'>
Good enough. The room keeps its eyes locked on you, One person looks around to see the other's reactions. They clearly want to listen but....
</div>
<div style='padding-left: 120pt'>
History (intelligence) 16 reminds you of a certain Danzuishanese elf who was excellent at hiding their own appearance. Another Spy. So that's where they've been. Somehow, you are more conspicuous. Now that you've noticed, you can spot the illusion on their head, a very dangerous game here.  
</div>
<div style='padding-left: 90pt'>
Well done. One person turns his mouth into an approving frown and nods, thinking about something. This is high praise from the Kholirahi
</div>
<div style='padding-left: 120pt'>
Insight(wis) 14 will tell you that this is Mhoni, whose wife died last year in the seige. He is bitter about her loss, but has never begrudged the opponents of Kholira. This song has reminded him that she didn't hate them either. He wishes those opponents didn't hate <i>him. </i>He reminds you of your father. They'd probably get along. The people of Kholira believe in their mission more than their own misgivings, but they are shrewd. Mhoni works at the docks, and one of the slaves he helped shepherd into the encampment was singing a similar song to one of their cocaptives. That's why you chose it.
</div>
<div style='padding-left: 90pt'>
Banger. Several people begin nodding, stand up to get drinks in unison, and keep their eyes on stage. When they get their drinks they lay them on tables near the side. People begin to clear the room in order to dance.
</div>
<div style='padding-left: 120pt'>
Investigation(wis) 12, these are young sailors. They've not had a good reason to dance in a while. The Kholirahi weakness is dance. The roots could never take away their need to jump and move together. A glint of polish among their scratched legacy. Taparmishi is a slur in their language, but no people have ever prevented adventurous souls from doing daring things.
</div>
<div style='padding-left: 90pt'>
Exceptional. You see several people slow their breathing, a tear fall from one eye, and the very corner of a smile. The dancing is fervent. The highest praise
</div>
<div style='padding-left: 120pt'>
Performance (cha) 10, Thalomendar's reel was old before whistling was invented. It is the lullaby of many children, the courting of many lover, and the requiem of many dead. Ogoghi's father is in the war, and her mother comatose with some shadowfell disease. Hellslayer the godblooded, son of the godking, has never once felt happy or relaxed, it is hard to tell if he deserves that smile, It'd better for everyone, himself especially if he died soon. You've stirred their blood, their prayers and offerings to their godking will be different tomorrow, and this will afford greater mercy to those recently enslaved. 
</div>
<div style='padding-left: 90pt'>
On a critical success, they sing along with the song as well as proper dancing. A normal night in many places is a shining gem in this cold country. Many of them cry<br>
You gain advantage on all other checks. 
</div>
<div style='padding-left: 120pt'>
Once, you told your moggy where you were going, where you had been, after your brother's death. She gave you a deep hug, her head barely to your head, and said, "Aye, those poor folk can't be that bright given what they did. Probably don't have enough music. Quiet folk like your daggy. You're talented, make them feel something"
</div>
</p>

<br>

<p>
EACH OF THESE RESULTS WILL BE WOVEN BACK INTO THE CAMPAIGN LATER. THE POWER OF THIS SONG OFFERS LATER ADVANTAGES
</p>

<p>
When the night passes, you head to your apartments. One of many doors in the Capital's smooth streets. Tonight, the sky is flat, with no sign of moon or stars. The temperature is dropping, and a few thick gusts herald a major storm. Tonight, there are demons that would crawl back into hell to avoid the Godking's Wrath, slang for a storm such as this. You intend to be elsewhere, of course. You trudge through a waist-high trench to an unreasonably far apartment, nearly equidistant between two dining halls. You <i>unfeel</i> the cold as you temporarily pass under a white-leafed tree, all thoughts momentarily stilled. Dettor Bloodstolen. One of the sons of the godking. He has gripped his roots into a roof as is often his way. Tonight, he intends to feel the blizzard. Two Sons in one night, not a common evening. Do you say anything?
</p>

<p>
Finally, you reach your apartments. As you close the door, you realise you are not alone. A man with a half shaved beard is currently Crawling out of your oven, Coals are scattered all over the floor, their dim glow fading. He is Kholirahi, that much is certain. Rather Bizzarely Inside your oven is where your portal to the feywild is, hidden in an impossible turn behind the chimney pipe.
</p>

<br>

<p>
<b>Roberto Dreamwarden</b><br>
<div style='padding-left: 30pt'>
Roberto is taking your coat, one way or another, he does not care that you will be left with one less layer.
</div>
</p>

<p>
<div style='padding-left: 30pt'>
<b>Hello</b>
</div>
<div style='padding-left: 60pt'>
AH. GOOD. A person. I was worried this place was empty. I will be taking your coat, your boots if they fit me, and your hat. 
</div>
<div style='padding-left: 30pt'>
<b>Who are you</b>
</div>
<div style='padding-left: 60pt'>
A son, <i>Jaraha.</i>
</div>
<div style='padding-left: 90pt'>
His eyes are indeed orange.<br>
History 16, Roberto Dreamwarden, frequents the feywild and is a powerful druid of dreams. 
</div>
<div style='padding-left: 30pt'>
<b>What are you doing in my oven?</b>
</div>
<div style='padding-left: 60pt'>
Just arriving home from the feywild. This is a mercifully close portal, I'm surprised I didn't know about it.
</div>
<div style='padding-left: 30pt'>
<b>A portal?</b>
</div>
<div style='padding-left: 60pt'>
Yes, Deep inside behind the pipe. You'll probably get stuck.
</div>
</p>

<p>
Roberto leaves carelessly. Your fire hopelessly guttered. Your flint, smashed. The skeleton in your closet, undiscovered. The colony of rats you've been feeding in your pantry, Hungry for a chance at what's left of the marrow. Three sons in one night and one of them has even been rather helpful, even if he was an ass. It'll be easier to frame your own death and explain *why* your fire was out during a thick blizzard. Your assignment, finally, is over, And you are headed home with only one minor stop on the way. Is there anything you want to do before you leave this little house for good?
</p>

<br>

<p>
You tuck yourself in the rapidly cooling oven, not difficult with your abilities, close the door, and shuffle to the hole for the chimney, and past it, deeper into the yet comfortable wall, beyond where it should stop, and step out  around a corner into a tile-floored room with a rather ornate but pale-wooded door, a soft padding sound can be heard  outside
</p>

<br>
<br>

<p>
END<br>
Feywild
</p>

<p>
A nature check of 14 can be made to guess at what the sounds are.<br>
<div style='padding-left: 30pt'>
Culldersnatch
</div>
No action is needed to hide until the culdersnatch is alerted such as when a door is either opened or closed. After opening any seven doors (including the start), Philo Exits the Corridoorways. That said, within one pair of doors, there is a wrongoblin, who is as surprised as Philo is, but attacks anyway.
</p>

<p>
Your path travels wide across the branches of a spruigia forest, with branches thick enough to drive multiple carts on, to the thin river paths of a wanderswamp, into the dark branches of a Gamnus Oak and the local Xanarans, or it would be if it wasn't dracoon mating season.<br>
<div style='padding-left: 30pt'>
Three Dracoons attack
</div>
</p>

<br>
<br>
<br>
<br>


	</div>

	<br />

	<div class='page-footer'>
		<b>Backlinks:</b>

		<a href='..\How_You_Came_to_Be.html'>Nirrum's Encyclopedia of Varomar:Plot Notes:Homegroup 2023:How You Came to Be</a>

		<br /><br />

	</div>

	

</div>

</body>
</html>
