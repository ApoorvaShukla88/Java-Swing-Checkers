<h1>Java-Swing-Checkers</h1>

Your goal is to implement the functionality for the model of a checkers game. 

The board is to be represented by a 8x8 2D array of strings. Pieces on the board should be donated as Color-Rank. For example, a Red Pawn should be R-P and Black King 
should be B-K. An empty square should be denoted by the string EMPTY. 

All the animations are taken care of by the view, no work is needed there. Two methods are stubbed out for you to complete, create and update. Create is used to create the 
game at start. Update is called when the user makes a move. The current board, current player, and the moves start and stop coordinates are passed in as parameters. This method 
should update the board based on the move and return the modified board.  

<h2>Part One</h2>
<h3>Requirements</h3>
<ul>
  <li>The system generates a new game board (see mock up)</li>
  <li>The user can move their piece</li>
  <li>The system removes the opponent's piece when the user performs a jump</li>
  <li>The user's piece is kinged when they reach the opposite side of the board</li>
</ul>
<h3>Mock Ups</h3>
<img src="https://drive.google.com/uc?export=view&id=1kYKqzbyezM8DjMLYRZI6cCAveYsYzb_B" width=300px height=300px/>