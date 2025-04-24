1. values added:  20
2. final result: 20
3. We should not use var because it is a function scope variable. That means that it will hold its value throughout the value irrespective of the block it was defined it (given that the block is within the function). So, here result is still 20 even outside the if-block.
4. value added: 20
5. It causes an error. This is because the result variable is defined as a const type which has block-scope so, outside of the if-block result has not been defined.
6. It causes an error in line 7 because we are trying to change the value of a const variable which we initially assigned the vaue of 0.
7. The code does not reach line 13 because there is an error in line 7 so line 13 is never executed.
