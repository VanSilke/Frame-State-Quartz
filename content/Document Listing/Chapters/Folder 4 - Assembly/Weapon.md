---
{"publish":true,"created":"2025-08-07T17:37:25.944+02:00","modified":"2025-08-07T18:41:47.030+02:00","cssclasses":""}
---

A weapon is a separately usable frame feature, which is usually governed by its own properties based on damage type and weapon type, which set the weapon's unique rules.

# Weapon Tiers
The strength of a weapon is measured in tiers. Higher weapon tiers are slower and more expensive, but generally hit harder. They also have more points to spend on the properties of the weapon in question.
- Each weapon property has its own attribute, which can be increased with property points from 0 upward.
- Weapon type and damage type describe what each of the two properties actually do with the weapon.

| Tier |     Use Cost      | Damage | Impact | Property Pts. |
| :--: | :---------------: | :----: | :----: | :-----------: |
|  I   |      1 step       |   d4   |   1    |       1       |
|  II  |      2 steps      |   d6   |   2    |       2       |
| III  | 2 steps; 1 energy |   d8   |   3    |       3       |

# Weapon Type
The weapon type describes the general use case of a weapon. Further, targeting tests tend to be different for each weapon type.

| Weapon Type | Description  |
| ----------- | ------------ |
| [[OLD/Weapon Folder Main/Weapon Type Folder/Gun]]     | **Targeting:** Sharpness + Aim Assist
**Base Range:** 3
**On Use:** Discharge
**Recoil:** On Discharge; base 1 plus rail
**Property:** Rail (value)
The rail value is added to targeting during discharge. The rail value causes additional recoil loss on discharge.     |
| [[OLD/Weapon Folder Main/Weapon Type Folder/Cannon]]  | **Targeting:** Sharpness + Lock Correction  
**Base Range:** 4 + Artillery  
**On Use:** Discharge  
**Recoil:** On Discharge; base 1  
**Property:** Artillery (value)  
The artillery value increases the base range before it is multiplied. The artillery value causes additional recoil loss on discharge.  
**Special:** Can be angled, overcoming obstacles on a vertical plane, shooting above buildings for example, but must remain a straight line horizontally.  |
| [[OLD/Weapon Folder Main/Weapon Type Folder/Melee]]   | **Targeting:** Sharpness + Servo Assist  
**Base Range:** Adjacent Hex Only  
**On Use:** Discharge  
**Recoil:** On Discharge; base 1  
**Property:** Force (value)  
The force value is added to the harm test on hit during discharge.  
**Special:** Range is not multiplied by the scanner value. Cannot be installed on the mounted slots.   |
| [[OLD/Weapon Folder Main/Weapon Type Folder/Missile]] | **Targeting:** Lock Correction + Homing + d8  
**Base Range:** 4  
**On Use:** Discharge  
**Recoil:** On Discharge; base 1  
**Property:** Homing (die)  
The homing die is added to targeting during discharge.  
**Special:** Add extra d8 to targeting during discharge. |
| [[OLD/Weapon Folder Main/Weapon Type Folder/Drone]]   | **Targeting:** d8  
**Base Range:** 2  
**On Use:** Activate  
**Recoil:** None  
**Property:** Lifetime (value)  
The lifetime value increases the number of rounds for which the weapon can remain active.  
**Special:** During your turn, you may designate a point of interest. The weapon then autonomously discharges on that designation once at no action cost during an ally turn, every round, while active. The drone is not affected by your own recoil.   |

# Damage Type
The damage type designates the type of defence a weapon is matched against, and adds a special property to it.

| Weapon Type            | Description             |
| ---------------------- | ----------------------- |
| [[OLD/Weapon Folder Main/Damage Type Folder/Kinetic Damage]]     | **Plating:** Anti-Kinetic Plating  
**Property:** Piercing (value)  
When you hit a designation with a kinetic weapon during discharge, you reduce the kinetic defence against that weapon by the piercing value, to the minimum of 0.     |
| [[OLD/Weapon Folder Main/Damage Type Folder/Energy Damage]]      | **Plating:** Anti-Energy Plating  
**Property:** Plasma (value)  
When you hit a designation with an energy weapon during discharge, and deal at least 1 point of unblocked damage, the designation takes damage equal to the listed plasma value at the beginning of its next turn. This damage recurs for one more turn and clears.  
**Special:** While the designation is suffering from plasma, subsequent hits with energy weapons with at least 1 plasma value add 1 to this recurring damage to the maximum of 5 and refresh the round count before plasma is extinguished.      |
| [[OLD/Weapon Folder Main/Damage Type Folder/Blast Damage]]       | **Plating:** Anti-Blast Plating  
**Property:** Radius (value)  
Whether you hit or miss the designation during weapon discharge, you generate an explosion in the designation's hex. An explosion has a range equal to the radius value. You harm all points of interest within the explosion range including yourself and the initial designation again. This counts as a separate instance.       |
| [[OLD/Weapon Folder Main/Damage Type Folder/Wave Damage]]        | **Plating:** Wave damage is compared against the lowest of all three plating types.  
**Property:** Resonance (value)  
When you hit a designation with a wave weapon during discharge, it resonates until the beginning of your next turn. All subsequent damage taken during this time is increased by the resonance value.  
**Special:** Wave weapons are rare, and need to be uncovered, reverse-engineered, or both, as part of downtime. They additionally require a wave generator on board.        |
| [[OLD/Weapon Folder Main/Damage Type Folder/Singularity Damage]] | **Plating:** None.  
**Property:** Stability (value)  
Add Stability value to damage.  
**Special:** Singularity weapons are extremely rare and borderline illegal. They additionally require a singularity generator on board. |
