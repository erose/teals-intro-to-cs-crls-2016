# Unit 1 Challenge

In this challenge, you will make a game.

You control the player (grey) and are being chased by the enemy (red). The goal of the game is to survive as long as possible.

## 1. Basic Functionality

1.1) Create an enemy sprite and a player sprite. Choose starting positions for them and make sure that, when you press the 'c' key, they get returned to those positions.

The player should always moving forward and uses the left and right arrow keys to turn. The enemy is always facing the player and moving towards them. Clicking the flag should start the game.

1.2) When the enemy catches up to the player, the game should restart and the player should go back to their starting position.

What's a good speed for the enemy?

1.3) Make sure the enemy also goes back to the starting position when the player gets caught.

## 2. Magic Orbs

A magic orb is a sprite. Its costume is a circle of a certain color. It should have a starting position that it returns to when you press 'c'. When the player runs into it, it should

  * go away -- there's no block for this in SNAP; I just move it to `(1000, 1000)`.
  * have the effect on the enemy, and make the enemy display the name of the effect for five seconds.
  * end the effect after five seconds.

HINT: Use broadcasts.

2.1) The 'shrink' magic orb makes the enemy smaller.

2.2) The 'fisheye' magic orb applies the 'fisheye' effect to the enemy (use the "set ... effect to ..." block under 'Looks').

2.3) [Challenge] The 'slow' magic orb makes the enemy 50% slower.

2.4) [Challenge] The 'frozen' magic orb makes the enemy unable to move.

## 3. Extra Stuff

There's a lot you can do here. These are just suggestions!

  * Make the player start with 3 lives, and lose a life if they get caught.
  * Make the player have a score that goes up every second they survive.
  * Add another enemy, but make it move randomly instead of following the player.
  * Make another orb that switches the player and the enemy's positions (there's a trick to this).
