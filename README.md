# Software-dev-2-assignment-2d platformer game-
## Table of Contents

- [Project Overview](#1-project-overview)
- [Project im and Objectives ](#2-project-aim-and-objectives)
- [Game Concept](#3-game-concept)
- [Target Audience](#4-target-audience)
- [User Profiles](#5-user-profiles)
- [User Requirements](#6-user-requirements)
- [System Requirements](#7-system-requirements)
- [Game Rules & Mechanics](#8-game-rules--mechanics)
- [Game Design](#9-game-design)
- [Technology Used](#10-technology-used)
- [Development Strategy](#11-development-strategy)
- [Scrum Backlog](#12-scrum-backlog)
- [Project Management](#13-project-management)
- [Testing](#14-testing)
- [Challenges & Solutions](#15-challenges--solutions)
- [Evaluation](#16-evaluation)
- [References](#17-references)

## 1. Project Overview

Platform Quest is a 2D side-scrolling platform game developed using Godot and GDScript for the Software Development 2 module.

The game challenges the player to navigate through a level by jumping across platforms, collecting relics, avoiding hazards and reaching the exit.

The project focuses on implementing core platformer mechanics while following a structured software development process.

## 2. Project Aim and Objectives

### 2.1 Aim

To develop a functional 2D platform game where the player can navigate obstacles, collect relics and successfully reach the end of the level.

### 2.2 Objectives

Design and develop a playable platform game.
Implement player movement and jumping mechanics.
Implement collectible items.
Implement hazards and fail conditions.
Create win and lose states.
Design a simple user interface.
Test the game against requirements.
Produce a playable prototype suitable for demonstration.

## 3. Game Concept

The game is a 2D side-scrolling platformer that draws inspiration from vintage video games. A character that the player controls must move left and right, jump across platforms, and stay upright in order to complete a level.

The goal of the game is to complete the level while avoiding obstacles. By requiring more accurate jumps and better timing, the level is meant to progressively test the player.

Instead of emphasizing intricate features, the game focuses on fundamental platformer mechanics. This includes responsive jumping, fluid motion, and accurate collision detection. To guarantee that the game is both practical and simple to comprehend, the overall design is kept straightforward.

## 4. Target Audience

### 4.1 Casual Gamers
Characteristics:

Prefer simple controls
Want enjoyable short play sessions
Expect quick understanding of the game

### 4.2 Nostalgic Platform Game Fans
Characteristics:

Familiar with platform games
Often enjoy nostalgic games inspired by older titles
Prefer addictive but easy-to-play experiences

### 4.3 Students/Young Adults Aged 18-25
Characteristics:

Notice movement quality and jump accuracy
Appreciate fair challenge and good level flow
Enjoy replayable platforming mechanics

## 5. Overall specification




## 6. User Requirements

- The player should be able to move left and right  
- The player should be able to jump  
- The player should be able to collect coins  
- The player should avoid enemies  
- The player should be able to restart after losing  

---

## 7. System Requirements

- The system must detect keyboard input  
- The system must implement gravity and jumping  
- The system must detect collisions  
- The system must update and display the score  
- The system must render the game in real time  
- The system must reset the game when the player loses  

---
## 8. Game Rules & Mechanics

The game is a side-scrolling platformer where the player moves from left to right.

- The player can move and jump  
- Platforms are used to navigate the level  
- Coins increase score when collected  
- Enemies must be avoided  
- Touching an enemy results in game over  
- The level is completed when the player reaches the end  

---

## 9. Game Design

### Player

The player is controlled by the user and can move left, right and jump.

### Environment

The level consists of platforms placed at different heights. The player must navigate across them to progress.

### Gameplay Loop

Move → Jump → Avoid falling → Reach end → Restart

---

## 10. Technology Used

**Game Engine:** Unity  
**Programming Language:** C#  

**Tools:**
- Unity Editor  
- Visual Studio  
- GitHub  

Unity was chosen because it provides built-in physics and tools for 2D game development, making it easier to implement core mechanics.

---
## 11. Development Strategy

The project follows an iterative development strategy based on Agile principles. This approach was chosen because it allows the game to be developed in small, manageable stages while continuously reviewing progress.Instead of attempting to build the entire game at once, the development was broken down into smaller features such as movement, jumping and collision detection. Each feature would be planned, implemented and then tested before moving on to the next stage. This reduces the risk of major errors and makes debugging easier.A Scrum-style workflow was used to organise tasks. Features were added to a backlog and prioritised based on importance. Core mechanics such as player movement and jumping were given the highest priority, while additional features like coins and enemies were considered lower priority and planned for later stages.This structured approach ensured that the most important parts of the game were focused on first. It also allowed flexibility, meaning changes could be made if issues were identified during development.Version control using GitHub was used to manage the project. This allowed progress to be tracked over time and ensured that different versions of the work could be saved and reviewed.

---

## 12. User scrum stories

| ID   | Priority | User Story                                                                                              | Purpose                                                     |
| ---- | -------- | ------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| US1  | High     | As a player, I want responsive movement controls so that I can explore the environment effectively.     | Allows the player to navigate the level smoothly.           |
| US2  | High     | As a player, I want to jump onto platforms so that I can access different parts of the level.           | Supports level traversal and progression.                   |
| US3  | High     | As a player, I want to collect relics so that I can work towards completing the objective.              | Encourages exploration and interaction with the game world. |
| US4  | High     | As a player, I want hazards to create consequences for mistakes so that the game feels challenging.     | Introduces risk and player decision-making.                 |
| US5  | High     | As a player, I want a clear level objective so that I know how to complete the game.                    | Gives the player a sense of direction and progression.      |
| US6  | Medium   | As a player, I want visual feedback when collecting relics so that I know my progress is being tracked. | Improves user experience and feedback.                      |
| US7  | Medium   | As a player, I want a main menu so that I can start or restart the game easily.                         | Improves usability and navigation.                          |
| US8  | Medium   | As a player, I want a game over screen so that I understand when I have failed.                         | Clearly communicates failure states.                        |
| US9  | Medium   | As a player, I want a win screen so that I receive confirmation of completing the level.                | Provides closure and achievement feedback.                  |
| US10 | Low      | As a player, I want additional levels so that the game offers more content in future versions.          | Supports future expansion of the project.                   |




---

## 13. Project Management

### Development Log

**Week 1**  
Set up project and planned features.

**Week 2**  
Created game window and player.

**Week 3**  
Implemented movement and jumping.

**Week 4**  
Worked on collisions and level design.

**Week 5**  
Added enemies and coins.

**Week 6**  
Testing and bug fixing.

---

### Development Meetings

### Development Meetings

**Meeting 1**  
Discussed overall game idea and core features. Decided to focus on a simple platformer with movement and jumping.

**Meeting 2**  
Reviewed progress and identified challenges with implementing physics and collision detection. Planned next steps for improving gameplay.

**Meeting 3**  
Evaluated overall project progress and focused on documentation, testing and final improvements.


---

## 14. Testing

| Test | Expected Result | Result |
|-----|-----|-----|
Move left/right | Player moves correctly | N/A|
Jump | Player jumps and lands | N/A |
Collect coin | Score increases | N/A |
Hit enemy | Game over triggered | N/A|
Reach end | Level completes | N/A |

---

## 15. Challenges & Solutions

One challenge was implementing collision detection between the player and platforms. This caused issues where the player would fall through objects.
Another problem was time along with. getting the jump mechanics to feel smooth, which required adjusting gravity and jump strength.

---

## 16. Evaluation

The project successfully demonstrates the core mechanics of a platform game including movement, jumping and collision detection.The main strength is that the game is functional and demonstrates key programming concepts.A limitation is that the game is quite simple and only includes one level. In the future, more levels and improved graphics could be added.

---



