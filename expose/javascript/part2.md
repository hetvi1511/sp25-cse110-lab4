1. 3 is printed because i is declared as a var type variable so it retains its value throughtout the function irrespective of the block it has been declared in.
2. 150 is printed because thats the last value stored in var discountedPrice when i=2 and this when the for loop is exited because at i=3 i is not less than prices.length.
3. Here also 150 is printed because thats the value in var finalPrice when i=2 and this is when the for loop is exited.
4. The function does not return anything to the terminal because it is a return statement and that does not print anything. It returns an array with the discounted price but again nothing is printed the code just runs without errors.
5. There's an error at line 12 because i is defined as a let variable which is block-scope type so outside the for loop, i is not defined and so it causes the error.
6. This would also result in an error because discountedPrice variable is defined as a let variable inside the for loop so the scope of the variable is only within the for loop. That's why when we try to print it outside the for loop, we run into an error.
7. 150 is printed because finalPrice is defined in the main function block so as long as we print it within the function it can print the value stored in it. In this case 150 is when i=2 which is the last time the for loop runs.
8. Same as question 4, the function does not print anything to the terminal because it is a return statement and that does not print anything. It returns an array with the discounted price but again nothing is printed the code just runs without errors.
9. There's an error because i is defined as a let variable inside the for loop and let is a block scope type so i is not defined outside the for loop where we are trying to access it and print it.
10. 3 is printed which is the length of the prices array. length variable is defined as the const type variable in the main function and its value cannot and does not change so it correctly prints 3.
11. 
