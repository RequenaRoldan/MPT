The program “MPTs_rxc.exe” is a program written in Fortran that calculates all
the maximum probability tables (MPTs) starting from an MPT.

INPUT: number of rows and number of columns (integer values greater than 0) of 
the initial MPT and frequency of each cell of the MPT (all frequencies must be 
values greater than or equal to 0). If any frequency is not a suitable value 
then an error message is displayed.

The maximum dimension of the initial MPT is 11x30. The maximum value of each 
marginal sum of row or column is 25,000. With these values, a great majority 
of the problems that arise in practice can be solved.

The program is valid if in the algorithm for calculating the MPTs no row has 
to be increased by more than 8 units. This situation (increasing more than 
8 units) is extremely unlikely.

The program requests the number of MPTs that are desired to be obtained. 
This value is requested after displaying the number of MPTs obtained.

OUTPUT: the initial MPT and its probability, the associated U table, 
the number of MPTs obtained, the number MPT that is desired to be 
obtained and the MPTs. The result is recorded in a text file 
called “output_2” in the same folder from which the program is run.
