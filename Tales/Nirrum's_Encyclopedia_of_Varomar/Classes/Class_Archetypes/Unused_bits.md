<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
	<title>Unused bits</title>
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
	[ <a href='./True_Hunter.html'>Prev</a> ]

	[ <span class='insen'>Index</span> ]

	[ <a href='./Way_of_Eight_steps.html'>Next</a> ]
</div>

<hr />

<!-- Wiki content -->

<div class='pages'>
	<div class='heading'>
	<h1>Unused bits <a name='Nirrum's Encyclopedia of Varomar:Classes:Class Archetypes:Unused bits'></a></h1>
	</div>

	<div class='content'>
	<p>
Created Wednesday 26 February 2020
</p>

<p>
<s>Mythweft</s><br>
<div style='padding-left: 30pt'>
<s>When you reach 18th level, You recieve one  based on your choice of talespinning from 1st level</s>
</div>
</p>

<p>
<s>Lore. You have captured some power that stood beyond your grasp. You learn one spell from any spell list. You must otherwise obey all the restrictions for selecting the spell, and it becomes a sorcerer spell for you and does not count toward your spells known. If it has the ritual tag, you can perform that spell as a ritual.</s><br>
<s>Valor. Tales do not end without your say-so. As a reaction, you can spend two sorcery points to add or subtract your charisma modifier to an attack or damage roll made by a creature within 60ft of you. </s><br>
<s>Glamour. Your stunning presence is too powerful to harm, you made sure of that. As a reaction, when a creature makes an attack roll against you, you can spend two sorcery points to force that creature to make a Charisma saving through against your spell save DC. On a failed save, it must choose a new target for the attack or the attack is wasted. On a successful save it has disadvantage against your spells on your next turn.</s><br>
<s>Swords. All magic seems to come from your sword. When you damage a creature with a spell cast through your chosen melee weapon, you may roll your weapon's damage and add it to the damage total.</s><br>
<s>Whispers. You pick apart the remnants of the dead to learn what could have hurt them. When a creature dies within 30ft of you, you capture its shadow. You learn all information that the creature would freely share with a casual acquaintance as well as a single ruinous secret that the target would not wish its enemies to know.  You also gain the ability to unerringly mimic the target's voice if it has one. You can only have one such shadow at a time</s> 
</p>

<br>
<br>

<p>
<s>Terror. You sing fear into creatures that can feel it, and force those who have never known it to experience it.  As a bonus action Creatures of your choice within 60ft of you that can hear you have disadvantage against effects that would cause them to be frightened. Those creatures lose immunity to the Frightened condition if they have it. This effect lasts for one minute. You can spend a sorcery point to extend the duration to one hour, or two sorcery points to extend it to 8 hours.</s> 
</p>

<br>

<p>
go invisible on reaction on passed save, leave body behind
</p>

<br>
<br>
<br>
<br>

<p>
<b>Disciple of Magic</b><br>
<div style='padding-left: 30pt'>
When you choose this tradition at 3rd level, you learn how to manipulate Magic with your ki. Choose
</div>
choose two disciplines, learn more at 6.11.17, gain a level to replace<br>
Casting E Spells. Some e<br>
disciplines allow you to cast spells. See chapter 10<br>
of the Player’s Handbook for the general rules of<br>
spellcasting. To cast one of these spells, you use its<br>
casting time and other rules, but you don’t need to<br>
provide material components for it. When you cast a<br>
spell with a discipline, it is cast at the spell’s lowest<br>
level unless otherwise specified.<br>
Once you reach 5th level in this class, you can spend<br>
additional ki points to increase the level of an elemental<br>
discipline spell that you cast, provided that the spell has<br>
an enhanced effect at a higher level, as burning hands<br>
does. The spell’s level increases by 1 for each additional<br>
ki point you spend. For example, if you are a 5th-level<br>
monk and use ROPADOPE FIX THISyou can spend 2 ki points to cast it as a 2nd-level<br>
spell (the discipline’s base cost of 1 ki point plus 1).<br>
The maximum number of ki points (its base ki point<br>
cost plus any additional points) that you can spend on<br>
the spell is 2, unless a discipline specifies otherwise.<br>
This maximum increases to 3 at 9th level, 4 at 13th<br>
level, and 5 at 17th level.
</p>

