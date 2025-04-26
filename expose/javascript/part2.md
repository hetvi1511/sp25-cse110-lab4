1. 3 is printed because i is declared as a var type variable so it retains its value throughtout the function irrespective of the block it has been declared in.
2. 150 is printed because thats the last value stored in var discountedPrice when i=2 and this when the for loop is exited because at i=3 i is not less than prices.length.
3. Here also 150 is printed because thats the value in var finalPrice when i=2 and this is when the for loop is exited.
4. The function returns the discounted array as [50, 100, 150] because that's the value stored in discounted.
5. There's an error at line 12 because i is defined as a let variable which is block-scope type so outside the for loop, i is not defined and so it causes the error.
6. This would also result in an error because discountedPrice variable is defined as a let variable inside the for loop so the scope of the variable is only within the for loop. That's why when we try to print it outside the for loop, we run into an error.
7. 150 is printed because finalPrice is defined in the main function block so as long as we print it within the function it can print the value stored in it. In this case 150 is when i=2 which is the last time the for loop runs.
8. The function returns the discounted array as [50, 100, 150] because that's the value stored in discounted.
9. There's an error because i is defined as a let variable inside the for loop and let is a block scope type so i is not defined outside the for loop where we are trying to access it and print it.
10. 3 is printed which is the length of the prices array. length variable is defined as the const type variable in the main function and its value cannot and does not change so it correctly prints 3.
11. The function returns the discounted array as [50, 100, 150] because that's the value stored in discounted.
12. A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. student["Favorite Teacher"].name
    E. student.courseLoad[0]
13. A. Output is '32' becuase the + operator triggers string concatenation so 32 is outputted as a string.
    B. Output is the number 1 because in some case such as this the - turns 3 into a number.
    C. Output is the number 3 becuase null is treated as a 0.
    D. Output is '3null' because the + sign performs the string concatenation in this case.
    E. Output is 4 because true takes the value of 1 in this case.
    F. Output is 0 because false and null take them value 0.
    G. Output is '3undefined' because string concatenation takes place in this case.
    H. Output is NaN because undefined is not a number and can't be changed to one.
14. A. Output is true because '2' is changed to the number 2.
    B. Output is false because the string 2 is greater than the string 1 that appears first in '12'.
    C. Output is true because '2' is changed to the number 2.
    D. Output is false because === checks the value and type and 2 is a number but '2' is a string.
    E. Output is false because true takes the value of 1 and 1 and 2 are not the same.
    F. Output is true because boolean(2) will return true.
15. '==' allows type coercion where as '===' check for value and type.
16. a
17. The function will return the array [2, 4, 6]. The modifyArray function loops through the array and pplies the doSomething function to each element of the array which is why it returns [2, 4, 6].
18. a
19. 1
    4
    3
    2
