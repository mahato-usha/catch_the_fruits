# catch_the_fruits 
This is a simple game where the player controls a basket with the arrow keys to catch falling fruits. The game consists of two canvases, one for the background and one for the gameplay. The background image is loaded from an external file and the player and fruit images are drawn onto the gameplay canvas using the canvas context.

The game uses two constructor functions, Player and Fruit, to create player and fruit objects respectively. The Player constructor creates a player object with properties such as the player's position, speed, score, and number of fruits collected and missed. It also has methods to move the player left or right and to draw the player onto the canvas.

The Fruit constructor creates a fruit object with properties such as the fruit's position, speed, score, and image. It also has methods to make the fruit fall, check if it has been caught by the player, and draw the fruit onto the canvas.

The game starts by creating a new Player object and an array of Fruit objects. The number of fruits in the array is determined by the numberOfFruits variable. The game loop is implemented using the setInterval() function, which calls the update() function every 30 milliseconds. The update() function clears the gameplay canvas, updates the positions of the player and fruits, checks if any fruits have been caught, and draws the player and fruits onto the canvas.

The game keeps track of the player's score and the number of fruits collected and missed. If the player misses too many fruits, the game is over and the player's score is compared to the previous high score. If the player's score is higher, it becomes the new high score. The game then displays a game over screen with the player's score and the high score. The player can restart the game by pressing the enter key.

# How to Play
Use the left and right arrow keys to move the basket horizontally. Try to catch as many fruits as you can before the time runs out. The game ends when you miss 10 fruits.

# Customization
If you want to customize the game, you can modify the variables in the script.js file.

# Technologies Used
Catch the Game is built using HTML, CSS, JavaScript, and NodeJs.
