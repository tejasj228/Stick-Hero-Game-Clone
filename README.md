************IMPORTANT NOTE************

---> If you try to extend the stick before all the other animations are over, the game causes a bug where you cannot extend the stick and character just falls down.

---> There are a lot of random bugs that just happen anytime, these are all due to the unstability of JavaFX platform.

__________________________________________________________________________________________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________________________________________________________________________________________


**Name:** 

**----> TEJAS JAISWAL : 2022538 || KSHITIJ SHAH : 2022256**

__________________________________________________________________________________________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________________________________________________________________________________________

StickGame - JavaFX Game Project
__________________________________________________________________________________________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________________________________________________________________________________________

**Table of Contents:**

Introduction
Features
Getting Started
Prerequisites
Installation
Usage
Project Structure
Code Overview
User Class
Volume Class
SpawnPillars Class
Game Mechanics
Serialization and Deserialization
Contributing
License

__________________________________________________________________________________________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________________________________________________________________________________________

**ASSUMPTIONS:**

--> Gap limit: 	5<= Gap <= 180
--> Player width = 35
--> Player fixed position in x : 150 - 35 = 115
--> Please wait for the animation to complete else you will see bugs in the code as we added timing in such a way that 
--> Every pillar fixed position 150

__________________________________________________________________________________________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________________________________________________________________________________________

**Introduction:**

StickGame is a JavaFX-based game project that involves navigating a stick character through a series of pillars while collecting berries. The game incorporates elements of physics, animation, 
and user interaction to create an engaging experience.

__________________________________________________________________________________________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________________________________________________________________________________________

**Features:**

---> Dynamic Pillar Generation: Pillars are randomly generated with varying sizes and gaps, providing diverse and challenging levels.

---> Stick Stretching Mechanism: Players can stretch a stick to bridge the gap between pillars, adding a strategic element to gameplay.

---> Background Animation: The game includes a scrolling background that simulates continuous movement, enhancing the overall gaming experience.

---> Berry Collection: Collecting berries during gameplay contributes to the player's score, adding a rewarding aspect to exploration.

---> Game Over and Revive: The game offers options to retry, revive, or exit when players reach the game-over state, allowing for continuous engagement.

__________________________________________________________________________________________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________________________________________________________________________________________

**Getting Started:**

Prerequisites:

Java Development Kit (JDK) 8 or later
JavaFX library


**Usage:**

---> Launch the game application.
---> Navigate the stick character through the pillars by stretching the stick.
---> Collect berries to increase your score.
---> If the stick does not fit between pillars, the game will end.
---> Options to retry, revive, or exit will be presented upon game over.


__________________________________________________________________________________________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________________________________________________________________________________________


**Code Overview:**

---> User Class
Manages user data such as username, password, highest score, current berries, and player position.

---> Volume Class
Implements a singleton pattern to manage volume settings in the game.

---> SpawnPillars Class
Handles the dynamic generation of pillars, player movement, stick stretching, and game mechanics.

---> Implementation of Junit for testing

__________________________________________________________________________________________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________________________________________________________________________________________


**Game Mechanics:**

---> Pillar Generation: Randomly generates pillars with gaps and sizes.

---> Stick Stretching: Allows the player to stretch a stick between pillars.

---> Background Scrolling: Creates an illusion of continuous movement with a scrolling background.

---> Berry Collection: Increases the score when the player collects berries.


__________________________________________________________________________________________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________________________________________________________________________________________


**Serialization and Deserialization:**

Utilizes Java serialization to save and load user data.

__________________________________________________________________________________________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________________________________________________________________________________________

__________________________________________________________________________________________________________________________________________________________________________________________________
__________________________________________________________________________________________________________________________________________________________________________________________________
