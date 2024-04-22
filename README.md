# Mini-Project-Tic-Tac-Toe-Python

<p>This is a simple implementation of the classic Tic Tac Toe game in Python. The game allows you to play against a computer opponent or against another human player.</p>

<h2>How to Play</h2>

<p>To play the game, follow these steps:</p>

<ol>
    <li>Clone the repository to your local machine:</li>
    <code>git clone &lt;https://github.com/JAK0707/Mini-Project-Tic-Tac-Toe-Python&gt;</code>
    <p>Or download the source code directly from the repository.</p>

  <li>Navigate to the directory containing the files:</li>
    <code>cd &lt;directory_name&gt;</code>

  <li>Run the game using Python:</li>
    <code>python game.py</code>
    <p>You will be prompted to make moves by entering the number corresponding to the square where you want to place your symbol (either 'X' or 'O').</p>
</ol>

<h2>Files</h2>

<ul>
    <li><code>game.py</code>: Contains the main logic to run the game.</li>
    <li><code>player.py</code>: Defines classes for different types of players, such as <code>HumanPlayer</code>, <code>RandomComputerPlayer</code>, and <code>SmartComputerPlayer</code>.</li>
    <li><code>README.md</code>: This file.</li>
</ul>

<h2>Packages Used</h2>

<p>The following Python packages are used in the program:</p>
<ul>
    <li><code>math</code>: Used for mathematical calculations.</li>
    <li><code>time</code>: Used for time-related functions.</li>
</ul>

<h2>Functioning and Logic</h2>

<p>The program consists of the following components:</p>

<ul>
    <li><strong>TicTacToe Class</strong>: Represents the Tic Tac Toe game board and provides methods to interact with the board, such as making moves, checking for winners, and displaying the board.</li>
    <li><strong>Player Classes</strong>: Different player types are defined in the <code>player.py</code> file. These include:
        <ul>
            <li><code>HumanPlayer</code>: Allows human players to make moves by inputting their choices.</li>
            <li><code>RandomComputerPlayer</code>: Generates random moves for the computer player.</li>
            <li><code>SmartComputerPlayer</code>: Implements a simple algorithm to make intelligent moves for the computer player.</li>
        </ul>
    </li>
    <li><strong>Game Logic</strong>: The <code>game.py</code> file contains the main logic to run the game. It allows players to take turns making moves until there is a winner or the game ends in a tie. The game logic handles switching between players, validating moves, and determining the outcome of the game.</li>
</ul>

<p>The game supports customization by allowing players to choose their opponents and adjust the difficulty level.</p>

<h2>Requirements</h2>

<ul>
    <li>Python 3.x</li>
</ul>
