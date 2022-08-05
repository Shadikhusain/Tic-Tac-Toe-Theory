# Tic-Tac-Toe-Theory

https://user-images.githubusercontent.com/44305804/84823159-300eb880-b01e-11ea-9f2c-db8b899586a1.png


Simple Class Diagram:
https://user-images.githubusercontent.com/44305804/84825913-78c87080-b022-11ea-91d0-285812c4d3b5.jpg

System Components:
TitleScreen [Entry point]: This class is responsible for the GUI of the title screen, its main functionality is to gather game options set by the user, then starting a game by creating a Tic Tac Toe controller with the user options.

TTTController [Controller]: This class is the controller for a Tic Tac Toe game, it takes in game options as input, and controls the view (TicTacToeGame) and the model (Board) according to the game logic specified in this class, it is also responsible for calling the AI agent to play its turn if specified by the game options.

Board [Model]: This class is responsible for representing the underlying model of the game, it is a 2D matrix representation of the GUI that is machine readable, and can be used when running any sort of algorithms on the board.

TicTacToeGame [View]: This class is responsible for the GUI of a game, it is responsible for building the cells of a board, which can be of variable size, and a navigation button to take the user back to the title screen, and a button for resetting the game and playing a new one.


Manage State:
Local state is perhaps the easiest kind of state to manage in React, considering there are so many tools built into the core React library for managing it.

useState is the first tool you should reach for to manage state in your components.

It can take accept any valid data value, including primitive and object values. Additionally, its setter function can be passed down to other components as a callback function (without needing optimizations like useCallback).


Props:
We use props in React to pass data from one component to another (from a parent component to a child component(s)). Props is just a shorter way of saying properties. They are useful when you want the flow of data in your app to be dynamic.





