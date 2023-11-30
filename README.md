# TFTD Rework: Evolution by Alpha Centauri Bear

Main thread

https://openxcom.org/forum/index.php/topic,8661.0.html

Based on TFTD Rework by R Kallisti (aka Orz, Illamasqua)

https://openxcom.org/forum/index.php/topic,4265.0.html


# Mod idea

* All weapons (both hand and craft) are usable at least in their respective time. Gauss weapons should not be skipped.

# Hand weapons (Gauss and Sonic series)

Gauss and Sonic weapon series powers are overlapping. Gauss Rifle is about as strong as Sonic Pistol and Heavy Gauss is about as strong as Sonic Rifle. That allows fighting Lobstermen and Tashots with Heavy Gauss should they pop up before Sonic Cannon is discovered.

Gauss weaponry is designed by humans for humans and, therefore, is optimized in fire rate and precision.

- faster
- more accurate

Sonic weaponry uses advanced alien power technology and lightweight alloys.

- lighter
- more powerful

Within the series heavier versions are more accurate but slower. Same as in vanilla.

# USOs

All USOs attack range is 60. Now interceptors receive some damage from each attack. Could be pretty small from tiny USOs but still something to take into account when planning an intercept. DUP does not guarantees imputnity anymore. More powerful aramament allows faster kill reducing interceptor damage. Group attack futher reduces interceptor damage.

USOs damage capacity are about doubled and their weapon power is about halved with some adjustments here and there. That doesn't change their overall threatening but prolongs combat and makes initial approaching less devastating to interceptors. Crafts with projectile armaments now able to close up and unleash their power. Number of misslie loads were increased proportionally to compensate for higher enemy damage capacity.

All alien subs have same reload time: 24s. This parameter directly affects sub firepower but is not shown in UFOpaedia which makes relative sub firepowers obscure to user. Now when it is same for all alien submarines their UFOpaedia entries with weapon power and damage capacity completely defines their corresponding aggressiveness and toughness. Now when player sees one alien sub having twice more powerful weapon they can expect twice as more damage to their interceptors.

The above change also uniformly changes all USOs firepower with difficulty level. Which lets player correctly estimate damage to interceptor on different difficulty levels.

| difficulty | firepower multiple |
| ---- | ----:|
| Beginner | 100% |
| Experienced | 109% |
| Veteran | 120% |
| Genius | 150% |
| Superhuman | 200% |

# X-Com craft armament

## Projectiles

- cheaper
- shorter range
- higher firepower
- enourmous payload

Projectile equipped interceptors should attack tougher target in as large group to compensate for damage and losses on approach.

## Missiles

- more expensive
- longer range
- lower firepower
- limited payload

Missile equipped interceptors can attack in group. However, they also can attack one by one from relative safety. It may require more attacks to sink larger targets due to limited payload.

## Comparative table

1B, 2B, 3B, 4B, 1M - toughest USO that can be sunk by simultaneous attack of so many interceptors (Barracuda or Matha). Losses may occur.

| armament | cost | range | 1B | 2B | 3B | 4B | 1M |
| ---- | ---- | ----:| ---- | ---- | ---- | ---- | ---- |
| Gas Cannon | near zero | 10 | Cruiser | H.Cruiser | Hunter | Predator | Hunter |
| Gauss Cannon | low | 20 | H.Cruiser | Predator | Battleship | Dreadnaught | Dreadnaught |
| Sonic Oscillator | high | 30 | Hunter | F.S.Cruiser | Dreadnaught |  | Dreadnaught |
| AJAX | average | 40 | H.Cruiser | Hunter | Predator | Battleship | Hunter |
| D.U.P. | very high | 50 | H.Cruiser | Predator | F.S.Cruiser | Dreadnaught | Hunter |
| P.W.T. | immensive | 60 | Hunter | Predator | Battleship | Dreadnaught | Hunter |

## Tactics

* Use projectile armament to save money on regular not too dangerous targets. Attack more dangerous targets in group.
* Use missiles for faster response, better coverage, and easier combat, for the expense of extra ammo cost.
* Missiles are good for Barracudas to ensure their safety against stronger opponents.
* Matha and above are better off with projectiles as they can easily withstand approaching even strongest opponents on their own.

