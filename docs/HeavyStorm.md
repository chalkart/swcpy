---
title: Heavy Stormtrooper (HeavyStorm)
category: unit
---

# Heavy Stormtrooper (HeavyStorm)

You can read an [explanation  of the various unit stats](unitexplained.md).

## Main stats

### Unit stats

  * Armor type: infantry
  * Side: Empire
  * Buildable unit: Yes
  * Role: Generic
  * Shield cooldown: 0s
  * Shield health: 0
  * Shield range: 0
  * Unit capacity: 4
  * Type: infantry

|Level |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|------|----|----|----|----|----|----|----|----|----|----|
|Health|3200|3840|4480|5120|5760|6400|7040|7680|8320|9600|


|Level |11   |
|------|-----|
|Health|10368|


### Training stats

|Level        |1                                |2                                      |3                                      |4                                      |5                                      |6                                      |7                                      |8                                      |9                                      |10                                      |
|-------------|---------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|----------------------------------------|
|Training time|1m20s                            |1m28s                                  |1m32s                                  |1m36s                                  |1m40s                                  |1m44s                                  |1m48s                                  |1m52s                                  |1m56s                                  |2m                                      |
|Training cost|200$                             |280$                                   |360$                                   |440$                                   |520$                                   |600$                                   |680$                                   |800$                                   |840$                                   |920$                                    |
|Building     |[Barracks 6](empireBarracks.html)|[Research Lab 2](empireOffenseLab.html)|[Research Lab 3](empireOffenseLab.html)|[Research Lab 4](empireOffenseLab.html)|[Research Lab 5](empireOffenseLab.html)|[Research Lab 6](empireOffenseLab.html)|[Research Lab 7](empireOffenseLab.html)|[Research Lab 8](empireOffenseLab.html)|[Research Lab 9](empireOffenseLab.html)|[Research Lab 10](empireOffenseLab.html)|


|Level        |11                                      |
|-------------|----------------------------------------|
|Training time|2m4s                                    |
|Training cost|1000$                                   |
|Building     |[Research Lab 11](empireOffenseLab.html)|


### Upgrading stats

|Level               |1    |2    |3    |4     |5     |6      |7      |8      |9       |10      |
|--------------------|-----|-----|-----|------|------|-------|-------|-------|--------|--------|
|Upgrade time        |0s   |15m  |1h   |3h30m |8h    |1d     |2d     |3d12h  |5d      |1w2d    |
|Upgrade requirements|3000$|3000$|6000$|12500$|25000$|100000$|160000$|320000$|1000000$|1750000$|


|Level               |11      |
|--------------------|--------|
|Upgrade time        |1w3d    |
|Upgrade requirements|3500000$|


### Movement stats

  * Acceleration: 0
  * Crushes walls: No
  * Flying unit: No
  * Max speed: 20
  * Propensity to go around obstacles: 15
  * Rotation speed: 7.854
  * Run speed: 0
  * Run threshold: 0
  * Unit size on map: 1x1

## Main attack : HeavyStorm

### Targeting

  * Attack shield border: No
  * Max attack range: 7
  * Min attack range: 0
  * New rotation speed: 7854
  * Target preference strength: 90
  * Target preferences: **Droideka (50)**, **Flying infantry (50)**, **Flying vehicle (50)**, **Headquarters (50)**, **Heavy infantry (50)**, **Heavy vehicle (50)**, **Infantry (50)**, **Light vehicle (50)**, **Other building (50)**, **Ressource generator (50)**, **Shield (50)**, **Shield generator (50)**, **Storage (50)**, **Support troop (50)**, **Turret (50)**, Heavy infantry hero (1), Heavy vehicule hero (1), Infantry hero (1), Vehicule hero (1), Wall (1), Trap (0)
  * View range: 8

### Shooting

  * Animation delay: 0
  * Charge time: 500ms
  * Clip retargeting: No
  * Gun shooting sequence: 1
  * Impact delay: 500ms
  * Can shoot over walls: No
  * Reload time: 2s
  * Retargeting offset: 14
  * Self-centered targeting: No
  * Shot count: 10
  * Shot delay: 100ms
  * Target locking: No

|Level          |1  |2  |3  |4  |5  |6  |7  |8  |9  |10 |
|---------------|---|---|---|---|---|---|---|---|---|---|
|Damage per shot|177|213|248|283|319|354|389|425|460|531|


|Level          |11 |
|---------------|---|
|Damage per shot|573|


### Projectile

