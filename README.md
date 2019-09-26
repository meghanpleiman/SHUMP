# Mini-Project 1 Project Report
## Authors 
Meghan Pleiman and Casey Haskins
## Responsibilities
Meghan constructed the enemy ship, added the background color, created the new colors for the ships and bullets, made the spawner, added the sound, and wrote the report. 

Casey constructed the ship, got the ship to fire correctly, added the lives to the ship, added the functionality of the enemy ship to follow the normal ship, and made the ship take damage. 

## Licenses 
- Music from https://filmmusic.io "Tyrant" by Kevin MacLeod (https://incompetech.com) License: CC BY (http://creativecommons.org/licenses/by/4.0/)
- [Rifle Burst](https://freesound.org/s/482120/), by [qubodup](https://freesound.org/people/qubodup/sounds/482120/) used under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)
- [Explosion_02](https://freesound.org/s/235968/), by [tommccann](https://freesound.org/people/tommccann/sounds/235968/) used under [CC0 1.0](http://creativecommons.org/publicdomain/zero/1.0/)
- [Artillery Explosion (Close)(Mixed)](https://freesound.org/388528/), by [EFlexMusic](https://freesound.org/people/EFlexMusic/sounds/388528/) used under [CC BY-NC 3.0](https://creativecommons.org/licenses/by-nc/3.0/)

## Evaluation 
The following criteria were met in the SHUMP game, demonstrating that we have earned an A on this project.
<!--
        This is a Markdown output of specifications grading criteria. Note that " - [ ]" is Markdown 
        syntax for a checkbox list item. To "fill in" the checkbox, put an 'x' within the square brackets,
        as in, " - [x]". Many markdown preview systems, including GitHub's, will render this as a checkbox.
        -->
- [X] D-1: The camera is placed so that the player can see the ship and the waves
             of enemies.
- [X] D-2: Correctly configured on the depot so that a new client provides a runnable game.
- [X] C-1: WASD, arrow keys, or gamepad controls move the ship appropriately.
- [X] C-2: Z, space, or gamepad controls fire a projectile.
- [X] C-3: Projectiles are removed when they are off-screen.
- [X] C-4: Projectiles damage enemies and are removed after striking them.
- [X] C-5: Collision with an enemy damages or destroys the player.
- [X] C-6: Enemies appear and move in a single direction.
- [X] C-7: Start with a title screen that, on input, transitions into the game.
- [X] C-8: Loop background music.
- [X] C-9: Play sounds upon firing and upon projectiles striking an enemy.
- [X] C-10: Runs without errors
- [X] C-11: All raw referenced assets are in the <code>ToImport</code> folder.
- [X] C-12: Demonstrated during the associated showcase day.
- [X] C-13: Complies with an <a href="http://www.esrb.org/ratings/">ESRB rating</a> of &ldquo;M&rdquo; or lower.
- [X] C-14: All assets are in a folder named after the project [GUSG&nbsp;<a href="https://github.com/Allar/ue4-style-guide#structure-top-level">2.2</a>].
- [X] C-15: Project report meets the requirements listed on <a href="https://www.cs.bsu.edu/~pvgestwicki/courses/cs315Fa19/project">the projects page</a>.
- [X] B-1: Input controls are properly configured through the editor's Input settings.
- [X] B-2: Incorporate weapon cool-down that (a) allows the player to hold
         the attack button for periodic firing and/or (b) limits the rate of fire.
- [X] B-3: Enemy ships demonstrate more advanced behavior than single-direction movement,
          such as circular or periodic movement.
- [X] B-4: Enemies emit projectiles that damage the player on collision.
- [X] B-5: Compiles without warnings.
- [X] B-6: Assets and directories follow naming conventions [GUSG&nbsp;<a href="https://github.com/Allar/ue4-style-guide#anc">1</a>, <a href="https://github.com/Allar/ue4-style-guide#21-folder-names-">2.1</a>].
- [X] B-7: Variables and methods follow naming conventions [GUSG&nbsp;<a href="https://github.com/Allar/ue4-style-guide#321-naming-">3.2.1</a>, <a href="https://github.com/Allar/ue4-style-guide#321-naming-">3.3.1</a>].
- [X] B-8: Contains no assets not used in the build.
- [X] B-9: Commit messages follow established standards.
- [X] B-10: Uses timers and tasks appropriately rather than abusing the <code>Tick</code> event.
- [X] A-1: Player input is managed in a <code>PlayerController</code> subclass while 
         motion is handled in the <code>Pawn</code> subclass that is possessed by
         the <code>PlayerController</code>.
- [X] A-2: Correctly handle multiple simultaneous inputs (for example, the player
         does not move twice as fast when holding W and Up).
- [X] A-3: Enemy ship movement is controlled with an <code>AIPlayerController</code>.
- [X] A-4: Complies with an <a href="http://www.esrb.org/ratings/">ESRB rating</a> of &ldquo;T&rdquo; or lower.
