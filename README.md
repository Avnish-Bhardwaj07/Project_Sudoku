# Sudoku Game

This is a **Sudoku game project** developed using HTML, CSS, JavaScript, and Java. The project allows users to play Sudoku with different difficulty levels and ensures a user-friendly experience.

## Features
- Interactive Sudoku board.
- Multiple difficulty levels (Easy, Medium, Hard).
- Real-time validation of inputs.
- Option to get hints and reset the board.

## Team Members and Contributions
1. **Avnish Bhardwaj** - Frontend Development (HTML & CSS)
   - Designed the layout and styling of the Sudoku board and UI components.
   
2. **Lokesh** - Backend Logic (Java)
   - Implemented the Sudoku game generation logic and validation using Java.

3. **Nikhil** - JavaScript Functionality
   - Integrated frontend with backend and handled the game interaction features.

4. **Vinayak Tyagi** - Documentation and Testing
   - Wrote the project documentation and performed testing for various functionalities.

## Repository Structure
```
Sudoku-Game/
├── frontend/
│   ├── index.html       # Main HTML file
│   ├── style.css        # Styling for the Sudoku board and UI
│   └── script.js        # JavaScript for frontend interactions
├── backend/
│   ├── Sudoku.java      # Main Java logic for game generation and validation
├── docs/
│   ├── README.md        # Project documentation
├── resources/
│   ├── sample_sudoku.png # Screenshot of the game
├── .gitignore
└── LICENSE
```

## Requirements
To run this project, ensure you have the following installed:
- A web browser (e.g., Chrome, Firefox)
- Java Development Kit (JDK) version 8 or higher

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Sudoku-Game.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Sudoku-Game
   ```
3. Run the Java backend:
   ```bash
   cd backend
   javac Sudoku.java
   java Sudoku
   ```
4. Open the `index.html` file in your browser to start the game:
   ```bash
   cd ../frontend
   open index.html
   ```

## How to Play
1. Open the game in your browser.
2. Select a difficulty level.
3. Fill in the numbers to complete the Sudoku puzzle.
4. Use the "Validate" button to check your solution.
5. You can reset the board or get hints as needed.


