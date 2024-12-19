# 🧪 SwarmShot - Top-Down Zombie Horde Survival Game 🧟‍♂️

## 📖 Story: The Setting - A World in Chaos

The year is **2084**. Humanity’s insatiable curiosity led to the creation of _Project Genesis_ , a genetic experiment aimed at **eradicating all diseases**. Scientists engineered a virus that could rewrite DNA to repair any cellular damage. However, something went wrong. The virus _mutated_ uncontrollably, turning most humans into mindless, bloodthirsty **zombies**. Worse, it spread to nearly all life forms, devastating ecosystems and leaving the world on the brink of extinction.

Amidst the chaos, a few species inexplicably developed natural immunity. These animals not only resisted the virus but seemed to carry a **genetic marker** that might hold the key to reversing the apocalypse.

You are **Dr. Arin Locke**, a robotics engineer and survivalist. Once a part of the Genesis project, you now bear the weight of humanity's survival. Armed with your wits, cutting-edge technology, and an experimental combat suit, you embark on a mission to save the immune species and unlock the cure hidden in their DNA. Armed with technology and a combat suit, **you must protect, survive, and rebuild** humanity.

## 🎮 Gameplay Overview

### Base Version:

- **Map:** 50x50 tiles, each 16x16 pixels
- **Current Mechanics:**
  - The scientist (player) moves around the map
  - Player sprite is animated using a spritesheet

### Final Version:

- **Top-down zombie horde survival game** with:
  - Player mechanics
  - Pets and weapons
  - Shop system
  - Defensive buildings
  - Zombie wave attacks (20 waves)
  - Optimized spritesheet rendering for all elements

Refer to `1Gameplay.txt` for a full breakdown of mechanics.

## 🗂️ Folder Structure

```
SwarmShot/
│
├── main.py            # Game loop, UI, wave system, window creation
├── player.py          # Player class (movement, health, weapons)
├── enemy.py           # Enemy base class and enemy types
├── pet.py             # Pet base class and properties
├── weapon.py          # Weapon base class and bullet behavior
├── building.py        # Building class (defense structures)
├── shop.py            # Shop system logic
│
├── Example_of_Game/
│   ├── Initial_Issues.txt # Info about beginner issues
│   ├── Explaination.txt   # Spritesheet parsing explanation
│   ├── practice.py        # Practice file for contributors
│   └── example.py         # Demonstrates game mechanics integration
│
├── 1Gameplay.txt      # Detailed gameplay documentation
│
├── Sounds/            # Game music and audio files
│
├── Sprites/
│   ├── Sprites_Building/     # Building sprites
│   ├── Sprites_Enemy/        # Enemy sprites
│   ├── Sprites_Environment/  # Environment tiles
│   ├── Sprites_Pet/          # Pet sprites
│   ├── Sprites_Player/       # Player sprites
│   └── Sprites_Weapon/       # Weapon sprites
│
├── .gitignore         # Ignores unnecessary files
└── README.md          # This file!
```

## 🚀 Installation Guide

1. **Install Python (3.12.4)**:

   - Download Python from the [official site](https://www.python.org/downloads/)
   - Ensure Python is added to your system path

2. **Install Pygame(pygame 2.6.1 (SDL 2.28.4, Python 3.12.4))**:

   ```bash
   pip install pygame
   ```

3. **Clone the Repository**:

   ```bash
   git clone https://github.com/SauravGitte/SwarmShot.git
   cd SwarmShot
   ```

4. **Run the Game**:

   ```bash
   python main.py
   ```

5. **Test Mechanics**:

   - Run `example.py` to get glimpse of Final version of game.

   ```bash
   cd Example_of_Game
   python example.py
   ```

### 👨‍💻 Contribution Guidelines:

1. **Fork the Repository**:

   - Visit [SwarmShot Repository](https://github.com/SauravGitte/SwarmShot.git)
   - Click **Fork**

2. **Clone Your Fork**:

   ```bash
   git clone https://github.com/<Your_Username>/SwarmShot.git
   cd SwarmShot
   ```

3. **Create a Branch**:

   ```bash
   git checkout -b add_music_loop
   ```

4. **Make Changes**:

   - Follow the folder structure
   - Use relative paths (e.g., `Sprites/Sprites_Player/Char_003.png`)

5. **Test Changes**:

   - Run the game locally

6. **Commit and Push**:

   ```bash
   git add .
   git commit -m "Added looping background music to main game loop"
   git push origin add_music_loop
   ```

7. **Create a Pull Request**:
   - Go to the original repository
   - Click **Pull Requests** → **New Pull Request**
   - Submit with a clear description

## 🕹️ Gameplay Mechanics at Glance

### Map:

- 50x50 grid, each tile 16x16 pixels
- Map boundary restricts player movement

### Player:

- Starts at the center
- Moves in 8 directions
- Can hold up to 6 weapons and 2 pets

### Wave System:

- 20 waves of zombies with increasing difficulty
- Enemies spawn randomly but avoid buildings

### Weapons:

- Auto-aim at nearest enemy
- Bullets disappear after hitting an enemy or crossing a set distance

### Pets:

- Follow the player dynamically
- Provide offensive or supportive abilities

### Buildings:

- Place defensive structures like cannons and Mortars
- Cannot overlap or spawn enemies

### Enemies:

- Various types: Basic, Tank, Ranged, and Bosses
- Damage the player on collision

## 🎵 Audio and Optimization

- Use spritesheets for all animations
- Add music and sound effects to the **Sounds/** folder
- Ensure all paths are relative

## 🔧 Technologies

- Python 3.12.4
- Pygame (latest version)(pygame 2.6.1 )

## 🤝 Contributors

Thank you to everyone contributing to **SwarmShot**! 🎉

Check the **Example_of_Game** folder for a simple codebase breakdown.

## 📜 License

Open-source under the **MIT License**.

---

_Happy coding, and let's save the world one wave at a time! 🌍👨‍🔬_
