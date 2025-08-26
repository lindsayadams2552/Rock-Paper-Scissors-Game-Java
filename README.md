# Rock-Paper-Scissors Game (Java Swing)

A simple Rock-Paper-Scissors game built in Java Swing with a graphical user interface (GUI).  
Users play against the computer by clicking Rock, Paper, or Scissors buttons. The computer makes a random choice, and the winner is displayed.  

This project was developed in **Apache NetBeans** using its **drag-and-drop GUI Builder (Matisse)**.  
- NetBeans automatically generated the GUI layout files (`.form`, `nbproject`, `build.xml`, etc.).  
- I wrote the main game logic and event-handling code inside **`NewJFrame.java`**.

---

## Game Rules
- Rock crushes scissors
- Scissors cuts paper
- Paper covers rock
- Same move from each opponent is a tie
```
Examples:
- User clicks Rock → Computer chooses Scissors → “Rock crushes scissors, User wins!”
- User clicks Paper → Computer chooses Rock → “Paper covers rock, User wins!”
- User clicks Scissors → Computer chooses Scissors → “It’s a tie!”
```

---

## Project Description
This project recreates the classic Rock-Paper-Scissors hand game as a desktop GUI application.  
- The user selects Rock, Paper, or Scissors by clicking buttons with images.  
- The computer randomly chooses one of the three options.  
- The result (Win, Lose, or Draw) is displayed in a label, with colors:  
  - 🟩 Green → Win  
  - 🟥 Red → Lose  
  - ⬛ Black → Tie  
- A **RESET** button restarts the game (showing the welcome instructions again).  
- An **EXIT** button closes the application.  

---

## Skills Utilized / Learned
This project demonstrates key Java concepts:
- **Java Programming** → classes, methods, conditionals, event-driven logic  
- **GUI Development with Swing** → JFrame, JLabel, JButton, JScrollPane  
- **Event Handling** → `ActionListener` for button clicks  
- **Random Number Generation** → used to simulate the computer’s choice  
- **Logic & Decision Making** → rules of Rock-Paper-Scissors implemented  
- **User Interface Design** → aligning labels, images, and buttons for a clean layout  

---

## Code Overview
Key parts of the program:
- **randz()** → generates the computer’s random choice
- **gameResult(user, com)** → compares player vs. computer choice and returns result
- **rockActionPerformed, paperActionPerformed, scissorsActionPerformed** → event handlers for buttons
- **resetActionPerformed** → clears labels and shows welcome menu again
- **exitActionPerformed** → closes the application

---
## Demo Video
You can watch the demo video here:  
[Watch Demo](./Video/video1849913667.mp4)

---

## Project Structure
```
RockPaperScissors/
├── JavaApplication/
│ ├── nbproject/ # NetBeans project configuration files
│ │ ├── build-impl.xml
│ │ ├── genfiles.properties
│ │ ├── project.properties
│ │ ├── project.xml
│ ├── src/ # Source Code and Supporting Files
│ │ ├── NewJFrame.form # NetBeans GUI form (layout definition)
│ │ ├── NewJFrame.java # Main Java Swing GUI + game logic
│ │ ├── paperImg.jpg # Paper button image
│ │ ├── rockImg.jpg # Rock button image
│ │ ├── scissorsImg.jpg # Scissors button image
│ ├── build.xml # Apache NetBeans Ant build script
│ ├── manifest.mf # Manifest file for JAR packaging
├── Video/ # Video demonstration
│ ├── audio1849913667.m4a
│ ├── recording.conf
│ ├── video1849913667.mp4
├── README.md # Documentation (this file)
```
---

## Project Info
- **Author:** Lindsay Adams
- **Date:** 08/04/2023
- **Course:** Java Programming (Professor Ruiz)
- **IDE:** Apache NetBeans
