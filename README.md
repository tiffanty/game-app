UpRush is a game where you are a character stuck in an elevator shaft that is platforming up it to avoid the rising elevator. It features various GUI implementations such ass a start and game over screen. The player has the ability to move left and right, as well as jump and even dash with a limited energy bar that can be replenished by collected energy orbs. 



Tiffany Akwarandu's Contributions: Sprites, Animations, and general help. 

- Helped implement and make sure every part of the code meshed together
- Created the sprite for the player
- Obtained and implemented the player's animations, including movements of sprite, making sure
  they are aligning with keys.
- Implemented sound effects for death & game over, bringing the game to life
- Created the instructions screen
- Implemented different animations based on idle, running, and in air







JaCory’s Contribution: Start Screen, Sound, Pause Menu, and Game Control

JaCory worked on the start screen, sound system, pause menu, and game control features for UpRush.

Start Screen:
    •    Created the start screen with the animated “UpRush” title that uses ease in/ease out effect.
    •    Added a start button and made it so players can press ENTER or click to start.
    •    Built a smooth transition (fade effect) when moving from the start screen into the game.
    •    Displayed the player’s high score on the start screen.

Sound and Volume Control:
    •    Added background music that plays during the start screen and the game.
    •    Added sound effects for jumping and dashing.
    •    Made sure the sounds only play once per action (no repeated sounds when holding buttons).
    •    Set up sliders for players to control music and sound effect volume.

High Score Saving:
    •    Made a system to save and load the high score from a file called highscore.txt.





Surendra's Contribution: Background Movement and Design + Obstacle class

As part of the background:
-Created an elevator platform that is constantly moving up along with the background
objects. The elevator shaft is show by the black, side panels. Visual effects include fire and sparks, determined by the FireParticle and Sparks class respectively.
- Additionally, there are warning lights that fade in and fade out periodically. In terms of the upward movement, there is a global moving speed for all objects. There is integration with the player class to move with this speed to ensure smooth gameplay. In terms of platforms, there is dynamic production of these platforms within the bounds of the elevator shaft. This platforms randomly generate in different rectangular shapes to ensure variety.
- This is all mainly organized in the generateWorld() function to easily work with





Mustafa Sarici:

Worked on the data input / data output and the scoring system

* The player high score is stored in a text file inside the data folder of the sketch
* Worked on the function to load in the text file that contains the high score and shows it on the screen when the game starts again
* Created two separate score variables in order to track the current total score of the player (which is based on the time the player is alive) and the high score
* Worked on the function to save the most recent high score of the player
* The function that loads in the highs core is only called once in the setup function
* The current and total scores are constantly updated in the draw function







Evan Hernandez's Contribution: Player class and general help

- The player class is the main controlling factor of what makes the player run. 
- controls physics, collision, and everything to do with how the player operates besides animations.
- ensured project was running smoothly and on time
- Helped implement and make sure every part of the code meshed together






Some unexpected challenges with this project was putting everything together. A lot of our pieces were very specifically made, and we had to constantly account for who's function did what and how we could use that. 



















