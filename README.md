# Various Methods of Determining the N<sup>th</sup> Fibonacci Number
And their respective space and time complexities, with example code in Python

## Naive Recursion
f<sub>0</sub> = f<sub>1</sub> = 1  
f<sub>n</sub> = f<sub>n-1</sub> + f<sub>n-2</sub>

## Memoized Recursion

## Iterative

## Closed Form Z-Transform
f<sub>n</sub> = ((1/sqrt(5)) * ((((1/2)+(sqrt(5)/2))<sup>n</sup>)-((1/2)-(sqrt(5)/2))<sup>n</sup>))

## Matrix Exponentiation

## Advanced Recursion (Fast Doubling)

f<sub>0</sub> = f<sub>1</sub> = 1  
f<sub>2n</sub> = 2f<sub>n</sub>f<sub>n+1</sub> - f<sub>n</sub><sup>2</sup>  
f<sub>2n+1</sub> = f<sub>n+1</sub><sup>2</sup> + f<sub>n</sub><sup>2</sup>  

## Memoized Advanced Recursion
