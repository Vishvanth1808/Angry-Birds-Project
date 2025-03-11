Angry Birds Game
This Angry Birds game was created using Java and the libGDX framework. The game has a home page,level selection screen and three levels with different functionality.
Currently, Level 1 is functioning, with interactive buttons and a score display, however Levels 2 and 3 have no score display and merely a close button.
In addition, the game has a settings tab where you can change numerous in-game parameters.There are also interactive Bird,Pig and Structure components.
The goal is to throw birds at structures and pigs, hoping to knock them down and defeat the pigs.
Class:
Main:
* The main class that initializes the game, manages the SpriteBatch, and sets the home screen.
level1:
* Manages the first level of the game.
* Functionalities:
   * Displays background, catapult, and score when "End Level" is clicked.
   * End Level button triggers score display.
   * Exit button returns to the level selection screen.
Level 2:
* Manages the second level of the game.
* Functionalities:
   * Displays a static background and catapult.
   * Settings button for modifying game settings.
   * Close button to return to the level selection screen.


Level 3:
* Manages the second level of the game.
* Functionalities:
   * Displays a static background and catapult.
   * Settings button for modifying game settings.
   * Close button to return to the level selection screen.
SettingScreen:
* Provides a user interface for adjusting game settings.
* Functionalities:
   * Includes back, sound, save, info, and exit buttons with hover effects.
   * Exit button will close the application.
   * Returns to the level selection screen via the back button.
levelselectionpage:
* Provides a level selection interface for players.
* Functionalities:
   * Buttons for each level, settings, and exit to the main menu.
   * Interactive hover effects for a more engaging selection screen.
Bird:
* Represents a bird object with launch, position update, and disposal capabilities.
Pig:
* Represents a pig object with health points and damage management.
Structure:
* Represents a structure that can be damaged. Each structure has a material type affecting its health.
Usage:
* Navigate Screens: Choose levels from the level selection screen. To change the game settings, click the settings button, or return to the main menu.
* Level Interactions:
   * In Level 1, select the "End Level" button to view your score and save it.
   * In Level 2, press the close button to return to the level selection screen.
   * In Level 3, press the close button to return to the level selection screen.
* Settings:Change game settings and save them. Return to the level selection screen once completed.
