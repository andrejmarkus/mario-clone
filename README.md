# 🕹️ MarioClone

A 2D platformer recreation of the classic Super Mario Bros, built using **Java** and the **LibGDX** framework. This project features physics-based movement, enemy AI, power-ups, and level parsing from Tiled maps.

---

### 🎓 Academic Context

This is my **first university project** for the **Informatics 1** course. As such, the codebase reflects my initial learning journey with Java and game development patterns. While the code might not be perfectly "pretty" or follow all industry best practices yet, it represents a significant milestone in my programming education.

---

## 🚀 Features

- **Physics-Driven Gameplay**: Utilizing Box2D for realistic collisions and movement.
- **Classic Mechanics**: Jump, stomp enemies, and collect power-ups (Mushrooms, Flowers).
- **Dynamic Levels**: Levels are parsed directly from `.tmx` files created in Tiled Map Editor.
- **Entities & AI**: Includes Goombas with basic patrol AI and projectile systems (Fireballs).
- **HUD System**: Real-time tracking of score, coins, time, and world progress.
- **Animations**: State-based animation system for player and NPC actions.

## 🛠️ Tech Stack

- **Language**: [Java](https://www.oracle.com/java/)
- **Framework**: [LibGDX](https://libgdx.com/) (Cross-platform game development)
- **Physics**: [Box2D](https://box2d.org/)
- **Map Editor**: [Tiled](https://www.mapeditor.org/)
- **Build Tool**: [Gradle](https://gradle.org/)

---

## 🎮 How to Play

### Controls

| Key       | Action                                 |
| :-------- | :------------------------------------- |
| **W**     | Jump                                   |
| **A**     | Move Left                              |
| **D**     | Move Right                             |
| **SPACE** | Shoot (when Flower power-up is active) |

### Installation & Running

Ensure you have **Java JDK** installed on your system.

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/MarioClone.git
   ```
2. Navigate to the project directory:
   ```bash
   cd MarioClone
   ```
3. Run the desktop version using Gradle:
   ```bash
   ./gradlew desktop:run
   ```

---

## 📁 Project Structure

- `core/`: Main game logic, entities, and screens.
- `desktop/`: Desktop-specific launcher (LWJGL3).
- `assets/`: Game assets including sprites, maps, and fonts.

---

## 📜 Credits

Developed as part of the **Informatics 1** university course.
Special thanks to various LibGDX communities and tutorials for providing the foundation to build this project.

_Note: This project is for educational purposes only._
