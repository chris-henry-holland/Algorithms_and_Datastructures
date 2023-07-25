<h1>Project Euler</h1>
Contains the solutions to Project Euler questions.
The solutions are written to give a solution to as general a collections of problems, of which the question posed in the specific Project Euler question is a special case, as possible. In particular, they also work with different inputs than those requested by Project Euler questions (which in general only request computation for a single case), and solutions to problems involving the digits of integers are where possible written so that the base used can be specified by the user, and not just limited to representation in base 10.
The solutions are given by the computation of one of the functions in the Project_Euler_m1_m2.py file (where m1 and m2 are integers and [m1, m2] is the range of the Project Euler question solutions the file contains), with the specific functions for each question outlined below. 
The functions representing the solution generally configured so that the default arguments result in the function giving the solution to the corresponding Project Euler question. In other words, say that func is the function that calculates the solution to Project Euler question n, where n is an integer. Then the solution to question n is given by the return value of func(). The exception to this is for questions where the problem is the same just for different inputs (e.g. Project Euler 18 and 67, Maximum Path Sum I & II).

All solutions written using Python 3.6

<h2>Project_Euler_1_50.py</h2>
This contains the functions that calculate solutions to Project Euler questions 1-50 and 67. The function corresponding to each solution is as follows:
