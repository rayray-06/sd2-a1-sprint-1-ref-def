# Software-dev-2-assignment-2d platformer game-
## Table of Contents

- [Project Overview](#1-project-overview)
- [Project Breakdown ](#2-project-breakdown)
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

## 2. Project Breakdown

**Planning**  
In order to comprehend common mechanics like movement, jumping, and level progression, research into current 2D platformer games was done during the planning phase. This led to the decision to develop a straightforward platformer that prioritizes basic gameplay over sophisticated features.

The primary characteristics noted were:- The player's left and right movements
Gravity-driven jumping
Designing at the platform level
Basic detection of collisions

This phase assisted in defining the project's scope and guaranteed that it could be completed within the allotted time.

**Design**  
The game's structure was planned during the design stage. This included the layout of the level and how the player would engage with the surroundings.

Among the important design choices were:Using a side-scrolling design
Setting up platforms at varying heights to necessitate leaping
Maintaining responsive and straightforward controls
Creating a level with a distinct beginning and ending

**Development**  
The development stage involved building the game in Unity using C# scripts. Work was completed in stages to allow testing after each feature was added.

The order of implementation was:
1. Setting up the Unity project and scene  
2. Creating the player object  
3. Implementing movement controls  
4. Adding jumping using Unity physics  
5. Creating platforms with colliders  
6. Implementing collision detection  
7. Adding a camera that follows the player  
8. Designing the level layout  

This step-by-step approach made it easier to identify and fix issues early.

**Testing**  
Testing was carried out throughout development rather than only at the end. Each feature was tested after implementation to make sure it worked correctly.

Examples of testing included:
- Checking if the player could move smoothly  
- Ensuring jumping felt natural and responsive  
- Verifying the player did not fall through platforms  
- Testing level navigation  

**Deployment**  
Prepared the final version for submission.

---
## 3. Game Concept

The game is a 2D side-scrolling platformer that draws inspiration from vintage video games. A character that the player controls must move left and right, jump across platforms, and stay upright in order to complete a level.

The goal of the game is to complete the level while avoiding obstacles. By requiring more accurate jumps and better timing, the level is meant to progressively test the player.

Instead of emphasizing intricate features, the game focuses on fundamental platformer mechanics. This includes responsive jumping, fluid motion, and accurate collision detection. To guarantee that the game is both practical and simple to comprehend, the overall design is kept straightforward.

---
## 4. Target Audience

Casual gamers who like easy-to-play games are the target market for this game. It is appropriate for players with little to no gaming experience because the controls are simple to learn.

Because it replicates the fundamental mechanics of classic games, it is also appropriate for players who like retro-style platformers.

The target audience consists of:Young players and students searching for an easy game to play ,Casual players who like quick, simple games  and Players who like challenges based on platforms  

The game's quick gameplay, straightforward goal, and low level of complexity make it suitable for a broad spectrum of players.

---
## 5. User Profiles
<img width="544" height="206" alt="image" src="https://github.com/user-attachments/assets/94a1dda8-71c2-40fa-9546-465a8e5bb069" />
<img width="410" height="178" alt="image" src="https://github.com/user-attachments/assets/0078ce91-df44-40a5-8717-05220fdcecaa" />


---
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

## 12. Scrum Backlog

| Feature | Priority | Description | Test Criteria |
|--------|----------|-------------|---------------|
| Player Movement | High | Allow the player to move left and right using keyboard input | Player moves smoothly left/right when keys are pressed |
| Jump Mechanic | High | Implement jumping using gravity and physics | Player jumps and lands naturally without floating |
| Platform Collision | High | Ensure player can stand on platforms without falling through | Player lands on platforms and does not pass through them |
| Camera Follow | Medium | Camera follows the player as they move through the level | Camera tracks player smoothly without lag |
| Level Design | Medium | Create platforms at different heights for navigation | Player can move across the level using jumps |
| Game Restart | High | Allow the game to restart after player falls or loses | Game resets correctly when player loses |
| Testing & Debugging | High | Identify and fix bugs in movement and collisions | No major bugs during gameplay |



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



