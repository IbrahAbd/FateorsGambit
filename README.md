
# Fateor's Gambit


<img src="https://github.com/IbrahAbd/Flappy-Bird-in-PyGame/blob/main/flappy-bird-assets-master/finalFG.png" width="1000" height = "500"/>

<div align="center">
A high-stakes 1v1 FPS Arena Card Battler where every round is unpredictable.  

Step into the fight across three distinct battlegrounds (Gambit Grounds, Gambit Runner 3099, and Fateor’s Foyer) each featuring unique, theme-driven weaponry that changes the way you play.  Strategize, adapt, and outgun your opponent using a card-based system that ensures no two matches ever feel the same.

 ⚔️ Will you leave it to fate or take control with a gambit? ⚔️
</div>

## How To Run

- The executable files can be found in different folders depending on your OS. 
    - The Windows executable is located in the FateorsGambitWin folder and called "FateorsGambitWin.exe"
    - The MAC executable is located in the FateorsGambitMac folder and called "FateorsGambitMac.exe"
    - Launch it to play the game. 
- Once in the game, Press the "Settings" button and set your mouse sensitivity. If you do not do this, you won't be able to move your mouse in the game. 
- Then go back to the main menu and press "Matchmake" to play. 
    - When trying to connect with a second player, make sure to let Player 1 load in completely before Player 2 begins matchmaking. Failure to do this will result in 2 different lobbies being created.
    - There is a known issue of the menu sometimes overlaying once the game ends, this most times resolves itself within a few seconds, but if it persists, a restart  is recommended.
- There is also a tutorial where you can learn the basics of the game. Press the "Tutorial" button to load into it.


## Template Used

The game was built off the free asset template: [Projectiles Advanced Multiplayer - Photon Fusion](https://assetstore.unity.com/packages/templates/systems/projectiles-advanced-multiplayer-photon-fusion-286072). The template uses Photon and Fusion 2 Multiplayer SDKs to setup basic multiplayer connections and logic for Unity. This template was editied and expanded to include our own round and game logic. 

The ranged weapons were provided by the template, with their damage numbers, ranges and attack rates being modified. 

All the melee weapons were taken from free assets provided on the unity asset store with their functionality being a modified implementation of the "WeaponBeam.cs" script. Like the ranged weapons, their damage numbers, ranges and attack rates to provide variety between different weapons.

## Scripts 📜

- In the Scripts folder, the following sub-folders were provided by the template and left largely unchanged :
    - Extensions
    - Utilities
    - UI, Health
    - Projectiles
    - GameplayObjects 


- In the Game sub-folder: 
    - the GameManager and Spawnpoint scripts were unchanged from the template. 
    - The BeanBounce script was added. 
    - The Gameplay script was heavily changed, with basically no methods the same as the template.

- In the Scene sub-folder, All scripts were provided by the template. 
    - Only the SceneContext script was changed, with all the methods and variables added by us, except the first 6 variables.
- All scripts in the Audio, Cards, and Tutorial sub-folders were created by us.

- Some Fusion scripts were built upon for the GUI:
    - FusionBootstrapDebugGUI was adjusted for the more styled main menu.
    - FusionBootstrapDebugGUIS was created for the settings menu.
    - FusionBootstrap was modified to return to the main menu after a game is completed.


## Known Bugs 🐞
- After completing the tutorial, both clients freeze once the countdown completes.
- Occasionally the main menu UI will duplicate. Wait a few seconds or if it persists longer than 10s, restart the game.
    
## Developers 🛠️

- [Mahir Moodaley](https://github.com/MrMoodles123)
- [Ibrahim Abdou](https://github.com/IbrahAbd)
- [Kai Connock](https://github.com/kcurious)

