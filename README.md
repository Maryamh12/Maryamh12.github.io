# Maryamh12.github.io
#  Snak Game!

Snak Game is a classic snake game implemented using HTML, CSS, and JavaScript. The game allows the player to control a snake and navigate it to eat food and grow longer. The objective of the game is to achieve the highest score possible without colliding with the boundaries or the snake's own body.



![enter image description here](https://cdn-icons-png.flaticon.com/128/1303/1303574.png)
#  Features

-   Responsive and visually appealing game interface.
-   Smooth snake movement controlled by arrow keys.
-   Randomly generated food for the snake to eat.
-   Score tracking and display.
-   Game over detection when the snake collides with the boundaries or itself.
-   Start and restart functionality.

##  Technologies Used

-   HTML
-   CSS
-   JavaScript

## Getting Started

To run the Snake Game locally, follow these steps:

1.  Clone the repository:
    
    
    
    `git clone <repository-url>` 
    
2.  Navigate to the project directory:
    
    
    
    `cd snak-game` 
    
3.  Open the `index.html` file in your preferred web browser.
    
4.  Start playing the Snake Game!

##  JavaScript Code

The JavaScript code for the Snake Game is contained in the `script.js` file. Here's a brief explanation of its key components:

-   **Game Initialization**: The game initializes by setting up the game board, initializing the snake's position and direction, placing the food randomly on the board, and setting the initial score to 0.
    
-   **Game Loop**: The core functionality of the game is based on a game loop implemented using the `setInterval()` function. This loop continuously updates the game state and redraws the game board on the screen.
    
-   **Snake Movement**: The snake's movement is controlled using the arrow keys. The direction of the snake is updated based on the key pressed by the player.
    
-   **Collision Detection**: The code checks for collisions between the snake and the boundaries of the game board or its own body. If a collision is detected, the game is over, and the loop stops.
    
-   **Food Consumption**: When the snake's head collides with a food item, it "consumes" the food, grows longer, and the player's score is increased.
    
-   **Game Over and Restart**: When the game ends due to a collision, a "Game Over" message is displayed, and the player can restart the game by clicking the "Play Snake" button.

## CSS File

The CSS styles for the Snake Game are defined in the `style.css` file. Here's an overview of its structure and purpose:

-   **Layout**: The CSS file defines the overall layout of the game board and other elements. It sets the dimensions and positioning of the game container and centers it on the screen.
    
-   **Colors and Styling**: Various CSS styles are applied to create an attractive and visually appealing interface. You can find styles for the snake, food, score display, game over message, and the play button.
    
-   **Animations**: The CSS file contains animations for the snake's movement and transitions for smooth visual effects.
    
-   **Responsiveness**: The game interface is designed to be responsive, adapting to different screen sizes and orientations.
    
-   **Background Image**: The CSS file may include a background image for the game board, adding to the game's aesthetics.

##  Customization

You can customize the game by modifying the JavaScript code and CSS styles. In the JavaScript code, you can tweak game mechanics, add power-ups, or implement additional features. In the CSS file, you can adjust colors, sizes, positions, and animations to create a unique look for the game.


