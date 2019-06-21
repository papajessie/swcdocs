---
title: Shock Trooper (Shock)
category: unit
---

# Shock Trooper (Shock)

You can read an [explanation  of the various unit stats](unitexplained.md).

## Main stats

### Unit stats

  * Armor type: bruiserInfantry
  * Side: Empire
  * Buildable unit: Yes
  * Role: Breacher
  * Shield cooldown: 0s
  * Shield health: 0
  * Shield range: 0
  * Unit capacity: 3
  * Type: infantry
  * Unlock planet: Unlock on Tatooine

|Level |10  |9   |8   |7   |6   |5   |4   |3   |2   |1   |
|------|----|----|----|----|----|----|----|----|----|----|
|Health|9610|9070|8560|8080|7630|7210|6810|6440|6090|5760|


### Training stats

|Level        |10                                      |9                                      |8                                      |7                                      |6                                      |5                                      |4                                      |3                                      |2                                      |1                                |
|-------------|----------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------------|---------------------------------|
|Training time|2m                                      |1m56s                                  |1m52s                                  |54s                                    |52s                                    |50s                                    |48s                                    |46s                                    |44s                                    |42s                              |
|Training cost|920$                                    |840$                                   |800$                                   |680$                                   |600$                                   |520$                                   |440$                                   |360$                                   |280$                                   |200$                             |
|Building     |[Research Lab 10](empireOffenseLab.html)|[Research Lab 9](empireOffenseLab.html)|[Research Lab 8](empireOffenseLab.html)|[Research Lab 7](empireOffenseLab.html)|[Research Lab 6](empireOffenseLab.html)|[Research Lab 5](empireOffenseLab.html)|[Research Lab 4](empireOffenseLab.html)|[Research Lab 3](empireOffenseLab.html)|[Research Lab 2](empireOffenseLab.html)|[Barracks 1](empireBarracks.html)|


### Upgrading stats

  * Upgrade time: 5s
  * Upgrade requirements: 32 data fragments

### Movement stats

  * Acceleration: 0
  * Crushes walls: No
  * Flying unit: No
  * Max speed: 20
  * Rotation speed: 7.854
  * Run speed: 0
  * Run threshold: 0
  * Unit size on map: 1x1

|Level                            |2-10|1 |
|---------------------------------|----|--|
|Propensity to go around obstacles|200 |15|


## Main attack : Shock Rocket

### Targeting

  * Attack shield border: No
  * Max attack range: 9
  * Min attack range: 0
  * New rotation speed: 7854
  * Target preference strength: 90
  * Target preferences: **Trap (90)**, Droideka (50), Flying infantry (50), Flying vehicle (50), Headquarters (50), Heavy infantry (50), Heavy vehicle (50), Infantry (50), Light vehicle (50), Other building (50), Ressource generator (50), Shield (50), Shield generator (50), Storage (50), Support troop (50), Turret (50), Heavy infantry hero (1), Heavy vehicule hero (1), Infantry hero (1), Vehicule hero (1), Wall (1)
  * View range: 21

### Shooting

  * Animation delay: 0s
  * Charge time: 500ms
  * Clip retargeting: No
  * Gun shooting sequence: 1
  * Impact delay: 1s
  * Can shoot over walls: No
  * Reload time: 3s
  * Retargeting offset: 18
  * Self-centered targeting: No
  * Shot count: 1
  * Shot delay: 250ms
  * Target locking: No

|Level          |10  |9   |8   |7   |6   |5   |4   |3   |2   |1   |
|---------------|----|----|----|----|----|----|----|----|----|----|
|Damage per shot|4470|4152|3852|3580|3332|3100|2892|2692|2512|2340|


### Projectile

  * Splash damage percentages: 100,50,10,5

