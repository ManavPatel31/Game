# Bug Catcher Game

This is a simple bug-catching game built with JavaScript and HTML5 canvas. The goal of the game is to catch as many bugs as possible by clicking on them within a certain time limit. The game is won by reaching a certain score, and lost by running out of time.

To play the game, simply click on the bugs as they appear on the screen. Each time you catch a bug, your score will increase by 10 points. The game will also become more difficult over time, as the bugs will start moving faster and more frequently.

# How to Run the Game
To run the game, simply open the index.html file in your web browser. The game should load and start automatically.

# Code Overview
The game is built using a simple JavaScript and HTML5 canvas setup. The canvas is created and appended to the HTML document, and then the game assets (background and bug images) are loaded using the Image() constructor.

The game logic is handled in the main() loop, which uses requestAnimationFrame() to continuously render the game and update its state. The bugs are randomly generated and rendered on the screen, and the user's clicks are handled using the canvas.addEventListener() method.

The game also includes a score tracker and difficulty progression, which is controlled by the hopInterval variable. As the user catches more bugs, the interval decreases, causing the bugs to move faster and appear more frequently.

# Customization
To customize the game, you can modify the following variables:

- canvas.width and canvas.height: Adjust the size of the game canvas.
- backgroundImage.src and bugImage.src: Change the game assets by replacing these image files.
- score: Change the starting score value.
- hopInterval: Change the starting interval for bug movement and appearance.

# Credits
This game was built by Manav Patel using JavaScript and HTML5 canvas.
