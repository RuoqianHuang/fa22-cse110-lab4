1. It will print 3 to the console because there are 3 elements in the input list. i is a var so its scope is the entire function and we can access it without problems at line 12.
   
2. It will print 150 to the console because during the last execution of the for loop (when i equals 2), discountedPrice = prices[2] * (1 - 0.5) = 300 * 0.5 = 150. discountedPrice is also a var so its scope is the entire function and we can access it without problems at line 13.
   
3. It will print 150 to the console because during the last execution of the for loop (when i equals 2), finalPrice = Math.round(1500 * 100) / 100; = 150. finalPrice is also a var so its scope is the entire function and we can access it without problems at line 14.
   
4. This funtion will return a list called "discounted", which contains a list of the finalPrice (original price with the discount applied). In this case, [ 50, 100, 150 ].
   
5. It will return an error since i is not defined at line 12 (scope limited within the block due to the let keyword).

6. It will return an error since discountedPrice is not defined at line 13 (scope limited within the for block due to the let keyword).

7. It will print 150 to the console because finalPrice is defined at the start of the function without being blocked by others. Therefore, its scope is the entire function and we can access it without problems at line 14.

8. This funtion will return a list called "discounted", which contains a list of the finalPrice (original price with the discount applied). In this case, [ 50, 100, 150 ].

9.  It will return an error since i is not defined at line 11 (scope limited within the block due to the let keyword).

10. It will print 3 to the console since length is set to the length of the prices list at the beginning of the function. Its scope is the entire function and we can access it without problems at line 12.

11. This funtion will return a list called "discounted", which contains a list of the finalPrice (original price with the discount applied). In this case, [ 50, 100, 150 ].

12. a. student.name
    
    b. student['Grad Year']
    
    c. student.greeting();
    
    d. student['Favourite teacher']["name"]
    
    e. student.courseload[0]


13. a. '32' since integers map to their exact string   representation
    
    b. 1 since the integer representation of '3' is 3 and 3-2=1
    
    c. 3 since null becomes 0 when added to 3 and 3+0=3
    
    d. '3null' since null becomes 'null' and is concatenated with '3', forming a new string
    
    e. 4 since true maps to 1 and 1+3=4
    
    f. 0 since both false and null map to 0 and 0+0=0
    
    g. '3undefined' since undefined maps to its exact string representation and is concatenated with '3', forming a new string
    
    h. NaN since conversion failed and undefined becomes NaN

14. a. true since the integer representation of '2' is 2 and 2>1 is true
    
    b. false since it is dictionary comparison: first char "2" is greater than the first char "1"
    
    c. true since '2' becomes 2 and 2 is equal to itself
    
    d. false since strict equality is strict. Different types from both sides lead to false.
    
    e. false since true becomes 1 and 1 is not equal to 2
    
    f. true since Boolean(2) maps to true, thus === true

15. A strict equality operator === checks the equality without type conversion while == checks with type conversion

16. see the file

17. The output will be an array of [2,4,6]. When we call modifyArray([1, 2, 3], doSomething), our array is [1,2,3] and callback function is doSomething, which is defined to double the input. At first, an empty array called newArray is constructed; then, we loop through the original [1,2,3] array and apply doSomething to each element; the doubled result is pushed to newArr and we end up with the [2,4,6] array.

18. see the file
    
19. The output is 1 4 3 2
