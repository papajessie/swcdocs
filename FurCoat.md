---
title: Bufopel Protector (FurCoat)
category: unit
---

# Bufopel Protector (FurCoat)

You can read an [explanation  of the various unit stats](unitexplained.md).

## Main stats

### Unit stats

  * Armor type: infantry
  * Side: Rebellion
  * Buildable unit: No
  * Role: Generic
  * Unit capacity: 4
  * Type: infantry

|Level |10   |9    |8    |7    |6    |5    |4    |3    |2    |1    |
|------|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
|Health|20400|18580|17220|16320|15410|14500|13600|12690|11780|10880|


### Training stats

|Level        |10                                     |9                                     |8                                     |7                                     |6                                     |5                                     |4                                     |3                                     |2                                     |1                               |
|-------------|---------------------------------------|--------------------------------------|--------------------------------------|--------------------------------------|--------------------------------------|--------------------------------------|--------------------------------------|--------------------------------------|--------------------------------------|--------------------------------|
|Training time|30s                                    |29s                                   |28s                                   |27s                                   |26s                                   |25s                                   |24s                                   |23s                                   |22s                                   |20s                             |
|Training cost|230$                                   |210$                                  |200$                                  |170$                                  |150$                                  |130$                                  |110$                                  |90$                                   |70$                                   |50$                             |
|Building     |[Research Lab 10](rebelOffenseLab.html)|[Research Lab 9](rebelOffenseLab.html)|[Research Lab 8](rebelOffenseLab.html)|[Research Lab 7](rebelOffenseLab.html)|[Research Lab 6](rebelOffenseLab.html)|[Research Lab 5](rebelOffenseLab.html)|[Research Lab 4](rebelOffenseLab.html)|[Research Lab 3](rebelOffenseLab.html)|[Research Lab 2](rebelOffenseLab.html)|[Barracks 1](rebelBarracks.html)|


### Upgrading stats

  * Upgrade time: 0s

|Level               |10                |9                 |8                |7                |6                |5                |4                |3                |2                |1                |
|--------------------|------------------|------------------|-----------------|-----------------|-----------------|-----------------|-----------------|-----------------|-----------------|-----------------|
|Upgrade requirements|160 data fragments|120 data fragments|90 data fragments|70 data fragments|60 data fragments|50 data fragments|40 data fragments|30 data fragments|28 data fragments|32 data fragments|


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

### Modifiers

#### Modifier "Resilience"

  * Resilience apply value as: relativePercent
  * Resilience buff ID: buffResilience
  * Resilience duration: permanent
  * Resilience modifier: defense
  * Resilience ms first proc: 10s
  * Resilience ms per proc: 10s
  * Resilience name: Resilience
  * Resilience stack: 5
  * Resilience target: self
  * Resilience value: -25.0%


## Main attack : Melee Vibro Mace

### Targeting

  * Attack shield border: No
  * Max attack range: 2
  * Min attack range: 0
  * New rotation speed: 7854
  * Target preference strength: 90
  * Target preferences: **Droideka (50)**, **Flying infantry (50)**, **Flying vehicle (50)**, **Headquarters (50)**, **Heavy infantry (50)**, **Heavy vehicle (50)**, **Infantry (50)**, **Light vehicle (50)**, **Other building (50)**, **Ressource generator (50)**, **Shield (50)**, **Shield generator (50)**, **Storage (50)**, **Support troop (50)**, **Turret (50)**, Heavy infantry hero (1), Heavy vehicule hero (1), Infantry hero (1), Vehicule hero (1), Wall (1), Trap (0)
  * View range: 12

### Shooting

  * Animation delay: 500ms
  * Charge time: 400ms
  * Clip retargeting: No
  * Gun shooting sequence: 1
  * Impact delay: 0s
  * Can shoot over walls: No
  * Reload time: 500ms
  * Retargeting offset: 14
  * Self-centered targeting: No
  * Shot count: 1
  * Shot delay: 500ms
  * Target locking: No

|Level          |10  |9   |8   |7   |6   |5   |4   |3   |2   |1   |
|---------------|----|----|----|----|----|----|----|----|----|----|
|Damage per shot|2195|2120|2075|2050|2025|2005|1980|1955|1930|1910|


