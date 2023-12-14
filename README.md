**Tic-Tac-Toe Game**

The code uses a combination of frames, labels, buttons, and event handling to create a simple Tic Tac Toe game with a graphical interface.<br />
The scoring logic highlights winning combinations and increments player scores accordingly.<br />
The code provides a user-friendly way to play and track scores in a Tic Tac Toe game.

**Libraries used**

*Tkinter:*

Tkinter is the standard GUI (Graphical User Interface) toolkit for Python.<br />
It provides modules and classes to create a variety of GUI elements, such as windows, buttons, labels, and entry fields.

*tkinter.messagebox:*

This module is part of the Tkinter library and provides a simple way to display message boxes in a Tkinter application.<br />
In this code, tkinter.messagebox is used to display message boxes for certain events, such as winning the game.

**GUI Setup:**

The code utilizes Tkinter to create a graphical user interface (GUI) for the Tic Tac Toe game.<br />
The GUI includes a main window with a specified size, title, and background color.

**Frame Configuration:**

The GUI is divided into several frames (Tops, MainFrame, LeftFrame, RightFrame, RightFrame1, and RightFrame2) to organize the layout.

**Player Score Variables:**

IntVar() variables (Playerx and Playero) are used to keep track of the scores for Player X and Player O.

**Buttons and Click Handling:**

The game board consists of nine buttons arranged in a 3x3 grid (button1 to button9).<br />
Clicking a button triggers the checker function, which alternately places "X" or "O" on the button based on the current state.<br />
The click variable is used to alternate between "X" and "O."

**Scoring Logic:**

The scores function is called after each move to check if any player has won.<br />
If a player wins, the corresponding buttons are highlighted, and their score is incremented.

**Resetting the Game:**

The reset function resets the game board, clearing the text on all buttons and resetting their background color.

**New Game Functionality:**

The NewGame function resets the game board and sets both Player X and Player O scores to zero.

**Displaying Player Scores:**

Player scores are displayed using Labels and Entry widgets in the GUI.

**Buttons for Reset and New Game:**

Two additional buttons (btnReset and bntNew) allow users to reset the current game or start a new game.

**Main Loop:**

The root.mainloop() line starts the main event loop, allowing the GUI to respond to user interactions.
