# DICEBOUND

A browser-based roguelike dice combat game built around building your character through dice, abilities, and risk-based combat decisions.

---

## 🎲 Core Idea

In DICEBOUND, you don’t use fixed abilities.

Instead, you assign abilities to dice (d4, d6, d8, etc), and each die determines how strong and how often that ability can be used.

Stronger dice = higher impact  
Smaller dice = more frequent rolls

---

## ⚔️ Core Gameplay Loop

1. Fight enemies in a wave
2. Defeat all enemies in the wave
3. Choose a reward (upgrade or ability)
4. Progress to the next wave
5. Complete waves to reach a dungeon boss
6. Defeat bosses to progress to the next dungeon

---

## 🎯 Objective

Survive as many waves and dungeons as possible by building a strong dice-based loadout.

There is no fixed “correct build” — experimentation is encouraged.

---

## 🎲 Dice System

Each ability is assigned to a die:

- d4 (fast, frequent, low power)
- d6 (balanced)
- d8 (slow, strong)
- d10 / d12 / d20 (late game, high impact)

Rolling a die triggers its assigned ability.

---

## 🔋 Energy System

Each die has an energy cost:

- d4 = low cost
- d6 = medium cost
- d8 = high cost

You gain energy each turn and can choose how to spend it.

Unused energy carries over between turns.

You may end your turn early.

---

## 💥 Critical Rolls

If a die rolls its maximum value:

- The energy cost is refunded
- The action is especially powerful (critical effect)

---

## ❤️ Player Stats

- HP (Health)
- Shield (temporary damage buffer, capped at Max HP)
- Energy (used to roll dice)

---

## 🧠 Abilities

Abilities are assigned to dice and can be upgraded.

### Damage Types

- **Physical**: Reduced by Shield
- **Piercing**: Partially ignores Shield
- **Poison**: Ignores Shield completely

---

## ☠️ Poison

- Applies damage immediately when used
- Continues dealing damage at the end of each turn
- Damage decreases each turn until it reaches 0
- Poison is removed if the target is healed
- Poison works the same for players and enemies

---

## 🛡 Shield

- Absorbs incoming damage before HP
- Has a maximum cap equal to Max HP

---

## 🧪 Healing

- Restores HP
- Removes all poison from the target

---

## 🔥 Enemy Design

Enemies have different roles:

- Rats / Goblins → basic attackers
- Orcs → heavy damage
- Naga Warriors → piercing (anti-shield)
- Shamans → healing + poison

Enemies may have multiple abilities as difficulty increases.

---

## 🧭 Progression

- Waves → small groups of enemies
- Waves give rewards
- Dungeons → multiple waves + boss
- Bosses introduce special mechanics
- Future systems: realms and artifacts

---

## 🧪 Current State

This is an early prototype.

Balance is actively changing and systems are still being tested.

Expect frequent updates and experimental mechanics.

---

## 💡 Design Philosophy

- Builds should be emergent, not predefined
- Every run should feel different
- Strong strategies are allowed, but must have counters
- Enemy variety is as important as player power

---

## 🚧 Known Limitations

- No tutorial system yet
- UI is minimal
- Balance is experimental
- Enemy variety is still expanding

---

## 🎮 Have Fun

This game is being built through experimentation — if something feels broken or overpowered, that’s part of the discovery process.