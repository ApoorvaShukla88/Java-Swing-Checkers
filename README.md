<h1>Java-Swing-Checkers</h1>

Your goal is to implement the functionality for the model of a checkers game. 

The board is to be represented by a 8x8 2D array of strings. Pieces on the board should be denoted as Color-Rank. For example, a Red Pawn should be R-P and Black King 
should be B-K. An empty square should be denoted by the string EMPTY.

All the animations are taken care of by the view, no work is needed there. All off your logic should be in the update method of the Model. 

<h3>Requirements</h3>
<ul>
  <li>The system generates a new game board (see mock up)</li>
  <li>The user can move their piece</li>
  <li>The system removes the opponent's piece when the user performs a jump</li>
  <li>The user's piece is kinged when they reach the opposite side of the board</li>
  <li>The source code should all be unit tested</li>
  <li>The system should save the game to a text file when the user presses the 's' key</li>
  <li>The system should load the last saved game when the user presses the 'l' key</li>
</ul>
<h3>Mock Ups</h3>
<img src="https://drive.google.com/uc?export=view&id=1kYKqzbyezM8DjMLYRZI6cCAveYsYzb_B" width=300px height=300px/>