# Facilities

## General Stores

All item sizes are decreased 2-5 times to fit more into single General Stores facility. It seriously annoys me to not being able to buy a little bit more of equipment in first base right away.

## Defenses

I don't see much point in USO defense combat randomization. It doesn't serve any tactical purpose. I assume player desires to protect base for good when they build defenses. Another thing I cannot understand is the nesessity to build 20 torpedo defenses at base to protect it. It is obviously excessive. It is much more simple to proportionally increase cost and value such facilities to reduce their needed quantities. With that in mind, I modified all defenses as follow.

* All defenses have 100% hit ratio and their damage is equal to Dreadnaught damage capacity. With that one defense facility shot sinks Dreadnaught with 50% probability and two shots guarantees Dreadnaught destruction. Player can either build two facilities or one with Bombardment Shield which is a little cheaper.
* Defenses maintenance becomes very high and comparable to interceptor maintenance since it serves about same purpose.
* More advanced defenses are more expensive to build but require less maintenance. That gives player incentive to upgrade them.

| defense facility | build time, days | build cost, thousands | maintenance, thousands |
| ---- | ----:| ----:| ----:|
| Torpedo Defenses | 10 | 500 | 750 |
| Gauss Defenses | 15 | 1000 | 500 |
| Sonic Defenses | 20 | 1500 | 250 |
| P.W.T. Defenses | 25 | 2000 | 0 |

# Unit stats and armors

TFTD Rework set Tashoth health to 90. I think it is a mistake. Reset it to about vanilla values.

Reduced Deep One armor and health slightly. I understand Orz wanted some more challenge with them. However, they appear at first terror mission at the end of January and players absolutely rookie weaklings should fight them with conventional weapons or gauss pistols at best. I'd say it is too much of a challenge.

Reduced Coelacanth armor a little. Otherwise, it is impenetrable for Sonic Pistols.

Reduced Ion and Mag-Ion armour values a little. It is overprotective in vanilla.

Swapped Ion and Mag-Ion armour side and rear values. I never could understand this "brilliant" innovation in TFTD.

Increased soldiers' initial health to 30-50 and health cap to 80. This is in conjunction with their armor value decrease to make them wounded instead of instantly dying more often.

# Alien damage modifiers

The main problem with damage modifier is that they are NOT VISIBLE to player nor they are satisfactory referenced in description. Besides, same effect can be achieved by modifying armor value directly. With the above in mind damage modifiers were changed like that.

* All Gauss and Sonic damage modifier values are 1.0 for all creatures. These damages are most common and should be used as benchmark.
* All damage modifier values are standardized to use 0.5 step for simplicity of description and to make effect noticeable to player.
* Armor values of top level creatures (toughest Lobstermen) are increased to compensate for Gauss/Sonic DM modification.

| damage modifier | description |
| ----:| ---- |
| 0.0 | immune |
| 0.5 | resistant |
| 1.0 | normal |
| 1.5 | sensitive |
| 2.0 | vulnerable |

Some sample damage modifiers

* Ion armor and magnetic ion armor are immune to fire and smoke.
* All alien soldiers, Tentaculat, Hallucinoid are vulnerable to fire.
* Tentaculat is sensitive to HE.
* Lobsterman is resistant to AP and HE but vulnerable to drill.
* Xarquid and Biodrone are resistant to HE but sensitive to drill.
* Hallucinoid is resistant to AP, HE, freeze, drill. Looks like fire is the best way to kill it.
* Coelacanth/Displaceur is resistant to AP, HE, Gauss and immune to stun and smoke (obviously).

# Research

## Hand weapons

Gauss Pistol research cost is reduced to 50. This is the first and weakest manufactured weapon. Need to shorten the research to load technicians with something right away.

Gauss Rifle and Heavy Gauss research costs are reverted to their vanilla values. TFTD Rework added some extra cost on top. I don't think this is really needed. Their costs are adequate to very beginning of the game when player don't have too many scientists.

Sonic hand weapon research costs are progressively increased. Vanilla Sonic Cannon research cost was about the same as Sonic Pistol. Now it is twice bigger.

