# GitHub Actions Chess Game

This is an open chess game where ANYONE can play - using this README as the game board!  
It's your turn to play! Move a <!-- BEGIN TURN -->?<!-- END TURN --> piece.

<!-- BEGIN CHESS BOARD -->
(Here goes the chess board)
<!-- END CHESS BOARD -->

**It's your turn to move! Choose one from the following table**
<!-- BEGIN MOVES LIST -->
(Here goes the list of legal moves)
<!-- END MOVES LIST -->


Having fun? Ask a friend to do the next move!

## How it works

When you click on a possible move's link in the table, it will take you to the creation page of a new issue, where you simply need to submit the issue without adding/altering anything to it. 
A GitHub action is then triggered, which runs a small python script that performs the specified chess movement, updates this README file accordingly and commits the changes.
Refresh this page a few moments after submitting the issue to see your move played out on the board!


<details>
  <summary>Last 5 moves in this game</summary>
<!-- BEGIN LAST MOVES -->
(Here goes the list of the last 5 moves, automatically filled by the game - don't touch)
<!-- END LAST MOVES -->
</details>

<details>
  <summary>Top 10 most moves across all games</summary>
<!-- BEGIN TOP MOVES -->
(Here goes the top 10 most moves, automatically filled by the game - don't touch)
<!-- END TOP MOVES -->
</details>

---

Thanks to [@marchizo](https://github.com/marcizhu/) for laying the groundworks for this cool setup!
