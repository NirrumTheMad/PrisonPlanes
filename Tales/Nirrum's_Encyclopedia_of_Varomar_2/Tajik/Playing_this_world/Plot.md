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
	[ <a href='./Personal_Time.html'>Prev</a> ]

	[ <span class='insen'>Index</span> ]

	[ <a href='./Plot/Battle_Against_time.html'>Next</a> ]
</div>

<hr />

<!-- Wiki content -->

<div class='pages'>
	<div class='heading'>
	<h1>Plot <a name='Nirrum's Encyclopedia of Varomar 2:Tajik:Playing this world:Plot'></a></h1>
	</div>

	<div class='content'>
	<p>
Created Friday 28 February 2025
</p>

<p>
BOTH AT THE SAME TIME
</p>

<p>
<a href="./Plot/Random_Events.html" title="+Random_Events" class="page">+Random_Events</a> <br>
<a href="./Plot/workshopping.html" title="+workshopping" class="page">+workshopping</a> <br>
<a href="./Plot/Sidequests.html" title="+Sidequests" class="page">+Sidequests</a> 
</p>

<br>

<h3>Introduction<a id="introduction" class="h_anchor"></a></h3>

<p>
Your story begins with its own ending. You have completed your mission, defeated a great issue in your world. <br>
&lt;Insert Vignette&gt;<br>
<a href="./Plot/Vignette.html" title="+Vignette" class="page">+Vignette</a> 
</p>

<br>
<br>

<p>
Our story really begins behind a star that has just died, and has been doing so for countless millenia. Even mostly frozen in time, the type 2a supernova leaks enough energy to cast a continuous glow into the universe around it.<br>
Slowly being cooked by this supernova is the world now known as Tajik. A pale world, with a ring of green on the edge of the sunny side of the tidally locked sphere, encircling the rays of the mortal sun, Frozen oceans, and a mostly barren, dark side, save for the cities that live as little points of light away from the catastrope of uncaged nuclear fury. This world is trapped between its exploding mother star and  <b>The Wall Where Angels Do Not Walk, Fields of Broken Seeds,  Colour that the Heavens Refuse to See, Infinite world of Writhing Karma, End of all Intent, </b>which is a seething mass of horror that marks the border of the universe. There are no stars on that side of the sky. Day and night are irregular on Tajik, as Magnetic storms occasionally reach long tendrils across the far side, creating slow, lazy auroras. Sometimes the supernova dims, as stolen time overcomes it, only to flare back to life with passing space debris, or its own echoes. Elsewise, the darkside is always dark, and the bright side is always bright. 
</p>

<p>
Somewhere in front of The Wall, behind the Dead Star, is the city of Hemma, where by accident or design, you have found yourself in a world of power beyond your wildest dreams, and unfortunately, you don't have much of that power. 
</p>

<br>
<br>

<p>
<i>"Your Contribution is?"</i>
</p>

<p>
Contributions to your insurance plan are an automatic assessment of your value, measured in sand, that you have provided, directly or indirectly. Most of a paycheque is often thrown directly at the Tajik Insurance Adjusters. Sand isn't necessarily accumulated exclusively through one's job, but some can be transferred to your account for services rendered by whoever you rendered them to. Sometimes, Tajik itself will move sand around, and people will find their plan has been adjusted without their knowledge. Sand is really measured in its allocation, not its specific collection, and it is up to a person of any given rank to spend the sand they are worth wisely, largely on those who allow them to function in such a way that enables them to reboot their operations completely. Anything left over is yours to keep, so there is great incentive to keep your organisation slim, but also redundant enough to function with hiccups. Submitting a regular sand allocation report is very much like submitting a will.
</p>

<p>
Wills on the other hand do not exist. The only thing that keeps a great many families at the top of the hierarchy is the passing of clandestine rituals that maintain critical sets of passwords for infrastructure. Passwords are the only key to power that a person can pass on, as ownership can become *very fluid very quickly* if an important member of an organisation is missing when it comes time to restart time. Some of the most protected passwords are to resanding systems. Unobtrusive locations which, upon being resanded, set into motion a rapid change in entropy, cascading through factories and workplaces in ways that quickly and evenly restarts their time. 
</p>

<p>
You will have already surpassed the uncounted. Those people who cannot defend themselves live as they can, their monster is all of their existence, for however long it lasts. Their use is as sand, only audible in mass, and their effect is similarly minute. Level ~1-3<br>
<ul style='padding-left: 30pt'>
<li>You are not allowed to eat anywhere except at the scrapzones, which is exclusively leftover food from other places. This is a gamble, the food has often spoiled but sometimes it holds extra potency over normal food.</li>
<li>The only way to escape being uncounted is to be noticed and taken up by a citizen of a higher contribution</li>
<li>Many Uncounted flock to the homes of the highest ranks, where they are often entirely invisible, feasting on crumbs.</li>
</ul>
</p>

