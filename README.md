About makeCacheMatrix function:

This function creates a special “matrix” object that can cache its inverse. cacheSolve: This function computes the inverse of the special “matrix” returned by makeCacheMatrix above. If the inverse has already been calculated (and the matrix has not changed), then the cachesolve should retrieve the inverse from the cache. Computing the inverse of a square matrix can be done with the solve function in R. For example, if X is a square invertible matrix, then solve(X) returns its inverse.

For my assignment, assume that the matrix supplied is always invertible.

The following functions are used to create a special object that stores a matrix and caches its inverse. The first function, makeCacheMatrix creates a special “matrix”, which is really a list containing a function to:

set the value of the matrix

get the value of the matrix

set the value of the inverse

get the value of the inverse
![image](https://user-images.githubusercontent.com/84325486/119271050-6c2e9e00-bc1d-11eb-902d-a2592512cc3e.png)

cacheSolve should retrieve the inverse from the cache
![image](https://user-images.githubusercontent.com/84325486/119271059-7fda0480-bc1d-11eb-97a2-bf5f4963ca07.png)
 Testing it with an example
 Input:
 ![image](https://user-images.githubusercontent.com/84325486/119271115-b6b01a80-bc1d-11eb-8147-e86c0511d393.png)
Output:
![image](https://user-images.githubusercontent.com/84325486/119271199-27efcd80-bc1e-11eb-8a39-e8132dd7d4df.png)

