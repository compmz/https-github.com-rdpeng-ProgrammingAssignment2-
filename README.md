# https-github.com-rdpeng-ProgrammingAssignment2-
#Problem #1
makeCacheMatrix <- function( x = matrix) {
inv <- NULL 
set <- function(y)
x <<- y
inv <<- NULL
}
get <- function(x)
setinv <- function(solveMatrix)inv << solveMatrix 
getinv<- function(inv)}

#Problem 2
cacheSolve <- function(x){
inv <- x$getinverse()
if(!isnull(inv){
message("getting cached data")
return(inv)
}
data <- x$get()
inv <- solve(data)
x$setinv(inv)
inv
