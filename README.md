# Set of easy exercises in C

## Problem 1:

- with the help of a data structure we stored in a vector of words
the pair of words and its degree
- after calculating the degree with the help of a kind of characteristic vector of letters,
I first sorted the words from that vector of words descending in
depending on the degree, then in descending lexicographical order, taking into account
by the order of degrees

## Problem 2:

- also with the help of a data structure, I stored the coordinates in a vector
to each fool (his x and y), the chessboard being seen as a 2D plane,
but also as a matrix of 1's and 0's
- also when reading, when forming the above vector, we also formed a matrix
the square of mXm with 1 on the positions where there was a madman. this matrix helps
when checking if a madman can be moved so that he doesn't attack with any
- in the first part of the problem, the pairs of pawns on the same board are counted
diagonal (the main diagonal or parallel to the main diagonal of the board, i.e
from left to right, or secondary and those parallel to it, that is
diagonals from right to left) and this number is displayed.
- if the previously calculated number is not equal to 1, then "NO" is displayed
- checking the optimal moving positions (the second part of the problem) is done
searching in the matrix of positions/matrix of fools/matrix- table of positions with 0.
- if a free one is found, that is with 0, then it is checked if, what a fool
he would be in that position, he would attack with every other pawn on the board
- if it is not attacked, then it marks ok=1, a verification variable a
finding a possibility to move and "YES" is displayed.
- if they attack, look for another position.
- if a suitable position was not found, that is, if after searching for everything
table we have ok=0, then "NO" is displayed.

## Problem 3:
- it is known that eight numbers are read, so when reading we make a vector with eight numbers
- each number is converted to base two, but with eight bits/eight digits
- then each number from that one in base two is put in a matrix of strings
- that matrix is transformed into one of type int
- it is transposed
- the multiplication is done with the transpose and with itself and these products are
stores in two different int arrays
- the score of each matrix is calculated
- three scores are made: normal matrix score, a*a score (transposed) and a^2 score
- maximum scores are calculated
- a copy of the matrix with the maximum score is made
- the matrix with the maximum score (which is of type int) is transformed into a matrix of strings
- each line/string in the new matrix of strings is converted into a decimal
and each one is displayed

