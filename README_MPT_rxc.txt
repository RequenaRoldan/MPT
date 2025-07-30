The program “MPT_rxc.exe” is a program written in Fortran that calculates a maximum probability table (MPT).

INPUT: number of rows, number of columns, marginal sum of each row and marginal sum of each column.
All these values must be integer values greater than 0 (otherwise an error message is displayed).

It must be verified that the sum of all the marginal totals of rows is equal to the sum of all the marginal totals of columns. 
Otherwise an error message is displayed.

The maximum number of rows is 11 and the maximum number of columns is 30. 
The maximum value of each marginal total of row or column is 25,000. 
With these values, a large majority of the problems that arise in practice can be solved.

OUTPUT: a maximum probability table (MPT), the probability of this MPT, the associated U table and the computation time. 
The result is recorded in a text file called “Output_1” in the same folder from which the program is run.
