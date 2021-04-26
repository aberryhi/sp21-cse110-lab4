## 1a.
1. values added: 20
2. final result: 20
3. values added: 20
4. error, "result" is only defined within its block
5. error, "result" is const and cannot be reassigned on line 7
6. error, "result" is const and cannot be reassigned on line 7

## 1b.
1. "3" is printed, because "i" is defined with var and can be referenced outside the for loop
2. "150" is printed, because "discountedPrice" is defined with var and can be referenced outside the for loop
3. "150" is printed, because "finalPrice" is defined with var and is printed in the same block it is defined
4. The function will return the array [50, 100, 150]. The final price after the discount is added to the "discounted" array for each price in "prices".
5. An error will occur, as "i" is defined with let and cannot be referenced outside the for loop
6. An error will occur, as "discountedPrice" is defined with let and cannot be referenced outside the for loop
7. "150" is printed, because "finalPrice" is defined with let and is printed in the same block it is defined
8. The function will return the array [50, 100, 150]. The final price after the discount is added to the "discounted" array for each price in "prices", and "discounted" is returned in the same block it is defined.
9. An error will occur, as "i" is defined with let and cannot be referenced outside the for loop
10. "3" will be returned, as "length" is defined as the length of the prices array (3) on line 4 and is printed in the same block.
11. The function will return the array [50, 100, 150]. The final price after the discount is added to the "discounted" array for each price in "prices". Const arrays can have elements added to them, and "discounted" is returned in the same block it is defined.
12. A. `student.name`  
    B. `student['Grad Year']`  
    C. `student.greeting()`  
    D. `student['Favorite Teacher'].name`  
    E. `student.courseLoad[0]`
13. A. '32' because 2 is converted to '2'  
    B. 1 because '3' is converted to 3  
    C. 3 because null is converted to 0  
    D. '3null' because null is converted to 'null'  
    E. 4 because true is converted to 1  
    F. 0 because false is converted to 0 and null is converted to 0  
    G. '3undefined' because undefined is converted to 'undefined'  
    H. NaN because '3' is converted to 3 and undefined is converted to NaN
14. A. true because '2' is converted to 2  
    B. false because '12' comes before '2' in lexicographical order  
    C. true because '2' is converted to 2  
    D. false because they are different types  
    E. false because true is converted to 1  
    F. true because Boolean(2) returns true
15. == will automatically convert type before comparing, === does not convert type
16. [part1b-question16.js](part1b-question16.js)
17. modifyArray will return the array [2,4,6]. It will create "newArr", then run the callback function on each element of "array" and push the result to "newArr". The callback function is doSomething, which doubles the value.
18. [part1b-question18.js](part1b-question18.js)
19. 1  
    3  
    4  
    2