## Aliens

Alien containment is not given at start but is available after any autopsy (alien or terrorist). This way it requires some (logical) reseach to get built.

A lot of alient technology depends on further alien interrogation.

| technology | dependencies |
| ---- | ---- |
| Alien Containment | any autopsy |
| MC Reader | Alien Lerning Arrays (Cruiser and above) |
| MC Lab | MC Reader, Medic |
| MC Disruptor | MC Lab, Alien Implanter, high ranked psi skilled alien |
| Sonic Pulser | Soldier |
| Sonic Pistol | Squad Leader |
| Sonic Rifle | Technician |
| Sonic Cannon | Sonic Rifle, Navigator |
| Transmission Resolver | Sonic Cannon, Commander |
| Disruptor Pulse Launcher | Sonic Cannon, Commander |
| Manta | Alien Sub Construction, Alien Cloning, Technician |
| Hammerhead | Manta, Alien Cryogenics, Navigator |
| Leviathan | Hammerhead, Alien Implanter, Commander |
| Transmission Resolver | Alien Sub Construction, MC Reader |
| Alien Origins | interrogate all five alien races |
| Ultimate Threat | Alien Origins, Lobsterman Navigator, Lobsterman Commander |
| T'Leth Alien City | Ultimate Threat, Squidface Navigator, Squidface Commander |

# Increased challenge

## Armor

Balanced armor thikness between toughest aliens and power suits. That probably prolongs the challenge in late game which is now a cakewalk.

* Aliens are slightly tougher. Especially higher ranking ones.
* Aquanaughts power suits are slightly weaker.

## Thermal shock damage

Modified thermal shock to make it more threatening to aquanaughts as well as more difficult to capture live aliens.

* Thermal shock applies part of its damage to health stunning and injuring target at the same time.
* Tanks are resistant to stun but not immune, thus receiving some small damage from shock.

# Changelog

## 1.7

Carrying item weights modified. I don't like how heaviest weapon weights same as 4-6 hand grenades. That allows soldiers to carry such supposedly immensely heavy stuff by just not carrying some extra trinkets. Soldiers should become really strong to be able to even lift such devastating weaponry. Weapon weight should be an important factor of its usability. The primary weapon(s) should mostly define the soldier load and carrying multiple weapons should be costly as opposed to carrying multiple different tools/trinkets.

* All hand weapons (ranged and melee) are heavier proportionally to their power/size/series/level. Pistols are about the same weight. Heavy versions are much heavier, especially Gauss and Sonic series.
* All clips are are lighter but stay proportional to their respective weapon weight.
* All explosives keep their weight more or less to keep their thrown distance intact.
* Dye grenades and chemical-flares are much lighter.
* All non weapon tools are significantly lighter.
* Disruptor pulse launcher ammo weight is increased since it is an actual torpedo.

## 1.8

* Further alien subs and craft armament parameters adjustments.
* Smaller alien sub escape timer is increased a little to make them not necessarily flee from prolonged battle all the time. They still can randomly escape, though.
* Fleet Supply Cruiser damage capacity is increased slightly to make it slightly more threatening. Is has the lowest firepower in the size class.
* The new Battlestar/Predator alien sub weapon power is lowered to place it somewhere between medium and large USOs. It is now the easiest one to fight in large size class followed by Fleet Supply Cruiser then by Battleship.
* Battleship stays as most agressive sub beating Dreadnought by firepower. Yet its damage capacity is lowest among other large subs so it can be taken out by DUPs relatively safe.
* Conventional craft armaments firepower is reduced to distinguish them from advanced ones. Advanced armaments firepower slightly adjusted too.

## 1.9

* Decreased AJAX reload time thus increasing its firepower a little.

## 1.10

