# ABSTRACT
  Abstract: Tic-tac-toe is a fun game played by two players. Before starting the game, a 3x3 square grid is formed using two vertical and two horizontal lines. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row is the winner.
|  PSNO  |  NAME  |
|----| ----|
| 99006175 |  M.yaswanth Kumar|

# FOLDER STRUCTURE

|  Folder  |  Description  |
|----| ----|
| 1_Requirements |	Documents detailing and research  |
| 2_Architecture|  Documents regarding design details  |
|3_Implementation |	Complete code and documentation  |
|4_TestPlanAndOutput|	Documents with test plan and procedure  |
|5_Report|	Project Report  |
|6_ImagesAndVideos|	Project output and videos | 
# INTRODUCTION
In this course, we're going to learn how to build Tic Tac Toe in Ruby. Just in case you're unfamiliar with the game, let's discuss the rules first. Tic Tac Toe is played on a 3 x 3 grid of available cells, and the goal of the game is to place three of your tokens (X or O) on the grid in a row, including diagonals.

The following example game is won by the first player, X:

![alt tag](http://miro.medium.com/max/1024/1*Syzc_BbO0QHTx74NLHcpiQ.png)
## Objective
The main objectives of this project are: 
* Tic-Tac-Toe Game, Here the user can decide to play with the computer(single player mode) or with other user(double player mode) .
* This game displays wheather the player won the game or lost the game, and also display if it is draw.

## SWOT ANALYSIS
![image](https://github.com/yaswanthmittireddy/stepin-miniproject/blob/main/7_Others/SWOT.jpeg)



## **4 W's and 1 H**

## Who

Anyone who gets stressed and childers during fun hours  can play the game to have some relaxation.

## What

This project is concerned about developing a game which makes us to think logically to win the game.

## When

The children are encouraged to think more logically. They,  naturally develop their logical-mathematical thinking, which can help them in subjects such as math and engineering in the future.

## Why

As this project uses C programming language  it can be easy to understand the logic.

## How

Implemented using Functions , loops and other functionalities of C.
# Detail requirements
## High Level Requirements: 
| ID | Description | 
| ----- | ----- |
| HR01 | User can be able to choose the mode of play |
| HR01 | player1 chooses 'X' to play |
| HR02 | computer choose 'O' to play |
| HR03 | computer shall generate randon inputs |
| HR04 | player shall win|
| HR05 | player shall end up in a Draw situation|

##  Low level Requirements:
 
| ID | Description | 
| ------ | --------- | 
| LR01 | If the user presses '1', he'll be play with computer. |
| LR02 | The user1 is playing with 'O', he'll get the first turn. | 
| LR03 | If the computer gets 3 Xs or 3 Os in vertical,horizontal or diagonal row, User will lose. | 
| LR04 | If neither the computer nor user gets 3 Xs or 3 Os in vertical,horizontal or diagonal row, game will end up with draw. | 
| LR05 | If the user gets 3 Xs or 3 Os(as per his choice), in vertical,horizontal or diagonal row, he'll win. | 
| LR06 | User shall lose|
| LR07 | User shall win|
| LR08 | User shall end up in a Draw situation|

# DESIGN
## BEHAVIOURAL DIAGRAM
### USE CASE
![](https://github.com/yaswanthmittireddy/stepin-miniproject/blob/main/7_Others/use%20case.png)
### ACTIVITY DIAGRAM
![](https://github.com/yaswanthmittireddy/stepin-miniproject/blob/main/7_Others/Activity%20diagram.png)

## STRUCTURAL DIAGRAM
### CLASS DIAGRAM
![](https://github.com/yaswanthmittireddy/stepin-miniproject/blob/main/7_Others/Class%20diagram.png)
### SEQUENCE DIAGRAM
![](https://github.com/yaswanthmittireddy/stepin-miniproject/blob/main/7_Others/sqeuence%20diagram.png)


# TEST PLAN

| Test ID | Description | Exp I/P | Exp O/P |	Actual Output | Type of Test |
| --- | --- | --- | --- | --- | --- |
| T_01 | Check if the code is working as expected, by considering the test cases | 1 | O | O | Pass |
| T_02 | Check if the system handles boundary conditions | 10 | invalid move | inavalid move | Pass |
| T_03 | Check if cross is obtained  | 1 5 9 | O O O |O O O | Pass |
| T_04 | Check if first Row is 3 O's| O O O | Player 1 win | Player 1 win | Pass |

# IMAGES RELATED TO PROJECT
## INPUT 1
![](https://github.com/yaswanthmittireddy/stepin-miniproject/blob/main/6_Image%26Videos/input%201.png)
## OUTPUT 1
![](https://github.com/yaswanthmittireddy/stepin-miniproject/blob/main/6_Image%26Videos/output1.png)
## INPUT 2
![](https://github.com/yaswanthmittireddy/stepin-miniproject/blob/main/6_Image%26Videos/input%202.png)
## OUTPUT 2
![](https://github.com/yaswanthmittireddy/stepin-miniproject/blob/main/6_Image%26Videos/output%202.png)
## INPUT 3
![](https://github.com/yaswanthmittireddy/stepin-miniproject/blob/main/6_Image%26Videos/input%203.png)
## OUTPUT 3
![](https://github.com/yaswanthmittireddy/stepin-miniproject/blob/main/6_Image%26Videos/output%203.png
)
## INPUT 4
![](https://github.com/yaswanthmittireddy/stepin-miniproject/blob/main/6_Image%26Videos/output%203.png
)
## OUTPUT 4
![](https://github.com/yaswanthmittireddy/stepin-miniproject/blob/main/6_Image%26Videos/output%204.png)
## INPUT 5
![](https://github.com/yaswanthmittireddy/stepin-miniproject/blob/main/6_Image%26Videos/input%205.png
)
## OUTPUT 5
![](https://github.com/yaswanthmittireddy/stepin-miniproject/blob/main/6_Image%26Videos/output%205.png)


