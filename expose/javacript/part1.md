PART 1
1. Line 9 prints "values added: 20." The variable result is declared using var in the sumValues function and result holds the result of 10+10.
2. Line 13 prints "final result: 20." As result is declared in the function sumValues using var, so the value it obtains at one point is kept throughout the function unless changed. Therefore, it will be 20.
3. Line 9 prints "values added: 20." Here, let declares result in the if block and within the if block, we utilize the value assigned to result which is 20.
4. Line 13 results in an error that 'result' is not defined. This is because let only puts the variable "result" in the scope of the if block. It is not defined outside, so we get an error.
5. Line 9 results in an error. const was used for result so the value is supposed to stay at 0. We try changing its value so there is an error.
6. Line 13 also results in an error. The variable result is referred to outside of the block it was declared in, so there is an error.
  
PART 2
1. At line 12, the number 3 will get printed. i is defined as a var so it is within the scope for all aspects of the function, and line 12 is within the function. It takes on the value of i for the iteration that does not complete, which is 3.
2. At line 13, the number 150 will get printed. Here, the variable discountedPrice is initialized using var, so the final value it gets assigned will get carried over to the log statement. This value is attained during the last i value iteration for which the for loop conditions hold, which is 2. 
3. At line 14, 150 will get printed. Similar to previous question, finalPrice is initialized as a var so the final value will carry over. In this case, the final value is given during the i = 2 iteration, so finalPrice will be 100*100/100 with the round function applied, resulting in 150.
4. Now, the function will not print anything because there is no log statement. However, discounted will feature all of the values of finalPrice obtained during the 3 iterations for which the loop is ran. The values it will be filled with are 50, 100, and 150.
5. At line 12, it will result in an error. This is because i is declared only within the scope of the for loop block, and if we refer to it outside of the loop, it is no longer defined.
6. Similar to the previous question, at line 13 we will experience an error. This is because discounted price is declared using "let" only within the for loop. Once we call it outside the loop, it is no longer defined for that scope, so there is an error.
7. Here at line 14, the value 150 will be presented. The let keyword is used to initialize finalPrice in the scope of the entire function block, so its value will get changed in the for loop to hold the result for the final iteration where i = 2. This way, we get 150 when calling it later on.
8. Nothing will be printed to the output here, but the function will return the appropriate array correspondoing to the discount, which is [50, 100, 150]. This is because the resulting final prices are using within their scope and they'll get added to the discounted array. That discounted array is declared in the scope of the entire function so we will indeed get the accurate values when referring to it later on. 
9. At line 11, we will get an error. This happens because the variable i is being declared using the let keyword only within the scope of the for loop. When we refer to it outside of the for loop, it is no longer defined and there is an error.
10. At line 12, we will get the accurate length of the array "prices" which is 3. This is because length is declared in the scope of the entire function.
11. This function will not print anything to output, but the return value of the function will be the array [50, 100, 150]. This happens because we are defining and declaring a const variable at the same time instead of doing them on different lines. This way, the accurate value will be assigned. This value will also be placed in the discounted array because it is in the scope of the for loop where the discountedPrice variable has been initialized. The array discounted is declared in the scope of the entire function, so the right value will be returned. 
12. For the object student:
    A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. student["Favorite Teacher"].name
    E. student.courseLoad[0]
    
