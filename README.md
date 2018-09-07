# N-queens
This is a project I completed as a student at [hackreactor](http://hackreactor.com). This project was worked on with a pair.

# Algorithms
This sprint you'll learn a process for writing solutions to computational problems. A tool for visualizing chess board positions will support your exploration of the classic 'N-Queens' algorithms problem. Identify the time complexity for each of your working solutions.

# For your consideration
Pondering the following questions (in order) will help you conceptualize a solution: </br>
Given an n x n chessboard, how would you place n rooks such that none of them are attacking each other?</br>
Given an n x n chessboard, how many different ways can you place n rooks, such that none of them are attacking each other?</br>
Given an n x n chessboard, how would you place n queens such that none of them are attacking each other?</br>
Given an n x n chessboard, how many different ways can you place n queens, such that none of them are attacking each other?</br>


# The problem in a nutshell
Given an n x n chessboard, how many different ways can you place n queens, such that none of them are attacking each other?


![68747470733a2f2f662e636c6f75642e6769746875622e636f6d2f6173736574732f313537373638322f313235373432332f30663236323538652d326261372d313165332d393830382d6233393034316332653161322e706e67](https://user-images.githubusercontent.com/35877838/45191043-dbf26580-b1f5-11e8-8322-54bb832f9d72.png)
![68747470733a2f2f662e636c6f75642e6769746875622e636f6d2f6173736574732f313537373638322f313235373432342f30663265396463632d326261372d313165332d383266632d6666386662376266633332342e706e67](https://user-images.githubusercontent.com/35877838/45191064-fdebe800-b1f5-11e8-970e-f8634f29724d.png)
![68747470733a2f2f662e636c6f75642e6769746875622e636f6d2f6173736574732f313537373638322f313235373432312f30656637663538382d326261372d313165332d396362632d3537376433616432306262312e706e67](https://user-images.githubusercontent.com/35877838/45191076-1a882000-b1f6-11e8-8cda-f0499048654e.png)
![68747470733a2f2f662e636c6f75642e6769746875622e636f6d2f6173736574732f313537373638322f313235373432322f30663132376136362d326261372d313165332d393139362d3232316636356366303365332e706e67](https://user-images.githubusercontent.com/35877838/45191097-2d025980-b1f6-11e8-86ea-89b0bc8051a5.png)

# Helpful Info
Create new board instances that have access to all the helper methods you write in src/Board.js </br>
example: var board = new Board({n:5})</br>
Rather than setting or getting object properties directly with plain JavaScript, Backbone provides the get and set methods. Play with the getters and setters that Backbone provides</br>
example: board.get(3) will return the 3rd row of the instance board (assuming that instance exists)</br>
Rows run horizontally, left to right</br>
Columns run vertically, top to bottom</br>
Major Diagonals run diagonally, top-left to bottom-right</br>
Minor Diagonals run diagonally, top-right to bottom-left</br>
In chess the rook piece moves and attacks horizontally (along rows) or vertically (along columns), through any number of unoccupied squares</br>
In chess the queen piece moves and attacks horizontally (along rows), vertically (along columns), or diagonally (along major and minor diagonals), through any number of unoccupied squares</br>
