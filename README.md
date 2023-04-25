# binary-search

Here's the algorithm for the given code:

1. Start the main function.
2. Declare an integer array arr of size 6 and initialize it with some values.
3. Ask the user to enter a number to be searched and read it into the variable a.
4. Set the value of l to 6.
5. Initialize the variables b and e to 0 and l-1 respectively.
6. Initialize the variable mid and result to -1.
7. Run a while loop with the condition b<=e.
8. Calculate the value of mid as (b+e)/2.
9. If the value of arr[mid] is equal to a, set the value of result to mid and break out of the loop.
10. If the value of arr[mid] is greater than a, set the value of e to mid-1.
11. If the value of arr[mid] is less than a, set the value of b to mid+1.
12. Print the value of result.
13. End the main function.
