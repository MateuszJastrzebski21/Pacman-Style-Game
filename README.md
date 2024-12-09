# Pacman-Style Game

## **Overview**
This project is a Pacman-style game developed as part of a GUI programming course. The game implements advanced features such as upgrades, animations, high scores, and a responsive graphical interface. The game follows the **Model-View-Controller (MVC)** design pattern and includes event-driven programming.

## **Key Features**
- **Dynamic Gameplay**:
  - Enemies have a 25% chance to drop upgrades every 5 seconds.
  - Players can collect upgrades to gain advantages such as increased movement speed, invincibility, or score multipliers.
  - Includes 5 significant and complex upgrades.
- **Fully Functional GUI**:
  - Main menu with options: "New Game", "High Scores", and "Exit".
  - Customizable game board size (10x10 to 100x100) using **JTable** and a custom `AbstractTableModel`.
  - Game interface includes a score counter, time tracker, and life counter, all updated in real-time.
- **High Scores System**:
  - Uses the **Serializable** interface for data persistence, saving high scores locally.
  - Displays high scores using a scrollable **JList** component.
- **Animations and Graphics**:
  - Smooth animations for character movements and food consumption.
  - Custom graphics for characters and game elements.
- **Multithreading**:
  - Implements **Thread** for animations, enemy movement, and game logic.
  - Ensures proper synchronization of threads for seamless gameplay.
- **Interruptible Gameplay**:
  - Players can return to the main menu at any time using the keyboard shortcut `Ctrl+Shift+Q`.

## **Technologies Used**
- **Programming Language**: Java
- **Core Concepts**: Multithreading, Serialization, Event Handling, MVC Design Pattern
- **GUI Components**: JTable, JList, JFrame, and custom dialogs
- **Graphics**: Custom graphical assets for game elements
