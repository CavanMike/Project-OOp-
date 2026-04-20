## Project: Endless Monster Loop
**Start Date:** 4-20-2026 | **Team:** Cavan, R.M.; Cabuenas, A.J.; Alqueza, J.C.


### Game Overview
**Endless Monster Loop** is a turn-based survival RPG where players navigate an infinite cycle of combat. The loop continues until the player's HP reaches zero. To survive, players must strategically manage resources at **Shops** and **Camps** between waves of enemies and challenging **Bosses** every 5 rounds.

### OOP Architecture
* **Encapsulation:** Protects internal data (HP, stats) within classes for a secure, bug-free structure.
* **Abstraction:** Establishes a common template for all game entities, ensuring consistent behavior.
* **Inheritance:** Uses a base `Entity` class to efficiently extend properties to `Player`, `Enemy`, and `Boss`.
* **Polymorphism:** Enables a single system to handle diverse enemy types with unique AI and skills.

### System Flow
 **Combat:** Turn-based battles against scaling monsters.
 **Milestones:** A Boss encounter every 5th round.
 **Support:** Access to Shops (upgrades) and Camps (recovery) to extend the run.
 **Termination:** The game concludes only when the player's HP hits 0.

