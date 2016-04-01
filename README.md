# Blackjack_Game
Here in this projec, We have implementated the blackjack game on FPGA spartan 3 (VHDL)
For implementing the game we only use 4 buttoms of the board and the four 8-segments display 
available on the board. To do this We have had to make a simplificated version of the game. 
The changes we have done are:
- "As" card only have one value and is one 
- This is a 2 player game
- Face cards appear on display only by his numeric value

The game dynamic is: 
1) Turn on the board
2) On the four 8-segments display appear "PLAY"
3) Press play buttom
4) JUG1 appear 
5) Press Play buttom again 
6) Now you can see 4 zeros. The first two zeros are the value of the card and the last 2 zeros is the score
7) If you press play a new card appear(the numbre of the card) and every time you press play a new card appear
and the value of the card is summed to the score. If your score is larger than 21 the board automatically
passes to the next player display. You have the option of standing. So there is a buttom for this function. 
If you decide to stand the game automatically progress to the 2 player display. 
8) When the turn of player 1 is finished on the display appear "JUG2". Press play to start the player 1 turn
9) Player 2 has the same rules as player 1. Press play to hit or press the standing buttom to stand
10)When Player 2 finish its turn appears on the displays the name of the winner. If there is a draw appears "----"
11) Press play to start a new game

The game has been implemented by a moore machine (states machine).