|Level                       |10  |9   |8   |7   |6   |5   |4   |3   |2   |1   |
|----------------------------|----|----|----|----|----|----|----|----|----|----|
|Displayed damage per second |4470|4152|3852|3580|3332|3100|2892|2692|2512|2340|
|Calculated damage per second|1277|1186|1100|1022|952 |885 |826 |769 |717 |668 |
|Calculated damage per cycle |4470|4152|3852|3580|3332|3100|2892|2692|2512|2340|


  * Cannons per sequence: 1
  * Shooting cycle duration: 3.500s
  * Directional: Yes
  * Is deflectable: No
  * Max speed: 18
  * Damage multipliers: **(700)**: Wall, **(500)**: Trap, **(200)**: Headquarters, **(100)**: Droideka, Flying vehicle, Light vehicle, Vehicule hero, **(75)**: Heavy vehicle, Heavy vehicule hero, Other building, Ressource generator, Shield, Shield generator, Storage, Turret, **(50)**: Flying infantry, Infantry, Infantry hero, Support troop, **(25)**: Heavy infantry, Heavy infantry hero
  * Pass through shield: Yes
  * Salvos: 1

## Internal stats

These stats internal to the system link different parts of data together.

  * Unit ID: Shock
  * Upgrade shard uid: shrd_troopShock

## Presentation stats

These are all sorts of user interface settings, that should not interfere with gameplay.

  * Arcs: No
  * Asset name: shotrper_emp-ani
  * Audio attack: "sfx_attack_rocket_1":20,"sfx_attack_rocket_2":20,"sfx_attack_rocket_3":20,"sfx_attack_rocket_4":20,"sfx_attack_rocket_5":20
  * Audio death: "sfx_death_troop_1":10,"sfx_death_troop_2":10,"sfx_death_troop_3":10,"sfx_death_troop_4":10,"sfx_death_troop_5":10,"sfx_death_troop_6":10,"sfx_death_troop_7":10,"sfx_death_troop_8":30
  * Audio impact: "sfx_impact_rocket_01":35,"sfx_impact_rocket_02":35,"sfx_impact_rocket_03":30
  * Audio placement: "sfx_placement_troop_1":35,"sfx_placement_troop_2":35,"sfx_placement_troop_3":30
  * Audio train: "sfx_ui_unitcomplete_stormtrooper_01":35,"sfx_ui_unitcomplete_stormtrooper_02":35,"sfx_ui_unitcomplete_stormtrooper_03":30
  * Bullet: fx_rocket_projectile_r_sm
  * Bundle name: shotrper_emp-ani
  * Death animation: buffFireBurn:15
  * Event button action: planet
  * Event button data: planet1
  * Event button string: hn_open_tat
  * Event features string: fragment_obtain_gen
  * Factory rotation: 0
  * Factory scale factor: 1
  * Favorite target type: trap
  * Gun position: "pathfndr_rbl_rig_MASTER_MOVER/pathfndr_rbl_rig_locator_gun_Rt":1
  * Hit spark: fx_shocktrooper_vanguard_hit
  * Icon camera position: 12.08,15.01,15.66
  * Icon closeup camera position: 0.64,0.41,9.27
  * Icon closeup lookat position: 0.07,2.85,0.16
  * Icon lookat position: -0.06,1.53,-0.1
  * Max scale: 100
  * Muzzle flash: fx_rocket_muzzle_r_sm
  * Name: Shock Rocket
  * Spin speed: 0
  * Targeted type: ENEMIES
  * Unlocked by event: true

|Level                      |10         |9          |8          |7          |6          |5          |4          |3          |2          |1    |
|---------------------------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----------|-----|
|Displayed damage per second|4470       |4152       |3852       |3580       |3332       |3100       |2892       |2692       |2512       |2340 |
|Icon unlock position       |(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|0,0,0|
|Icon unlock rotation       |(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|0,0,0|
|Icon unlock scale          |(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|(not found)|1,1,1|


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

|Level      |10    |9     |8     |7     |6     |5     |4     |3     |2     |1     |
|-----------|------|------|------|------|------|------|------|------|------|------|
|Order      |121310|121309|121308|121307|121306|121305|121304|121303|121302|121301|
|Point value|9     |7.800 |7.200 |6.600 |6     |5.400 |4.800 |4.200 |3.600 |3     |


