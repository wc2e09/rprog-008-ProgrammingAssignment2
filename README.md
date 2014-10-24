rprog-008-ProgrammingAssignment2
================================

1.The R file was used for submitting the Assignment2 of r-programming course @coursera

2.In order to test inverse function easily, this assignment2 used ginv() function as the function to calculate inverse matrix. 
  Or you may use inv() instead of ginv() to do the testing by replacing line #42.
  
3.You may invoke the following commend as reference to do the testing. "getting cached data" was the message to prove this function worked.



> source("cachematrix.R")

> x=matrix(1:16,4,4)

> y=makeCacheMatrix(x)

> cacheSolve(y)

       [,1]    [,2]  [,3]    [,4]
[1,] -0.285 -0.1075  0.07  0.2475
[2,] -0.145 -0.0525  0.04  0.1325
[3,] -0.005  0.0025  0.01  0.0175
[4,]  0.135  0.0575 -0.02 -0.0975

> cacheSolve(y)

getting cached data

       [,1]    [,2]  [,3]    [,4]
[1,] -0.285 -0.1075  0.07  0.2475
[2,] -0.145 -0.0525  0.04  0.1325
[3,] -0.005  0.0025  0.01  0.0175
[4,]  0.135  0.0575 -0.02 -0.0975
