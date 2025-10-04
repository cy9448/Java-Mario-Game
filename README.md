# 🕹️ Shadow Donkey Kong

A 2D platformer game written in Java using the **Bagel** game engine (built on LWJGL).  
Developed as part of the *Object-Oriented Programming* coursework at Monash University.

---

## 🎯 Overview

**Shadow Donkey Kong** is a modern reinterpretation of the classic Donkey Kong arcade game.  
Players control a character navigating through levels filled with obstacles, moving platforms, and enemies, aiming to reach the goal without losing all lives.

---

## 🚀 Features

- **Smooth 2D Movement:** Jumping, falling, and collision handling using Bagel’s physics framework.  
- **Multiple Levels:** Distinct stages defined by configuration files in the `res/` folder.  
- **Dynamic Entities:** Includes barrels, platforms, hazards, and collectible bananas.  
- **Game States:** Start screen, win/lose conditions, and level transitions.  
- **Resource Loading:** Utilizes `.properties` and image files for sprites and UI elements.  
- **Object-Oriented Design:** Uses inheritance and polymorphism for clean, modular code.

---

##  🎮 Controls
Key	Action
← / →	Move left / right
↑ or Space	Jump
Esc	Quit game

## 📚 Learning Outcomes
This project demonstrates:
- Mastery of object-oriented principles (inheritance, encapsulation, polymorphism)
- Game loop architecture and event-driven programming
- Collision detection and resource management
- Code readability and maintainability using modular design

## ⚙️ How to Build and Run
### Using Maven (recommended)
```
mvn clean package
mvn -q exec:java -Dexec.mainClass=ShadowDonkeyKong
```

## 👤 Author
Chen Yu Lin |
University of Melbourne |
https://github.com/cy9448
