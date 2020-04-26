# Project-Euler-1
My C++ solution to the first project euler problem on https://projecteuler.net/problem=1

The problem is stated as follows:
*If we list all the natural numbers below 10 that are multiples of 3 or 5,
we get 3, 5, 6 and 9. The sum of these multiples is 23.*

*Find the sum of all the multiples of 3 or 5 below 1000.*

My solution employs a for loop with a nested if statement.
The for loop iterates through numbers 0 to 999 and checks
to see if the current number (i) is a multiple of 3 or 5
by checking for a remainder of 0 using the % operator.
If the if statement returns true, 'i' is added to an int
variable called 'sum'. After the loop finishes, 'sum'
is outputted to the console.

