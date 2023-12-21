# TFTD Evolution by Alpha Centauri Bear

Main thread

https://openxcom.org/forum/index.php/topic,8661.0.html

Based on TFTD Rework by R Kallisti (aka Orz, Illamasqua)

https://openxcom.org/forum/index.php/topic,4265.0.html

Runs on Brual-OXCE by Xilmi

https://openxcom.org/forum/index.php/topic,10967.0.html

# Mod idea

Promote old fashion strategic game steady progress. Advanced research -> advanced equipment -> more dangerous events -> more advanced alien items and higher ranking officers -> even more advanced research -> and on and on.

All items (craft armament, gauss weapon, tank, armor, etc.) should have their game niche and be an essetial part of the game.

# Interception

Conventional crafts and armament are economically unfeasible for intercepting larger USOs. Develop more advanced armament to face more dangerous opponents and reduce expenses.

Below table shows approximate toughest USO that can be easily sinked by simultaneous attack of that many interceptors armed with this weapon. Superhuman difficulty.

| armament | 1B | 2B | 3B | 4B | 1M |
| ---- | ---- | ---- | ---- | ---- | ---- |
| Gas Cannon | Escort | Cruiser | H.Cruiser |  | Hunter |
| Gauss Cannon | Cruiser | H.Cruiser | Hunter |  | Dreadnaught |
| Sonic Oscillator | Hunter | Predator |  |  | Dreadnaught |
| AJAX | Cruiser | H.Cruiser | Hunter |  | H.Cruiser |
| D.U.P. | H.Cruiser | Hunter | Predator | F.S.Cruiser | H.Cruiser |
| P.W.T. | Hunter | Predator | Battleship | Dreadnaught | Hunter |

Projectiles are cheap and carry enormous payload but short ranged causing higher interceptor damage and risk of casualties. Barracudas with projectiles are useless against Battleship.

Torpedoes are expensive and have limited payload but long ranged preserving Barracudas. Large group of Barracudas with D.U.P. can take Battleship with minimal casualties. P.W.T. is even better.

# Combat

Untrained squad with conventional weaponry and without armor should not be able to recover medium USOs and above even with Aquatoids and Gillmen. One need to develop armor and good Gauss weapons for that. Larger USOs are even more deadly. More difficult base/ship missions require even better preparation and equipment. Better (alien) equipment, in turn, requires capturing live aliens of higher ranks from progressively larger USOs.

Note: first terror mission with Gillmen and Deep Ones should be barely passable with conventional equipment. However, it can also be skipped (landed and abort) to avoid grinding and heavy losses.

## Hand weapons (Gauss and Sonic series)

Gauss and Sonic weapon series powers are overlapping. Gauss Rifle is about as strong as Sonic Pistol and Heavy Gauss is about as strong as Sonic Rifle. That allows fighting Lobstermen and Tashots with Heavy Gauss should they pop up before Sonic Cannon is discovered.

Gauss weaponry is designed by humans for humans and, therefore, is optimized in fire rate and precision.

* faster
* more accurate

Sonic weaponry uses advanced alien power technology and lightweight alloys.

* lighter
* more powerful

Within the series heavier versions are more accurate but slower. Same as in vanilla.

## Damage modifiers

Alien rank complete armor stats are now in ufopaedia.

All Electric damage modifiers are set to 1.0. There is no weapon with this damage in TFTD.

Smoke damage modifiers are set to whole values. The damage is too tiny to multiply it by fractions.

Incindeary damage modifiers are set to whole values. The damage is too tiny to multiply it by fractions.

Values close enough to default (0.9 - 1.1) are converted to 1.0 to avoid displaying mostly useless modifiers.

Gauss and Sonic damage modifers are set to the same values for aliens except Tasoth. There is no need for *all* aliens to be less vulnerable to Gauss. Some are fine.

Incindeary damage is increased for all aliens. This damage itself is very low. That may add some incindeary related tactical play.

Lobsterman lowest damage modifiers are raised to 0.5. Anything lower than that is very difficult to balance across all aliens and weapons.

## Thermal shock bomb damage

Modified thermal shock bomb to make it more threatening to aquanaughts as well as more difficult to capture live aliens. Thermal shock is an explosive damage also delivering stun effect.

## Brutal AI adaptation

* Explosives power is reduced.
* All weapons have accuracy dropoff for all shot types (auto, snap, aimed) including all alien weapons. Same for all throwable explosives.
* 80% penalty for shooting not visible target.
* All projectile weapon accuracy is increased to compensate for above penalties. They are more precise up close but less accurate at far.

# Facilities

## General Stores

All item sizes are decreased 2-5 times to fit more into single General Stores facility. It seriously annoys me to not being able to buy a little bit more of equipment in first base right away.

