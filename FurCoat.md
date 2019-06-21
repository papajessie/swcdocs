---
title: Fur Coat (FurCoat)
category: unit
---

# Fur Coat (FurCoat)

You can read an [explanation  of the various unit stats](unitexplained.md).

## Main stats

### Unit stats

  * Armor type: infantry
  * Side: Rebellion
  * Buildable unit: No
  * Can be given: Yes
  * Role: Generic
  * Unit capacity: 4
  * Type: infantry

|Level |10   |9    |8    |7    |6    |5    |4    |3    |2    |1   |
|------|-----|-----|-----|-----|-----|-----|-----|-----|-----|----|
|Health|16320|15560|14800|14050|13290|12540|11780|11030|10270|9520|


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


## Main attack : Storm

### Targeting

  * Attack shield border: No
  * Max attack range: 2
  * Min attack range: 0
  * New rotation speed: 7854
  * Target preference strength: 90
  * Target preferences: **Droideka (50)**, **Flying infantry (50)**, **Flying vehicle (50)**, **Headquarters (50)**, **Heavy infantry (50)**, **Heavy vehicle (50)**, **Infantry (50)**, **Light vehicle (50)**, **Other building (50)**, **Ressource generator (50)**, **Shield (50)**, **Shield generator (50)**, **Storage (50)**, **Support troop (50)**, **Turret (50)**, Heavy infantry hero (1), Heavy vehicule hero (1), Infantry hero (1), Vehicule hero (1), Wall (1), Trap (0)
  * View range: 12

### Shooting

  * Animation delay: 0s
  * Charge time: 400ms
  * Clip retargeting: No
  * Gun shooting sequence: 1
  * Impact delay: 0s
  * Can shoot over walls: No
  * Reload time: 500ms
  * Retargeting offset: 14
  * Self-centered targeting: No
  * Shot count: 1
  * Shot delay: 0s
  * Target locking: No

|Level          |10 |9  |8  |7  |6  |5  |4  |3  |2  |1  |
|---------------|---|---|---|---|---|---|---|---|---|---|
|Damage per shot|445|425|405|385|365|340|320|300|280|260|


### Projectile

|Level                       |10 |9  |8  |7  |6  |5  |4  |3  |2  |1  |
|----------------------------|---|---|---|---|---|---|---|---|---|---|
|Displayed damage per second |835|724|668|612|557|501|445|390|362|302|
|Calculated damage per second|494|472|450|427|405|377|355|333|311|288|
|Calculated damage per cycle |445|425|405|385|365|340|320|300|280|260|


  * Cannons per sequence: 1
  * Shooting cycle duration: 900ms
  * Directional: Yes
  * Is deflectable: Yes
  * Max speed: 15
  * Damage multipliers: **(100)**: Droideka, Flying infantry, Flying vehicle, Headquarters, Heavy infantry, Heavy infantry hero, Heavy vehicle, Heavy vehicule hero, Infantry, Infantry hero, Light vehicle, Other building, Ressource generator, Shield, Shield generator, Storage, Support troop, Trap, Turret, Vehicule hero, Wall
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

  * Arcs: No
  * Asset name: stotrper_emp-ani
  * Bullet: fx_blaster_beam_r_sm
  * Bundle name: stotrper_emp-ani
  * Event button action: galaxy
  * Event button data: planet1 planet3 planet6 planet8 planet21 planet23
  * Event button string: hn_open_galaxy
  * Event features string: fragment_obtain_gen
  * Factory rotation: 0
  * Factory scale factor: 1
  * Favorite target type: infantry
  * Hit spark: fx_blaster_hit_r_sm
  * Icon camera position: 12.13,10.63,15.32
  * Icon closeup camera position: 1.93,1.69,9.65
  * Icon closeup lookat position: -0.01,2.73,-0.82
  * Icon lookat position: 0.02,1.69,0
  * Max scale: 100
  * Muzzle flash: fx_blaster_flash_r_sm
  * Name: Storm
  * Spin speed: 0
  * Targeted type: ENEMIES
  * Unlocked by campaign: Yes
  * Unlocked by event: true
  * Unlocked by tournament: Yes

|Level                      |10 |9  |8  |7  |6  |5  |4  |3  |2  |1  |
|---------------------------|---|---|---|---|---|---|---|---|---|---|
|Displayed damage per second|835|724|668|612|557|501|445|390|362|302|


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


