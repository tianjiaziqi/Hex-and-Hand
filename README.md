# Hex & Hand

*A roguelike strategy game that blends dice-building, card-building, and tactical board movement.*

---

## Core Concept

This project aims to create a turn-based combat experience with deep strategic depth. Players must not only build their own **card deck** but also construct a unique **dice pool**. Each turn, players roll dice to obtain random resources, then use these resources (dice) to pay card costs while executing tactical movements, attacks, and defenses on a grid-based battlefield.


The core appeal of the game lies in managing the balance between “construction” (deck and dice pool) and “luck” (card draws and dice rolls each turn), while making optimal tactical decisions on the turn-based battlefield.


## Minimum Viable Product Goals

This list defines the minimum feature set required for the project's first playable prototype, intended to validate the feasibility and fun factor of the core gameplay.


* **[ ] Grid System**
    * [ ] Create a 5x5 battlefield grid.
    * [ ] Convert between grid coordinates and world coordinates.

* **[ ] Unit System**
    * [ ] Create a base unit containing health points (HP) and position attributes.
    * [ ] Generate player and enemy units on the battlefield.

* **[ ] Dice System**
    * [ ] Implement the functionality to roll two six-sided dice each turn.
    * [ ] Display the dice roll result for the current round on the UI.

* **[ ] Card System**
    * [ ] Create three basic cards (Move, Attack, Defense) using ScriptableObjects.
    * [ ] Implement the logic to pay card costs based on dice rolls.

* **[ ] Game Manager**
    * [ ] Establish the basic turn-based flow (Player Turn -> Enemy Turn).
    * [ ] Implement basic enemy AI (move toward the player and attack).
    * [ ] Implement basic victory/defeat determination (when one side's HP reaches zero).

* **[ ] Input & Interaction**
    * [ ] Allow players to select cards, dice, and targets by clicking.
    * [ ] Provide basic visual feedback to indicate the current selection.

## Tech Stack

* **Engine:** Unity 6000.2.8f1
* **Language:** C#
* **Version Control:** Git
* **Large File Management:** Git LFS

---