## Workshop

Removed workshop space requirement per project. 50 engineers can work in one workshop.

I never understood strategic use for manufacturing *project* taking space, not the manufactured item themselves. Why one item takes same amount of additional space as ten? In my mind both laboratory and workshop are places where 50 specialists can do their work regardless of what they are working on. The rest of the supplies and ready items should reside in storage.

## Sonars

* All sonar ranges are increased to improve coverage.
* Sonar detection chances are reduced for long range detection facilities.

This way Short Range Sonar is quite useful from the beginning of the game and is the most economical option. More advanced detection facility versions are better at detection but costlier. Player may still benefit at having many facilities at base even after building Transmission Resolver.

| facility | build cost | maintenance | radar range | detection chance, % |
| ---- | ----:| ----:| ----:| ----:|
| Standard Sonar | 100,000 | 5,000 | 2500 | 10 |
| Wide Array Sonar | 800,000 | 40,000 | 2750 | 20 |
| Transmission Resolver | 1,400,000 | 100,000 | 3000 | 20 |

## Defenses

I don't see much point in USO defense combat randomization. It doesn't serve any tactical purpose. I assume player desires to protect base for good when they build defenses. Another thing I cannot understand is the nesessity to build 20 torpedo defenses at base to protect it. It is obviously excessive. It is much more simple to proportionally increase cost and value such facilities to reduce their needed quantities. With that in mind, I modified all defenses as follow.

* All defenses have 100% hit ratio and their damage is equal to Dreadnaught damage capacity. With that one defense facility shot sinks Dreadnaught with 50% probability and two shots guarantees Dreadnaught destruction. Player can either build two facilities or one with Bombardment Shield which is a little cheaper.
* Defenses maintenance becomes very high and comparable to interceptor maintenance since it serves about same purpose.
* More advanced defenses are more expensive to build but require lower maintenance. That gives player incentive to upgrade them. Every one level upgrade pays off in few months in reduced maintenance or even faster if jumping over levels.

| defense facility | build time, days | build cost | maintenance |
| ---- | ----:| ----:| ----:|
| Torpedo Defenses | 10 | 250,000 | 800,000 |
| Gauss Defenses | 15 | 500,000 | 700,000 |
| Sonic Defenses | 20 | 1,000,000 | 500,000 |
| P.W.T. Defenses | 25 | 2,000,000 | 100,000 |
| Bombardment Shield | 20 | 2,000,000 | 100,000 |

# Research

Manufacturable items are generally easier to reseach allowing player to use them at their discretion. Things like tanks, new subs, new armament, etc. - are beneficial but require time, money, engineers, and materials to produce and maintain/replenish. Their use should be balanced by their cost and effectiveness and not by placing them at the end of the tech tree.

Game milestones (T'Leth) and powerful game changing items (PWT Launcher, MC Disruptor, Transmission Resolver) have explicit difficult to obtain requirements to make hunt for them more interesting.

## Weapons and ammunition

All ammunition research are removed from the tree. Researching weapon immediately unlocks this weapon/ammo use and manufacturing.

## Alien technologies

Alien technologies depend on USO components and alien interrogations. Rare componentes and officers can be obtained from larger and more dangerous USO.

| component | appearance | leads to |
| ---- | ---- | ---- |
| Ion Beam Accelerators | Survey Ship | Manta |
| Magnetic Navigation | Survey Ship | Manta |
| Alien Sub Construction | Cruiser | Transmission Resolver |
| Alien Learning Arrays | Cruiser | MC Reader |
| Alien Cloning | Fleet Supply Cruiser | Hammerhead |
| Alien Cryogenics | Battleship | Leviathan |
| Alien Implanter | Dreadnought | MC Disruptor |

| rank | appearance | leads to |
| ---- | ---- | ---- |
| Soldier | Survey Ship | Sonic Pulser |
| Squad Leader | Escort | Sonic Pistol |
| Technician | Cruiser | Sonic Rifle |
| Medic | Heavy Cruiser | Thermal Shock Launcher |
| Navigator | Heavy Cruiser | Sonic Cannon |
| Commander | Dreadnought | PWT Launcher |

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
* (Experimental) thermal shock delivers both stun and health damage.
* (Experimental) Coelacanth and Displaceur are resistant to stun but not immune to it. Thermal shock bomb can stun/injure them.
* Reduces Xharquid under armor a little to make it killable with explosives. Still need like 4-6 grenades/rockets to deal with it.
* Increased Triscene under armor a little as it is NOT HE resistant.

## 16

* Adapted to Brutal-AI engine.
* Decreased explosives power to make more gradual progression.
* Adjusted HE damage modifiers and under armors to make more gradual progression.