<p>
Begin as a finite, a low-class numbered citizen. You must seek money for food or steal it. You have very little, you gain very little. Your concerns are the hierarchy of needs. Your monsters are other people who wish to take all they can take from you. Your class is kept sedated by the dribbles of exquisitely impossible power, the shadows of the strong, and the chance to cast shadows of your own. Your use is as flagstones for the strong. Level ~3-5<br>
<ul style='padding-left: 30pt'>
<li>You are allowed to eat and shop at actual stores</li>
<li>Main Quest: The Hustle </li>
</ul>
<div style='padding-left: 90pt'>
<a href="./Plot/the_hustle.html" title="+the_hustle" class="page">+the_hustle</a> 4<br>
<a href="./Plot/run_with_the_hunted.html" title="+run_with_the_hunted" class="page">+run_with_the_hunted</a> 5
</div>
</p>

<br>
<br>

<p>
Graduating from Finite to an Innumerable requires taking risks and making a difference. There are, ironically, a seemingly unending slew of Finites, all competing to become an Innumerable. When an Innumerable makes a decision, it can actually effect things, so one must be careful, but at least food and shelter are easier to obtain and keep. You still do not have much, but your concerns now are keeping what you have. Your monsters are people who wish to take your place, or prevent you from surpassing them, and occasionally beasts that try to sneak in. Your Class is kept in line by the much clearer paths to power you have access to. The powerful might even listen to you. Your use is to make paths for the strong. lvl ~5-7<br>
<ul style='padding-left: 30pt'>
<li>You are allowed to eat and shop at *mid-tier stores* and are allowed into parks and larger public green spaces	</li>
</ul>
<div style='padding-left: 30pt'>
<a href="./Plot/Crazy_Nights.html" title="+Crazy_Nights" class="page">+Crazy_Nights</a> 
</div>
</p>

<br>
<br>
<br>

<p>
Beyond the Innumerable are the infinites. When you make a decision, it <i>matters</i> in lasting ways. Food is brought to you, Shelter is prepared for you. The news only bothers to mention people like you. You cast a shadow into the sky. Your monsters are actual monsters, things that choose to interfere with what peace or good you have wrought. Your class is Kept in line by the constant onslaught of forces arrayed against you, and your desire to maintain your plan with the Tajik company. You are capable of deciding paths, making changes. Your use is to know the way of power, and to move power, such that you and those you like get to be brought back as soon as possible when the inevitable happens. Lvl ~7-11<br>
<ul style='padding-left: 30pt'>
<li>Fight Rifts</li>
<li>Fight Ma Ra agents</li>
<li>Direct the sanding of a full city</li>
<li><a href="./Plot/Battle_Against_time.html" title="+Battle_Against_time" class="page">+Battle_Against_time</a></li>
</ul>
</p>

<p>
After the Infinities are the Incalculable. You can't even see the problems you used to have, both for their insignificance and for their infrequency compared to your new problems. Your monsters are armies, plots, sometimes industries, and most frequently, paperwork. You are automatically assured a quick revival but not necessarily in the order you require. lvl ~11-14<br>
<ul style='padding-left: 30pt'>
<li>This Arc Begins with the opportunity to take a short vacation, It is in fact Mandatory, as this is one of the easiest ways to dodge some of the more insideous stolen time events. Homeworlds are recommended, you can take as many people as you'd like, with the expectation that you'll return within two weeks local time. Transportation of the form of your choice is set up for you
<ul>
<li>Any member of the Party that travels to Snarl is met with the opportunity to influence their own campaign</li>
</ul>
</li>
<li>At some point someone makes the comment "wait... you're an incalculable? What company are you even with? Wait are you incalculable on brute force? No Inventory management, no specific immunities? You don't have a password vault portfolio? Your Only asset is your ability to do physical battle?"
<ul>
<li>This person then goes deathly pale</li>
</ul></li>
</ul>
</p>

<p>
After the incalculable are the unequestionable. You are strong level 14+
</p>

<p>
Beyond that, there are no ranks, only names whose utterances are as weighty as national identity, sports teams that win, chapters in history books. 
</p>

<br>


	</div>

	<br />

	<div class='page-footer'>
		<b>Backlinks:</b>

		<a href='..\Playing_this_world.html'>Nirrum's Encyclopedia of Varomar 2:Tajik:Playing this world</a>

		<br /><br />

	</div>

	

</div>

</body>
</html>