|Level                       |1   |2   |3   |4   |5   |6   |7   |8   |9   |10  |
|----------------------------|----|----|----|----|----|----|----|----|----|----|
|Displayed damage per second |520 |626 |729 |832 |938 |1041|1144|1250|1352|1561|
|Calculated damage per second|505 |608 |708 |808 |911 |1011|1111|1214|1314|1517|
|Calculated damage per cycle |1770|2130|2480|2830|3190|3540|3890|4250|4600|5310|


|Level                       |11  |
|----------------------------|----|
|Displayed damage per second |1561|
|Calculated damage per second|1637|
|Calculated damage per cycle |5730|


  * Cannons per sequence: 1
  * Shooting cycle duration: 3.500s
  * Directional: Yes
  * Is deflectable: No
  * Max speed: 30
  * Damage multipliers: **(175)**: Shield, Shield generator, **(100)**: Droideka, Flying infantry, Flying vehicle, Headquarters, Heavy infantry, Heavy infantry hero, Heavy vehicle, Heavy vehicule hero, Infantry, Infantry hero, Light vehicle, Other building, Ressource generator, Storage, Support troop, Trap, Turret, Vehicule hero, **(80)**: Wall
  * Pass through shield: No
  * Salvos: 10

## Internal stats

These stats internal to the system link different parts of data together.

  * Unit ID: HeavyStorm

## Presentation stats

These are all sorts of user interface settings, that should not interfere with gameplay.

  * Arcs: No
  * Asset name: heavytrooper_emp-ani
  * Audio attack: "sfx_attack_gatlinggun_1":30,"sfx_attack_gatlinggun_2":35,"sfx_attack_gatlinggun_3":35
  * Audio death: "sfx_death_troop_1":10,"sfx_death_troop_2":10,"sfx_death_troop_3":10,"sfx_death_troop_4":10,"sfx_death_troop_5":10,"sfx_death_troop_6":10,"sfx_death_troop_7":10,"sfx_death_troop_8":30
  * Audio placement: "sfx_placement_troop_1":35,"sfx_placement_troop_2":35,"sfx_placement_troop_3":30
  * Audio train: "sfx_ui_unitcomplete_stormtrooper_01":35,"sfx_ui_unitcomplete_stormtrooper_02":35,"sfx_ui_unitcomplete_stormtrooper_03":30
  * Buff asset offset: 0.00,0.28,0.00
  * Bundle name: heavytrooper_emp-ani
  * Death animation: buffFireBurn:15
  * Factory rotation: 0
  * Factory scale factor: 1
  * Favorite target type: closest
  * Gun position: "atst_emp_rig_MASTER_MOVER/atst_emp_rig_locator_gun":1
  * Hit spark: fx_gatling_hit_r_lrg
  * Icon camera position: 7.72,10.75,21.04
  * Icon closeup camera position: 1.24,0.61,11.39
  * Icon closeup lookat position: -0.02,2.5,-0.01
  * Icon lookat position: -0.4,1.77,0.55
  * Max scale: 100
  * Muzzle flash: fx_gatling_muzzle_r_lrg
  * Name: HeavyStorm
  * Spin speed: 0
  * Targeted type: ENEMIES

|Level                      |1          |2          |3          |4          |5          |6          |7          |8          |9          |10         |
|---------------------------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|
|Deploy vfx                 |(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|
|Displayed damage per second|520        |626        |729        |832        |938        |1041       |1144       |1250       |1352       |1561       |
|Prestige                   |(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|


|Level                      |11                           |
|---------------------------|-----------------------------|
|Deploy vfx                 |vfx_prestige_deploy_small_emp|
|Displayed damage per second|1561                         |
|Prestige                   |true                         |


## Uninterpreted stats

Seriously, we don't really know what to do with these.

  * Arming delay: 0
  * Auto spawn rate scale: 1
  * Auto spawn spreading scale: 1
  * Max scale: No
  * Seeks target: Yes
  * Splash: 0
  * Streams: no
  * Strict cool down: No
  * Target in range modifier: 1
  * Xp: 0

|Level      |1    |2    |3    |4    |5    |6    |7    |8    |9     |10   |
|-----------|-----|-----|-----|-----|-----|-----|-----|-----|------|-----|
|Order      |60601|60602|60603|60604|60605|60606|60607|60608|60609 |60610|
|Point value|4    |4.800|5.600|6.400|7.200|8    |8.800|9.600|10.400|12   |


|Level      |11   |
|-----------|-----|
|Order      |60611|
|Point value|12   |


