# 🧪 SwarmShot - Top-Down Zombie Horde Survival Game 🧟‍♂️

Welcome to **SwarmShot**, a beginner-friendly project to dive into game development with Python(using Py Game)!

## 📖 Story: The Setting - A World in Chaos

The year is **2084**. Humanity’s insatiable curiosity led to the creation of _Project Genesis_ , a genetic experiment aimed at **eradicating all diseases**. Scientists engineered a virus that could rewrite DNA to repair any cellular damage. However, something went wrong. The virus _mutated_ uncontrollably, turning most humans into mindless, bloodthirsty **zombies**. Worse, it spread to nearly all life forms, devastating ecosystems and leaving the world on the brink of extinction.

Amidst the chaos, a few species inexplicably developed natural immunity. These animals not only resisted the virus but seemed to carry a **genetic marker** that might hold the key to reversing the apocalypse.

You are **Dr. Arin Locke**, a robotics engineer and survivalist. Once a part of the Genesis project, you now bear the weight of humanity's survival. Armed with your wits, cutting-edge technology, and an experimental combat suit, you embark on a mission to save the immune species and unlock the cure hidden in their DNA. Armed with technology and a combat suit, **you must protect, survive, and rebuild** humanity.

## 📚 Table of Contents

- [Gameplay Overview](#-gameplay-overview)
- [Folder Structure](#️-folder-structure)
- [Setup and Installation](#-installation-guide)
- [Reference Links](#-reference-links)
- [Folder Structure](#️-folder-structure)
- [Contribution Guidelines](#-contribution-guidelines)
- [Communication](#-communication)
- [Mentor](#-mentor)
- [Contributors](#-contributors)

## 🎮 Gameplay Overview

### Base Version:

- Run the main.py file using VS code .
- **Map:** 44x44 tiles, each 16x16 pixels
- **Current Mechanics:**
  - The scientist (player) moves around the map
  - Player sprite is animated using a spritesheet

### Final Version:

-Run the example.py file( Inside Example_of_Game folder) .

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
├── 📁Example_of_Game/
│   ├── 📁Contributors          # Contains list of contributors
│   ├── 📁Practice_Animation    # Contains list of contributors
│   │   └── practice.py             # Practice file for contributors
│   └── example.py              # Demonstrates game mechanics integration
│
├──📄1Gameplay.txt      # Detailed gameplay documentation
│
├── 📁Sounds/            # Game music and audio files
│
├── 📁Sprites/
│   ├── 📁Sprites_Building/     # Building sprites
│   ├── 📁Sprites_Enemy/        # Enemy sprites
│   ├── 📁Sprites_Environment/  # Environment tiles
│   ├── 📁Sprites_Pet/          # Pet sprites
│   ├── 📁Sprites_Player/       # Player sprites
│   └── 📁Sprites_Weapon/       # Weapon sprites
│
├── .gitignore         # Ignores unnecessary files
└──📄README.md          # This file!
```

## 🚀 Installation Guide

1. **Install Python (3.12.4)**:

   - Download Python from the [official site](https://www.python.org/downloads/)
   - Ensure Python is added to your system path

2. **Install Pygame(pygame 2.6.1 (SDL 2.28.4, Python 3.12.4))**:

   ```bash
   pip install pygame
   ```

## ⚡ Running the Game

1.**Run current Game**
-Navigate to SwarmShot Folder and open it in any terminal
-Type "python main.py" command and press Enter.
-The game will start and you can play it

2. **Test Mechanics**:

   - Run `example.py` to get glimpse of Final version of game.
   - It is in Example_of_Game Folder

   ```bash
   cd Example_of_Game
   python example.py
   ```

## 🔗 Reference Links

- [SpriteSheet Parsing](https://youtu.be/mfX3XQv9lnI)
- [Learn to Contribute](https://dashing-sundae-cda.notion.site/Contributing-On-Github-162eee83a76a80c3bf6cfdc16bb833ed?pvs=4)
- [Py Game Documentation](https://www.pygame.org/docs/)
- [Py Game Tutorials](https://youtu.be/FfWpgLFMI7w)

### 👨‍💻 Contribution Guidelines:

- [Learn to Contribute](https://dashing-sundae-cda.notion.site/Contributing-On-Github-162eee83a76a80c3bf6cfdc16bb833ed?pvs=4)

1. **Claim the Issue**:
   -Go to the issue page of the repository where the issue is raised.
   -Add a comment like:"Claim"
   -Wait for the repository maintainers to assign the issue to you.

2. **Fork the Repository**:

   - Visit [SwarmShot Repository](https://github.com/opencodeiiita/SwarmShot)
   - Click **Fork**

3. **Clone Your Fork**:

   ```bash
   git clone https://github.com/<Your_Username>/SwarmShot.git
   cd SwarmShot
   ```

4. **Make Changes**:

   - Follow the folder structure
   - Edit the code or files as required to resolve the issue.
   - Use relative paths (e.g., `Sprites/Sprites_Player/Char_003.png`)

5. **Test Changes**:

   - Run the game locally

   ```bash
   python main.py
   ```

6. **Commit and Push**:

   ```bash
   git add .
   git commit -m "commit_message_as per issue"
   git push origin main
   ```

7. **Create a Pull Request**:

   - Go to your forked repository on GitHub.
   - Click **Pull Requests**,Fill out the PR form
   - Submit PR

8. **Engage in Review**:
   - Repository maintainers or reviewers may leave comments or request changes on your PR.
   - Make the requested changes directly in your forked repository's main branch.
   - Stage and commit the changes:
   ```bash
      git add .
      git commit -m "Updated changes as per review comments"
      git push origin main
   ```

## 💻 Communication

Stay connected on our **[Discord](https://discord.gg/SxBATvUPnC)** channel for updates and discussions with mentors and contributors or to ask any doubt needed. Make sure to use suitable channels according to your repo in the server.

## 🤝 Mentor

1. **Saurav Gitte**  
   _Game dev and avid gamer_  
   `GitHub:` [SauravGitte](https://github.com/SauravGitte)  
   `Discord:` gittesaheb
2. **Bhavya Gupta** _(aka Gamin8ing)_  
   _Game dev and an all-time gamer_  
   `GitHub:` [Gamin8ing](https://github.com/Gamin8ing)  
   `Discord:` gamin8ing (or blackHole)
3. **Srijan Suryansh**
   `Github:` [Lordlyamigo](https://github.com/LORDLYAMIGO/)
   `Discord:` Lordlyamiga

## 🤝 Contributors

Thank you to everyone contributing to **SwarmShot**! 🎉
Check the **Example_of_Game** folder for the list of contributors.

_Happy coding, and let's save the world one wave at a time! 🌍👨‍🔬_