<p>
Bitchin disciplines:<br>
<div style='padding-left: 30pt'>
1st level spells for 1<br>
bonus action cantrip
</div>
</p>

<p>
Ballin Disciplines <br>
<div style='padding-left: 30pt'>
Make something automatic<br>
2nd level spells for 2 with some effect<br>
Mini 3rd level spells<br>
PATIENT BADGER LISTENS
</div>
blastin disciplines<br>
<div style='padding-left: 30pt'>
3rd level spells for 3
</div>
Best disciplines<br>
<div style='padding-left: 30pt'>
for 5 R/BPS/Other, Movement, bonus action 1d10-3d6<br>
5th level spells for 5
</div>
</p>

<br>
<br>

<p>
5 ki Revive+heal 4d10<br>
Reaction melee on ally melee
</p>

<br>

<p>
<b>Torchbearer. Hold onto and double another's mage's spell</b>
</p>

<p>
<b>Ki points to recharge spells</b><br>
<b>For 2 ki points You may change the target of a spell or magical effect within</b> <br>
<ul>
<li>You become blind and deaf to anything that isn't magical in nature for one minute or until you end this effect as a bonus action. Shapeshifters appear in their true forms, things covered by illusions appear as they would without the illusion. Magical items and creatures concealed by magic appear as if illuminated by bright light, even if their nature would not normally allow this. All magic produces distinct sounds, making them perceivable as if visible. This state ignores mundane or magical darkness or effects of silence, as well as sublte metamagic. Creatures with intrinsic magic abilities glow dimly, creatures </li>
</ul>
</p>

<p>
<b>Weapon of all worlds</b> <br>
At second level you gain proficiency with martial weapons and can use wisdom as your modifer for attacks made with this weapon. Weapon attacks you make count as magical for the purposes of overcoming resistances and immunities. As a bonus action you can change the damage type that a weapon or piece of ammunition you are holding does. Some damage types have minor extra effects<br>
<ul style='padding-left: 30pt'>
<li>Poison - creatures struck by this weapon must make a saving throw against your spell save DC  or be poisoned until the start of your next turn</li>
<li>Acid - Constructs and objects take extra damage equal to your wisdom modifier from this weapon</li>
<li>Radiant - This weapon sheds bright light for 30ft and dim light 20 beyond. This light is sunlight.</li>
<li>Lightning - Weapon becomes magnetic</li>
<li>Thunder - This weapon hums ominously, makes cracking sounds when swung and impacts from this weapon can be heard for up to 200ft away.</li>
<li>Force -  The weapon Ignores gravity and hovers in place until the end of your next turn when dropped or until another force is applied. </li>
</ul>
 This effect lasts for a minute or until the end of your next turn if you let go of or throw the weapon. Other Damage types have minor flavour effects, such as fire giving off warmth and light comparable to a small campfire, or necrotic causing minor rashes on prolonged contact.
</p>

<br>

<p>
<b>Spring Within.</b><br>
<div style='padding-left: 30pt'>
You tap into your eld powers. You no longer need to sleep and can no longer be put to sleep magically. When you rest, you may instead disappear and spend your time in the dreams of another creature for 4 hours, though nothing in the dream can affect you. A creature that remembers its dreams might remember your presence in them. If their sleep is interrupted, you quietly appear in the nearest unoccupied space. If you sleep normally you find your dreams extremely wild, vivid, and filled with fey creatures. If you ever meet any of these fey creatures they can confirm the dream's occurence. You also speak, read, and write sylvan (and also old gaelic, but the difference is subtle). 
</div>
</p>

	</div>

	<br />

	<div class='page-footer'>
		<b>Backlinks:</b>

		<a href='..\Class_Archetypes.html'>Nirrum's Encyclopedia of Varomar:Classes:Class Archetypes</a>

		<br /><br />

	</div>

	

</div>

</body>
</html>
