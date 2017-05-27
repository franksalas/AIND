# Build a game playing agent

## Iterative Deepening

Search the level 1 and get an answer for what we thing is the best move, well keep that answer in case we run out of time but we'll start the process again and go to Level 2 this time.
If we finish searching Level 2 before time runs out, we'll keep its best move and restart the search from going from Level 3.
We'll continue doing this process until we run out of time and then return our best answer.

Iterative deepening doesn't waste that much time. Because of the exponential nature of the problem, the amount of time is dominated by the last level searched.

<!-- ![image](/images/quiz1.jpg) -->

### Understanding Exponential Time
<center>
$b=2, n = 2^{d+1}-1$
$b=3, n = \frac{3^{d+1}-1}{2}$
</center>
#### General formula
$b=k, n = \frac{k^{d+1}-1}{k-1}$

## Varying the Branch Factor

## Horizon Effect
A situation where is obvious to a human player that the game will be decided in the next move and a computer player cannot search far enough into the future to figure out the problem.



## Alpha beta pruning
