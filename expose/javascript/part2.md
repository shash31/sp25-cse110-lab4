1. Line 12 just prints the value of i which will always be the length of the prices array. In this case, it prints 3. It can access the variable i as it was declared using 'var' thus it has function scope.
2. Line 13 prints out the discounted price of the last item in the prices array. In this case, that would be 50% discount on something that costs 300, thus, it prints 150. It can access the variable discountedPrice as it was declared using 'var' thus it has function scope.
3. Line 14 also prints out 150 as it prints the rounded discounted price of the cost of the last item in the prices array. It can access the variable finalPrice as it was declared using 'var' thus it has function scope.
4. This function will return the array [50, 100, 150]. This is because the function calculates the discount which is entered as 0.5 on all the prices in the given array and returns the new discounted prices.
5. Line 12 causes an error as it cannot access i as its out of its scope as it was defined with the 'let' keyword in the for loop block. Thus, it cannot be accessed outside the for loop.
6. Line 13 also causes an error as it cannot access discountedPrice as it is out of its scope as it was defined with the 'let' keyword in the for loop block. Thus, it cannot be accessed outside the for loop.
7. Line 14 prints the variable finalPrice for the last item in the prices array which in this case is 150. As opposed to the previous questions, it can access the variable finalPrice as it was defined outside the for loop block inside the function.
8. This functino will return the array [50, 100, 150]. This is because the function calculates the discount which is entered as 0.5 on all the prices in the given array and returns the new discounted prices.
9. Line 11 returns an error as i is defined in the for loop block with the 'let' keyword thus, it is out of its scope when something tries to access it out of the for loop. 
10. Line 12 prints the length of the prices array entered in the function which in this case is 3. 
11. This function will return the array [50, 100, 150]. This is because the function calculates the discount which is entered as 0.5 on all the prices in the given array and returns the new discounted prices.
12. A. student.name; B. student['Grad year']; C. student.greeting(); D. student['Favorite Teacher'].name; E. student.courseLoad[0];
13. A. '32'
    B. 1
    C. 3
    D. '3null'
    E. 4
    F. 0
    G. '3undefined'
    H. NaN
14. A. true
    B. false
    C. true
    D. false
    E. false
    F. true
15. The == is the equality operator whereas === is the strict equality operator. The strict equality operator returns false if the data types for the two operands are different where as the regular equality operator does type conversion if the two operands are of different data types. 
16. The result of the function is the array [2, 4, 6]. Here, we pass in the array [1, 2, 3] and the function doSomething as the other argument. The function doSomething just takes in a number and returns its double. In modifyArray(), it calls the function given in the argument on each number in the array passed as the first argument and pushes these new numbers into a new array forming a modified version of the original passed in array where all the numbers are doubled. 
19. The output of the above code is:
    1
    4
    3
    2
 