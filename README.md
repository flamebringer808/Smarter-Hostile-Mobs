# Smarter Hostile Mobs (Forge 1.20.1)

A comprehensive AI overhaul for hostile entities in Minecraft Forge 1.20.1. Replaces rudimentary mob aggression with tactical awareness, threat assessment, hazard avoidance, and cooperative combat strategies.

---

## 🌟 Key Features

* **Tactical Awareness & Perception**: Mobs use multi-layered line-of-sight, hearing, and sound category detection to locate players and vulnerabilities.
* **Hazard Avoidance**: Entities navigate around fire, lava, cactus, powder snow, and dangerous drops instead of blindly charging forward.
* **Coordinated Breaching**:
  * **Creepers**: Breach defensive walls to clear pathways for other hostile mobs.
  * **Blazes**: Utilize flight awareness and ignite wooden obstacles to compromise player fortifications.
* **Skeleton Tactical Ranged Combat**: Skeletons maintain distance, strafe around obstacles, and switch tactics when cornered.
* **Extensible API**: Offers SmarterHostileMobsAPI and SmarterZombiesAPI allowing other mods to hook into mob perception states and awareness data.

---

## ⚙️ Configuration

Configuration is available at .minecraft/config/smarter-hostile-mobs-common.toml. Configure sensory ranges, tactical behaviors, and individual mob AI features.