### Projectile

|Level                       |10  |9   |8   |7   |6   |5   |4   |3   |2   |1   |
|----------------------------|----|----|----|----|----|----|----|----|----|----|
|Displayed damage per second |2195|2120|2075|2050|2025|2005|1980|1955|1930|1910|
|Calculated damage per second|1567|1514|1482|1464|1446|1432|1414|1396|1378|1364|
|Calculated damage per cycle |2195|2120|2075|2050|2025|2005|1980|1955|1930|1910|


  * Cannons per sequence: 1
  * Shooting cycle duration: 1.400s
  * Directional: No
  * Is deflectable: No
  * Max speed: 18
  * Damage multipliers: **(300)**: Flying infantry, Infantry, Infantry hero, Support troop, **(250)**: Heavy infantry, Heavy infantry hero, **(200)**: Flying vehicle, Light vehicle, Vehicule hero, **(150)**: Heavy vehicle, Heavy vehicule hero, **(100)**: Droideka, Headquarters, Other building, Shield, Shield generator, Turret, Wall, **(50)**: Ressource generator, Storage, **(0)**: Trap
  * Pass through shield: No
  * Salvos: 1

## Internal stats

These stats internal to the system link different parts of data together.

  * Resilience details: defense
  * Spawn apply buffs: buffResilience1
  * Unit ID: FurCoat
  * Upgrade shard uid: shrd_troopFurCoat

## Presentation stats

These are all sorts of user interface settings, that should not interfere with gameplay.

  * Arcs: Yes
  * Asset name: furcoat_rbl-ani
  * Audio attack: "sfx_attack_furcoat_01":33,"sfx_attack_furcoat_02":33,"sfx_attack_furcoat_03":34
  * Audio death: "sfx_death_furcoat_01":33,"sfx_death_furcoat_02":33,"sfx_death_furcoat_03":34
  * Audio placement: "sfx_placement_furcoat_01":33,"sfx_placement_furcoat_02":33,"sfx_placement_furcoat_03":34
  * Audio train: "sfx_ui_unitcomplete_furcoat_01":100
  * Bundle name: furcoat_rbl-ani
  * Event button action: galaxy
  * Event button data: planet1 planet3 planet6 planet8 planet21 planet23
  * Event button string: hn_open_galaxy
  * Event features string: fragment_obtain_gen
  * Factory rotation: 0
  * Factory scale factor: 1
  * Favorite target type: infantry
  * Icon camera position: 7.96,8.84,21.58
  * Icon closeup camera position: -14.18,5,14.81
  * Icon closeup lookat position: 1.05,1.88,-0.63
  * Icon lookat position: -0.29,1.42,-0.89
  * Max scale: 100
  * Muzzle flash: fx_melee_headbutt_med
  * Name: Melee Vibro Mace
  * Spin speed: 2
  * Targeted type: ENEMIES
  * Unlocked by campaign: Yes
  * Unlocked by event: true
  * Unlocked by tournament: Yes

|Level                      |10  |9   |8   |7   |6   |5   |4   |3   |2   |1   |
|---------------------------|----|----|----|----|----|----|----|----|----|----|
|Displayed damage per second|2195|2120|2075|2050|2025|2005|1980|1955|1930|1910|


## Uninterpreted stats

Seriously, we don't really know what to do with these.

  * Arming delay: 0
  * Auto spawn rate scale: 1
  * Auto spawn spreading scale: 1
  * Max scale: No
  * Resilience tags: Resilience
  * Seeks target: Yes
  * Streams: no
  * Strict cool down: No
  * Target in range modifier: 1
  * Xp: 0

|Level      |10    |9     |8     |7     |6     |5     |4     |3     |2     |1     |
|-----------|------|------|------|------|------|------|------|------|------|------|
|Order      |235510|235509|235508|235507|235506|235505|235504|235503|235502|235501|
|Point value|3     |2.600 |2.400 |2.200 |2     |1.800 |1.600 |1.400 |1.200 |1     |


