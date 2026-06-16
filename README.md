# Platform Quest - 2D Platformer Game


## Table of Contents
- [1.0 Project Overview](#10-project-overview)
- [2.0 Project Aim and Objectives](#20-project-aim-and-objectives)
- [3.0 Game Concept & Target Audience](#30-game-concept--target-audience)
- [4.0 Overall Specification & Minimum Viable Product (MVP)](#40-overall-specification--minimum-viable-product-mvp)
- [5.0 User and System Requirements](#50-user-and-system-requirements)
- [6.0 Scrum-Style User Stories](#60-scrum-style-user-stories)
- [7.0 Scrum Product Backlog](#70-scrum-product-backlog)
- [8.0 Game Narrative, Characters, and Visual Design](#80-game-narrative-characters-and-visual-design)
- [9.0 Environment, Gameplay, and Player Motivation Loops](#90-environment-gameplay-and-player-motivation-loops)
- [10.0 Game Rules & Logic System](#100-game-rules--logic-system)
- [11.0 State Management Architecture](#110-state-management-architecture)
- [12.0 Engine, Platform, and Input Maps](#120-engine-platform-and-input-maps)
- [13.0 Core Algorithmic Pseudocode (GDScript Structure)](#130-core-algorithmic-pseudocode-gdscript-structure)
- [14.0 Project Management & Development Records](#140-project-management--development-records)
- [15.0 Comprehensive Testing Strategy and Test Logs](#150-comprehensive-testing-strategy-and-test-logs)
- [16.0 Technical Challenges & Solutions](#160-technical-challenges--solutions)
- [17.0 Critical Project Evaluation](#170-critical-project-evaluation)
- [18.0 References](#180-references)

## 1.0 Project Overview
**Platform Quest** is a 2D side-scrolling platform game designed and developed using the **Godot Engine (v4.x)** and programmed in **GDScript**. Created as part of the reassessment for the Software Development 2 module, the project demonstrates how to plan, build, and test a simple interactive system.

The game requires the player to explore an underground map, run across platform layouts, jump over open gaps, gather ancient relics, avoid obstacles, and locate the final exit portal safely.

## 2.0 Project Aim and Objectives

### 2.1 Aim
To build, evaluate, and document a stable 2D platformer prototype in Godot that satisfies core software engineering principles—specifically low class coupling, modular scenes, and solid input validation.

### 2.2 Objectives
* **Requirements & Sprints:** Organize assignment constraints into real Scrum User Stories and a manageable Product Backlog.
* **Scene Architecture:** Use Godot's node nesting tree to separate player logic, level design, UI, and collectible items.
* **Physics & Interactions:** Code responsive movement profiles by adapting Godot’s built-in vector functions.
* **State Operations:** Set up a clean layout linking the Main Menu, active level loops, Game Over screens, and Victory screens.
* **Tests:** Run systematic playtests to prove the code matches our original assignment requirements.

## 3.0 Game Concept & Target Audience

### 3.1 Game Concept
Platform Quest balances classic 2D retro design with modern game feel. The level layout provides a natural difficulty progression. 

### 3.2 Target Audience 

#### Casual Gamers
* **Characteristics:** Want immediate visual feedback, straightforward layouts, and easy-to-learn control schemes.
* **Design Match:** Configured intuitive directional keyboard layouts along with clear score displays.

#### Nostalgic Platform Game Fans
* **Characteristics:** Players who love 2D pixel styles, strict jump weight, and a fair mechanical challenge.
* **Design Match:** Applied crisp *Nearest Neighbor* filters to pixel art sheets and tuned gravity curves to match retro gameplay.

#### Students & Young Adults (Aged 18–25)
* **Characteristics:** Highly sensitive to sticky collisions, poor hitboxes, or loose floaty movement.
* **Design Match:** Fine-tuned collision boxes and grounded checks so player movement inputs respond instantly.

## 4.0 Overall Specification & Minimum Viable Product (MVP)

### 4.1 Core Features (The MVP)
To keep the project scope realistic while ensuring all grading parameters are achieved, the core features include:
* **Bidirectional Movement:** Horizontal tracking connected directly to player arrow or `A`/`D` keys.
* **Grounded Jump Vectors:** Vertical physics checked against the floor to prevent infinite mid-air jumps.
* **Static Layer Colliders:** Setting up terrain layer layers so the player interacts properly with walls and solid paths.
* **Relic Tracking:** Intercepting overlapping boundaries to update point counts before safely freeing the item instance.
* **Basic Hazards:** Dedicated contact triggers that immediately load failure states.
* **UI Screen Overlays:** Clean canvas layers for the Main Menu, Game Over screen, and a final Level Clear prompt.

### 4.2 Optional/Extended Scope Features
* **Dynamic Camera Bounds:** Adding a `Camera2D` smoothing offset to trace player positions comfortably.
* **Audio Feedback Streams:** Connecting node streams to trigger unique sound effects whenever a player jumps or collects items.

### 4.3 Explicit Acceptance Criteria
The prototype is considered complete and operational only when:
1. The character moves left or right instantly on input and cuts speed immediately when keys are released.
2. The vertical jump only triggers when the player node's floor check is verified as true.
3. Overlapping a danger tile immediately halts inputs and switches the scene to the Game Over template.
4. Touching the exit gate stops physics updates and opens the Level Win overlay menu.
