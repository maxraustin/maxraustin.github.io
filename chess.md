# Chess AI for UVSChess

---

<img src="img/chess2.png?raw=true">

---

## Project Description

---

*Created with C# using Visual Studio as an IDE*

This was a team project for my AI course. The goal was to create an AI that would interface with a provided chess program and that would compete against other team's AIs.

My part in the project involved the implementation of the MiniMax algorithm which the AI uses to traverse the set of possible moves to pick the one with the best value. I also contributed towards the functions that determine the valuation of a given board state. The AI is only given a small amount of time to make decisions. This is a setting used in the chess program, which was set for 5 seconds during competition days.

---

## The Algorithm

---

The AI uses the well-known minimax algorithm with A/B pruning. The AI steps through the available moves for itself and its opponent and uses a function to assign scores to moves based on the corresponding board state. It goes as far as it can until the chess program tells it that it is running out of time, at which point it backs out to the nearest completed search depth and picks the highest value decision among them.

For those interested in code, please see bottom of page.

---

## Board Evaluation

---

Board evaluation is accomplished by first counting raw point values by adding points for the AIs pieces and subtracting points for the opponents pieces based on the values below

|Piece|Value|
|-----|-----|
|Pawn| 10|
|Knight | 30|
|Bishop | 30|
|Rook | 50|
|Queen | 90|
|King | 200|

From here, further points are added based on pieces being on certain positions. For example, knights towards the middle are worth slightly more than those on the edges due to having more movement options.

---


## Important Note about Code

---

If you are interested in the code for this particular project, please contact me at any of the available contacts I have posted here. The code itself is private to help maintain the integrity of the course at UVU. Thank you for your understanding.
