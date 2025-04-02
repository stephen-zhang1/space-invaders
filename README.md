# Space Invaders - Game Instructions & Description

## Game Description

In this arcade-style game, the player controls a spaceship, referred to as the "tank," positioned at the bottom of the screen. The objective is to eliminate waves of enemy invaders before they reach the bottom of the screen. The player can move left and right using the arrow keys and fire missiles using the space bar. If an invader reaches the bottom, the game is over.

### Requirements

    - Movement: Use the left (←) and right (→) arrow keys to move the tank horizontally.

    - Continuous Movement: Holding down the arrow key moves the tank in that direction at a constant speed. Releasing the key stops movement.

    - Boundary Limit: The tank cannot move past the edges of the screen.

    - Firing Missiles: Press the space bar to shoot a missile straight up from the tank's current position.

    - Missile Behavior: Once fired, the missile moves upwards at a constant speed.

    - Enemy Behavior: Invaders (enemy spaceships) appear at the top of the screen and descend in a straight vertical path. Some invaders move at different speeds.

    - Destroying Invaders: If a missile hits an invader, the invader is destroyed.

    - Game Over Condition: If an invader reaches the bottom of the screen, the game ends.


## Additional Requirements for the Space Invaders Game

    - Missile Collision Effect: When a missile hits an invader, there should be a small explosion animation or visual effect before the invader disappears.

    - Invader Speed Increase: As the player progresses (e.g., after every 10 invaders shot down), the speed of new invaders slightly increases to make the game more challenging.

    - Limited Lives: The tank has three lives. If an invader reaches the bottom, the player loses a life. The game ends when all lives are lost.

    - Score Multiplier: If the player successfully destroys multiple invaders consecutively without missing a shot, a combo multiplier increases their score.

    - Power-ups: Occasionally, a special power-up invader appears. If hit, it grants an extra missile, temporary rapid-fire ability, or a shield for the tank.

    - Background Music & Sound Effects: The game includes background music and sound effects for shooting missiles, destroying invaders, and game-over events.

    - Dynamic Background: The background subtly changes (e.g., stars moving) to create a space-like effect.

    - Leaderboard: A high-score tracker is displayed, showing the player's highest score from previous attempts.

    - Pause & Resume: The game can be paused and resumed using the "P" key.

    - Different Invader Types: Introduce different enemy types:

    - Basic Invader: Moves straight down.

    - Fast Invader: Moves faster but is worth more points.

    - Zig-Zag Invader: Moves unpredictably, making it harder to hit.

    - Win Condition: After reaching a score milestone (e.g., 100 points), a victory message appears, and the player can restart.

    - Mobile Compatibility: Ensure the game works with touch controls, allowing movement and shooting via on-screen buttons.

    - Game Start Trigger: The game starts only when the player moves the tank (left or right), ensuring no automatic start.

    - Soundtrack Activation: Background music starts when the game begins and does not play before that.

    - Looped Soundtrack: The background music plays continuously during gameplay but stops once the game is over.

    - Laser Sound Effect: A "laser beam" sound effect is played whenever the player fires a missile.

    - Explosion Sound Effect: A distinct explosion sound effect plays when an invader collides with the tank or a missile.

    - Clean Console Output: The deployed game must not display visible errors or debugging messages in the browser console.

    - Object-Oriented Programming (OOP): The game should follow OOP principles, with distinct Tank and Invader classes. It should also use inheritance and polymorphism where appropriate.

    - Encapsulation of Game Logic: The game should be structured with a Game class that encapsulates all logic. The main.js file should primarily handle setting up the canvas and instantiating the Game class, keeping it short and clean.

    - Efficient Memory Management: The game should efficiently manage objects, reusing or destroying inactive invaders and missiles to optimize performance. This means implementing garbage collection when a missile exits the canvas or hits an invader.