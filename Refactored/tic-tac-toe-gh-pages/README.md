tic-tac-toe - Refactored
===========

Chain of Responsibility Patter:  
The chain of responibility pattern starts  in around line 28. The changes involve moving the "someone wins", "It's a tie" trigger from checkWinner() to the individual checks. Furthermore checkWinner() only calls ceckRows() now. This function calls the next check and so on until one function ends the game (win, tie) or the turn is changed to the other palyer. 
