# Snake-Game
Recreated the classic mobile snake game using React JS 
It includes the apk installation file which able to play in the android phone

Brief about my snake game : 

Snake Game is a classic game that can be implemented using ReactJS. It is simple - the player controls a snake that moves around the screen and eats food to grow longer. The goal is to eat as much food as possible without hitting the walls or the snake's own body.

To create this game using ReactJS, you can start by creating a basic component structure. The main component would be the game board, which would hold the state of the game and render the other components.

The game board component would have a state that contains the following information:

The position of the snake's head and body segments
The direction the snake is moving
The position of the food
The score
To handle the user input, you can use event listeners to detect when the arrow keys are pressed. When a key is pressed, you can update the state to change the direction the snake is moving.

To move the snake, you can use the setInterval method to update the position of the snake's head and body segments every few milliseconds. You can also check for collisions with the walls, the snake's body, and the food. If the snake collides with the food, you can update the score and generate a new position for the food.

Finally, you can render the game board component and its child components, such as the snake and food components, using React's render method.

Overall, creating a snake game using ReactJS involves managing the game state, handling user input, and rendering the game components. With React's component-based architecture and state management, you can create a responsive and interactive snake game that is both fun to play and easy to maintain.


Ready to play ? https://v4ed2v.csb.app/