* Particle Disturbance Grenade gets a little heavier but much more powerful with bigger blast radius. Essentially it becomes a land mine. I think it will increase its use at least against Aquatoids/Gillmen because of guaranteed kill.
* Decreased AJAX and DUP firepower a tille to make them no better than advanced weaponry.
* Further adjusted medium and small USOs to make them more equal in the class. All small and tiny USOs now can be taken out by single Gas Cannon Barracuda. Meduim requires two. Predator requires three being sort of an intermediary step between medium and large. FSC requires four. And neither Battleship nor Dreadnought are vulnerable to four conventional armed Barracudas.
* Further reduced Zrbite requirement for P.W.T. Cannon ammo to 2. Otherwise, it becomes too economically unfeasible to use them even against larger USOs.

## 1.11

* Removed all armor bonuses. They are displayed inconsistently and ugly in different screens and Meridian doesn't want to fix it.
* Made all Gauss and Sonic hand weapons lighter. I made them too heavy before.
* Further reduced Coelacanth/Harpoon cost. With stripped cash it is a money eater.
* Doubled Coelacanth/AquaJet load. It is a nice aquisition but 8 missiles is not enough. Also made it not underwater only to help on terror missions.
* Reduced weapon power of smaller USOs a little. It seems they can can damage interceptors quite much by constantly escaping.

## 1.12

* Another increase in store capacity to 150. It is pretty annoying to use up all base space with storage facilities.
* Reworked damage modifiers.
* Reworked item weights.
* Reduced combattant armor and Coelacanth armor a little to make them not completely forgiving.
* Set initial melee accuracy to 40-60 instead of ridiculous 20-40.

## 1.13

* Exact TU recomputed to avoid stupid values like 50 when theoreticaly soldier can make two shots being completely motionless. While a single wigle of their head eating 1 TU suddenly denies them a second one. All values above guarantee predicted number of shots even for the cases when soldier turns 90 degrees left or right for reaiming on moved target.
* Both pistols are given more shots than in previous version. Gauss pistol now feels like SMG with its 12 bullets per turn on automatic.
* Accuracy slightly specialized comparing to previous version. Pistols are more accurate on short range, heavies are on long range, rifles are balanced for tactical combat.
* Gauss cannon is now somewhat better than AJAX especially against small and medium USOs. Less number of interceptors required and less damage sustained from attacks. It makes sense to use it to reduce repair time and responsiveness.
* Cephalid damage modifiers to both gauss and sonic are now 1.0. I missed this one in previous version as it was in separate file.
* Triscene side armor is reduced slightly. Now it can be scratched by HG/SR and definitely killed in few shots by SC. Its under armor is increased instead to make it not fall like a fly from grenades.
* Set initial strength to 30-50. It is impossible to carry anything with 20 strength. Such weaklings were immediately rejected anyway.

## 1.14

* Created special often used dependencies and gave them meaningful names for ease of further editing and understanding research tree. As the result many dependencies became quite simple and intuitive.
* Alien containment depends on alien corpse and terrorist corpse. Should be available to research after first successful terror mission.
* MC reader depends learning arrays which can be found in heavy cruiser.
* MC lab depends on MC reader and medic interrogation.
* MC disruptor dependes on MC lab, alien implanter and high ranked psi skilled alien.
* All alien weapon dependencies are same as before just redefined using more intuitive dependencies.
* Alien origins depends on researching all five alien races.
* The ultimate threat depends on alien origins and lobsterman navigator+commander interrogation
* T'leth alien city depends on the ultimate threat and squidface navigator+commander interrogation
* New subs have same interrogation dependencies plus additional sub components.
* Ion armour depends on Lobsterman autopsy instead of Deep One interrogation.
* Magnetic ion armour dependends on ion armour, magnetic navigation and displacer sonic.

## 1.15

* Reverted initial strength to 20-40. I think it is enough for light weaponry.
* Roughly doubled all missile damage but reduced their fire rate. Thus keeping their firepower but increasing payload. Now they are slightly more payload sufficient.
* Reverted General Store space back to 50 and reduced item sizes by 2-5 times, especially small items used in large quantities: grenades, clips, ammo, etc.
* Slightly reduced X-Com armor and slightly increased alien armor.
* (Experimental) Half of the thermal shock bomb damage goes toward health injuring the target. Aquanaughts will eventually die from fatal wounds if not healed.
* (Experimental) Coelacanth and Displaceur are resistant to stun but not immune to it. Thermal shock bomb can stun/injure them.

