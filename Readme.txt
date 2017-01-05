
Three versions of code to compute the Fibonacci number. Given a number greater than or equal to 0, the Fibonacci number for that number is the value at that given number as position in the series 1, 1, 2, 3, 5, 8, 13, 21,... In other words, the value at a position is equal to the sum of values at previous two positions. The first two positions, 0 and 1, have the values 1 and 1, respectively. The value as position 5, for example, is 8.

The three versions are:

1. Iterative solution. Use a loop to compute the value at a given position.

2. Recursive solution. Use a recursion to compute the value at a given position.

3. Use recursive solution with memoization. Memoization uses caching technique to store the value computed already. If the value that was computed is asked for once again, the cached value is retuned instead of being computed.

The main principles are under use are 
The DRY principle - Dont Repeat Yourself

The YAGNI principle- You Aint Gotta Need It yet

The DIP - Dependancy Inversion Principle - Handle the level of abstraction

The Single Responsibility Principle - Increased cohesion

The Open Closed Principles - open for extension but closed for modification and it leads to extensibility


 For Code coverage please refer to
 FibonacciNumbers\build\reports\coverageHtml
