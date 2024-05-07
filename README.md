# Tic-toe-Toe-Game
This project involves the Creation of a console-based TicTacToe game using Java,demonstrating fundamental principles of projects of Object-oriented Programming.The game consists of several classes to represent the board, Players, and the Main game launcher.

. TicTocTeo Class : 
         Initializes a 3*3 game board and displays it. Manages the gmae board state and provides methods for checking wins and draws. Implements logic for checking wins in rows, columns, and          Diagonals.
. Player Class (Abstract) :-
         An abstract class defining common attributes like player name and symbol. Contains an abstract method makeMove() for making a move, to be implemented by subclasses.

HumanPlayer Class (Extends Player): 
         Represents a human Player. Takes user input for row and column to make a move. Ensures the move is valid and updates the game board.

. AIPlayer Class (Extends Player) :

         Represents an AI Player. Generates random moves for the AI to simulate computer opponet behavior. Ensures the generated move is valid and updates the game board.

LaunchGame Class : 
        The main class responsible for starting and running the game. Creates instances of the TicTocToe game, a human Player, and an AI Player. Creates instances of the TicTocToe Game, a               
.  Human player, and an Ai Player. 
        Alternates turns between players, allowing them to make moves and updating the board. Checks for win or draw conditions after each move, terminating the game if necessary.


.  Key Features:

        Clear separation of concerns with distinct classes for the game, Players, and launcher. User-friendly interaction with the Human Player class taking user input. AIPlayer class   simulates a computer opponent by generating random moves. Demonstrates principles of encapsulation, inheritance, and polymorphism in an object-oriented context. Rebust error handling to  ensure valid moves and prevent out-of-bounds access. An intuitive display of the game board after each move for a better user experience.

. Skills Demonstrated :

Profinciency in Java programming, emphasizing object-oriented concepts. Implementation of game logic for win and draw conditions. User input handling error validation. Randomization for AI decision-making. Modular and organized code structure for maintainability.

. Conclusion :

This TicTacToe Project serves as a comprehensive illustration of Java Programming skills, particularly in object-oriented design, user interaction, and game logi implementation. It showcases a well-structured and readable codebase suitable for educational purposes or as a foundation for expanding into more complex game development projects.
