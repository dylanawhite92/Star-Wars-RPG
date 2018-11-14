# unit-4-game

## Overview

This assignment is a short Star Wars RPG that lets the player choose their fighter and duke it out against other iconic Star Wars characters.

## Built With

This assignment was built with several things we've covered in class up until now, including: HTML, CSS, Bootstrap, Google Fonts, Javascript, and jQuery.

## Here's How the App Works

* On initialization, all variables involving the characters are cleared or reset and all divs are created and assigned a character.

* The game listens for a user's click on one of the character divs, parses the assigned integer ID in the character's object, and appends it to the **Your Character** section.

* Then, the game loops through the array of characters and adds the remaining characters to the **Enemies** section. It listens for the user's click on an enemy, and then adds that enemy to the **Defender** section.

* Once a -Character- and a -Defender- has been chosen, the user can click the Attack button and the logic for attacking, counter attacking, and the updating of game messages is carried out until either the -Character- or the -Defender- is dead by reducing their HP to 0.

* If the player survives, they can choose another enemy to attack and continue the game with a new enemy.