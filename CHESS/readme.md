# CHESS
***
### Problem Statement
The positions of white king and rook are plotted against black King and you have to predict either the number of moves it takes for the white king to win or say if the white king loses.

### Dataset
A KRK dataset was first described in 1977. This dataset is also a KRK dataset, meaning it consists of positions of White King, White Rook, and Black King. In such a scenario if both teams play optimally(Black moves first) the only possible outcomes are either a draw or White King wins. 
The attributes are :    

* White King file (column)
* White King rank (row)
* White Rook file
* White Rook rank
* Black King file
* Black King rank
* optimal depth-of-win for White in 0 to 16 moves, otherwise draw(-1) .

### Files
* train.csv - (22444 samples) This csv file contains the positions of the White King, Rook and the Black king with the number of moves it takes for White king to win.
* test.csv - (5611 samples) This csv file contains the positions of the White King, Rook and the Black king but without the number of moves it takes for White king to win.

### Evaluation Metrics
During evaluation **Mean Absolute Error** and **F1 score** will be used to test the efficiency of the model.

### Result
#### No. of Registered: 359
#### Rank: 38

[Leaderboard](https://www.aicrowd.com/challenges/aicrowd-blitz-2/problems/chess/leaderboards?)<br/>
[Challenge Page](https://www.aicrowd.com/challenges/aicrowd-blitz-2/problems/chess)<br/>
[Resources](https://www.aicrowd.com/challenges/aicrowd-blitz-2/problems/chess/dataset_files)
