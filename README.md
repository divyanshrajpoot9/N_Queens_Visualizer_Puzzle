# N_Queens_Visualizer_Puzzle:
### Hosted Link: 
### Technologies Used: HTML5/CSS3/JavaScript/ES6/Git/GitHub/VSCode/Figma/FontAwesomeCDN.
This code is a JavaScript implementation of the N-Queens problem visualization using HTML, CSS, and JavaScript. 
Here's a breakdown of the code:
1. **HTML Structure**: The HTML file contains elements with IDs "numberbox", "slider", "progress-bar", "play-button", "pause-button", "n-queen-board", and "queen-arrangement". These elements are manipulated by JavaScript.

2. **JavaScript Variables**:
   - `numberbox`, `slider`, `progressBar`, `playButton`, `pauseButton`: Variables referencing various HTML elements.
   - `queen`: HTML markup for a chess queen icon.
   - `n`, `speed`, `tempSpeed`, `q`, `Board`: Variables used for controlling the visualization and solving the N-Queens problem.
   - `array`: Pre-calculated number of possible arrangements for different N values.
   - `pos`: Object used to store the state of the boards.
   - `Queen`: Class representing a Queen object with methods to solve the N-Queens problem and visualize the process.

3. **Event Listeners**:
   - `slider.oninput`: Updates the speed of visualization based on slider input.
   - `playButton.onclick`: Initiates the visualization process when the play button is clicked.

4. **Queen Class**:
   - `constructor`: Initializes the Queen object.
   - `nQueen`: Method to start solving the N-Queens problem.
   - `isValid`: Method to check if placing a queen in a certain position is valid.
   - `clearColor`: Method to clear colors on the chessboard.
   - `delay`: Method to introduce delays in visualization.
   - `solveQueen`: Recursive method to solve the N-Queens problem.

5. **Visualize Function**:
   - Triggered when the play button is clicked.
   - Parses input from the number box to set the size of the chessboard.
   - Clears previous arrangements and boards.
   - Generates HTML elements for the chessboard.
   - Initiates the N-Queens visualization process.

This code aims to demonstrate how the N-Queens problem can be solved and visualized using JavaScript, providing insights into the process of finding solutions. It utilizes HTML and CSS for the user interface and JavaScript for the logic and animation.
## The approach followed in this code can be summarized as follows:

1. **User Interface Setup**:
   - HTML is used to create the necessary elements for the user interface, such as input boxes, buttons, and the chessboard visualization area.
   - CSS is used to style these elements for a visually appealing interface.

2. **Event Handling**:
   - Event listeners are set up to handle user interactions, such as changing the speed of visualization with a slider and initiating the visualization process with a play button click.

3. **Data Representation**:
   - The chessboard and queen placements are represented using HTML tables.
   - JavaScript variables store data related to the state of the chessboard, queen positions, and visualization parameters.

4. **N-Queens Solver**:
   - The core logic of solving the N-Queens problem is encapsulated within the `Queen` class.
   - The `isValid` method checks whether a queen can be placed in a specific position without conflicting with existing queens.
   - The `solveQueen` method recursively attempts to place queens on the chessboard while ensuring no conflicts occur.

5. **Visualization**:
   - Visual cues are provided to represent valid and invalid queen placements on the chessboard.
   - Delays are introduced between steps to create a visual animation of the solving process.
   - Colors are used to highlight valid and invalid placements, as well as to distinguish between different boards.

6. **User Interaction and Feedback**:
   - Users can input the size of the chessboard via an input box.
   - Feedback messages are displayed for invalid inputs or when the N-Queens problem is being solved.

7. **Optimizations and Performance**:
   - The code includes optimizations such as pre-calculating the number of possible arrangements for different N values to provide efficient feedback to users.

Overall, this approach combines elements of user interface design, algorithm implementation, and visualization techniques to solve and demonstrate the N-Queens problem in an interactive and engaging manner.

  ## User Interface:
![visualisation](https://github.com/divyanshrajpoot9/N_Queens_Visualizer_Puzzle/assets/114856467/b42d0fc1-a95a-4189-baae-fcd7181ff23c)
![Screenshot 2024-04-10 094119](https://github.com/divyanshrajpoot9/N_Queens_Visualizer_Puzzle/assets/114856467/c53d42bc-2016-4494-a4a4-1b6ce4eda935)
