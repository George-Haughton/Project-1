# Project 1

## 1. Specifications
This game will consist of a player controlling a small square by moving his or her mouse. There will be an NPC (Non-Playable Character) chasing the players mouse and will attempt to touch the players mouse/square with its own square. The player will have 3 lives and will need to run away from the NPC for as long as possible but as soon as the players is touched 3 times the game will end.

## 2. Requirements
#### Non Functional Requirements
1. There will be a pure white screen that has the title 'TraceBall' with a small blue button below it that the player will click to start the game, which will start immediately.

2. The game will have a pure white background with a pure black border surrounding it. This is to make sure the players know the space they have to play. While the player is trying to escape they will be focusing on the NPC and their own square and either will not want to look away or will want to take a quick glance at the space they have. Using a strong, visible colour like black gives the player an easier time looking at the space they have with their quick glance. 

3. The game will contain two squares, one that is an NPC and another which will be the player. There will be two coloured squares, one for the NPC square and one for the player square; so the player knows which square they are. The NPC square which will be red to indicate it being the enemy, and the player's square will be blue to indicate that is it friendly.

#### Functional Requirements
1. Create the game screen in the top left of the screen taking up a space of 600px X 600px, which is a perfect size for the game as it is big enough to not strain the player’s eyes trying to look at a small box and small enough so it is not completely in your face and unnecessarily huge. Additionally, this size is perfect for a game of this nature, as games like this are enjoyable because of their simplicity; and this size provides that.

2. Create a button that will start the game. This will be a small blue button that the player will press that will start the game.

3. Create a pure white screen for the blue button to be on.

4. Create a title on the pure white screen that read 'TraceBall'

5. Create a collision detection for both squares. This will indicate to the player that they have been hit. This will be shown as the blue square turning red to indicate the player's square has been 'hit'/'hurt' (this is why it turns red) and the game will reset back to the start, where the game will start instantaneously, with 2 lives and so on until the player loses all 3 lives.

6. Create a blue square that will be controlled by the player's mouse movements. This square will react instantly to the player's mouse movements so the player has complete control over their square.

7. Create a red square that an NPC (Non-Playable Character) will control. This square move at a slower speed to make sure it does not instantly catch the player. The NPC will follow the players square and try to collide with it 3 times to end the game.

## Software requirements 
* I will be writing the code of the game in JavaScript.

* The IDE I will be using is Notepad

* I am going to make sure the NPC follows the player controlled square

* I will make sure the player controlled square is controlled by the movement of the player’s mouse


## User Stories

I would like to play the game within a browser, as I would be able to access it very easily.

I would like to see the NPC chase me while I am playing, as this would give me a sense competitiveness.

I would like to be know when the NPC has collided with my square so I know I have lost a life.

I would like to when the NPC has collided with my 3 times so I know that I have lost and the game is over.

I would like my square to follow my mouse movements so I can guide and control it.

## Project Backlog of user stories

|User Story|Description|Difficulty out of 5|Due date|Complete|
|----------|------------------------------------------------------------------------------------------------|--------------|-------|---|
| 1 |I would like to play the game within a browser, as I would be able to access it very easily.|2|N/A|No|
| 2 |I would like to be know when the NPC has collided with my square so I know that I have lost a lIfe.|3|N/A|No|
| 3 |I would like to see the NPC chase me while I am playing, as this would give me a sense competitiveness.|4|N/A|No|
| 4 |I would like to when the NPC has collided with me 3 times so I know that I have lost and the game is over.|3|N/A|No|
| 5 |I would like my square to follow my mouse movements so I can guide and control it.|3|N/A|No|

When we were given this project, it came with a project brief which outlined what needed to be done. After looking over the brief I came up with a general idea of what I would need to do to meet the requirements of the project which was to create a mini game where the player would control a square that would be controlled with their player’s mouse movements. Additionally, there would be a second square which was an NPC (non-playable character/computer controlled character) that the player would have to avoid by moving their mouse away from it. After being hit 3 times by the NPC the game would end and the player would lose.

Firstly, I broke the project into requirements; these are the most important/main objectives I need to address and things I need to complete to meet the needs of the requirements, these consisted of functional requirements and non-functional requirements. These functional requirements are visible objects or entities within the game that can be picked out by playing the game. For example, the NPC and player controlled square are a functional requirement as I need to create a visible square within the game. Additionally, the non-functional requirements are requirements that don’t do anything they are there for a purpose but do not move, and can be seen as the backbone/foundations of the game for example the white canvas background.

Secondly, I created user stories which are tasks or events that a player will want to happen within the game. For example, a user story I created was 'as a player I would like to know when the NPC has touched my square' this gave me a better idea at what features I would need to add to meet the requirements, make the player engaged and make sure they are enjoying the game. Additionally, the user stories gave me a better understanding at what the player would like to see/experience when playing. 

After making user stories to help me better understand the project from a player’s perspective I created a project backlog based on the user stories. This consisted of me outlining the user story, having a difficulty/value from 1-5; 1 being easy and 5 being very difficult to make sure I prioritised the more difficult user story. It also contained a part where I answered if it had been completed or not. This gave me an idea at what I should be working on first and give myself more time to work on the ones I may need more time to complete.

