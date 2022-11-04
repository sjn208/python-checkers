# python-checkers
Command-Line Game of Checkers via Python

The main code to run is checkers.py. Entering piece selections should follow format << (Row#,Col#) >> with no spaces. 

board.py contains the Board class with methods to intialize the board, show the board, move a piece, delete a piece, and ensure that pieces are movable. 

spaces.py contains the Piece class, an abstract class for the representation of a "red" and "black" player piece, and the Node class to represent an empty position on a checker board.  

players.py contains two classes Red and Black derived from Piece, with methods to check that the piece is crowned. 
