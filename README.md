# Tic Tac Toe

A simple, console-based implementation of the classic Tic Tac Toe game, written in Java. Two players take turns marking spaces in a 3x3 grid to achieve three consecutive marks in a row, column, or diagonal.

---

## Features

- Interactive Gameplay: Players input their moves through the console.
- Dynamic Game Board: The board updates in real-time after each move.
- Winning Logic: Detects winning conditions and announces the winner.
- Input Validation: Ensures valid moves, preventing overwriting of occupied cells.

---

## Prerequisites

Ensure you have the following installed:

- [Java JDK](https://www.oracle.com/java/technologies/javase-downloads.html) (version 8 or above)

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/pulkitgarg04/TikTakToe-Game.git
   cd TikTakToe-Game
   ```

2. Compile the Java files:
    ```bash
    javac Main.java
    ```

3. Run the application:
    ```bash
    java Main
    ```

---

## How to Play
1. The game initializes with an empty 3x3 board.
2. Players are assigned markers:
    - Player 1: X
    - Player 2: O
3. Players take turns entering their moves:
    - Input the row and column indices (0, 1, or 2) for your move.
    - For example: 1 1 places your marker in the center of the board.
4. The game detects if a player wins or if the board is full.
5. The game ends when:
    - A player forms a line of three marks (row, column, or diagonal).
    - The board is full with no winner (draw).

---

## GamePlay

**Initial Board**:
```
  |   |  
---------
  |   |  
---------
  |   |
```  

**Player X Move (1, 1)**:
```
  |   |  
---------
  | X |  
---------
  |   |
```

**Player O Move (0, 0)**:
```
O |   |  
---------
  | X |  
---------
  |   |  
```

---

## Contribution
Feel free to fork the repository and submit pull requests to enhance the functionality of the script.

#### Steps to Contribute
1. Fork the Repository:
    - Click the Fork button at the top right of the repository page to create a copy of the repository in your GitHub account.

2. Clone Your Fork:
    - Clone your forked repository to your local machine:

    ```bash
    git clone https://github.com/pulkitgarg04/TikTakToe-Game.git
    cd TikTakToe-Game
    ```

3. Create a New Branch:
    - Create a new branch for your changes:
    ```bash
    git checkout -b feature/your-feature-name
    ```

4. Make Your Changes:
    - Edit the script or add new features. Make sure your changes are well-tested.

5. Commit Your Changes:
    - After making changes, commit them with a clear and descriptive message:
    ```bash
    git add .
    git commit -m "Add a detailed description of your changes"
    ```

6. Push Your Changes:
- Push the changes to your forked repository:
    ```bash
    git push origin feature/your-feature-name
    ```

7. Open a Pull Request (PR):
- Go to the original repository on GitHub.
- Click on the Pull Requests tab.
- Click New Pull Request and choose your branch from your fork as the source.
- Provide a descriptive title and explanation of your changes.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.