1. At line 12 the method will print the most recent value of the variable i declared in the for loop,
   which is the length of the passed in list which is 3. So on line 12, "3" is printed to the console. Also
   note that i is declared with "var" so it has scope through the whole function
   
2. At line 13 the method will print the most recent value of the variable discountedPrice declared in the
   for loop, which is half of the last value passed in the prices list. So since 150 is half of 300
   "150" is printed to the console. Also note that discountedPrice is declared with "var" so it has scope
   through the whole function
   
3. At line 14 the method will print the most recent value of the variable finalPrice declared in the
   outmost block, which is 100 times the most recent value of the variable discountedPrice (which is
   150 as we found in the last question, so 1500) rounded to the nearest integer (still 1500), divided
   by 100, which comes out to 150. So "150" is printed to the console. Also note that finalPrice is
   declared with "var" so it has scope through the whole function
   
4. The function will return a list of the results of the finalPrice variable in the order the prices
   list was passed in. So [ 50, 100, 150 ]

5. There will be an error on line 12. Since the variable i is declared let in the for loop, it can only
   be accessed within the for loop, so since on line 12 we try to print it to the console outside the for
   loop, i can't be accessed and returns an error
   
6. There will be an error on line 13. Since the variable discountedPrice is declared let in the for loop, it
   can only be accessed within the for loop, so since on line 13 we try to print it to the console outside the
   for loop, discountedPrice can't be accessed and returns an error
   
7. Since the variable finalPrice is declared let in the outmost block of the function, it has scope through
   the whole function. As a result, it has the same result as when it was declared var in question 3. Thus,
   150 is printed to the console
   
8. The function will return a list of the results of the finalPrice variable in the order the prices
   list was passed in. So [ 50, 100, 150 ]. Since we saw in the last question that the finalPrice variable
   isn't affected by the let declarations, the returned values will also be unaffected. Again, this is also
   because the discounted variable is declared let in the outmost block of the function so it has scope
   through the whole function
   
9. Line 11 throws an error because the variable i is declared let in the for loop so it can only be 
   accessed in the for loop. Since we try to print it to the console outside of the for loop, the variable
   is out of scope and throws an error.
   
10. Since length is const and is only assigned value once in the initialization, there is no error thrown
    when we print it to the console in line 12. This means the length of the prices list passed in will be
    printed to the connsole, so "3" is printed
   
11. The function returns the same list as before [ 50, 100, 150 ]. This is because pushing values into the
    list isn't changing values already in it which would throw an error.

12. a) student.name
    b) student['Grad Year']
    c) student.greeting()
    d) student['Favorite Teacher'].name
    e) student.courseLoad[0]
    
13. a) '32' since 2 maps to the string representation of itself
    b) 1 since '3' maps to its integer representation
    c) 3 since null maps to 0
    d) '3null' since null maps to string representation 'null'
    e) 4 since true maps to 1
    f) 0 since false maps to 0 and null maps to 0 as well
    g) '3undefined' since undefined maps to the string representation
    h) NaN since undefined can't map to an integer
    
14. a) true since '2' becomes the integer 2
    b) false since we are comparing two strings which means it uses lexicographical order in which '2' isn't
       first
    c) true since '2' maps to 2 which is equal to 2
    d) false since === doesn't do type conversion and 2 and '2' aren't the same type
    e) false since true maps to 1 and 1 doesn't equal 2
    f) true since Boolean(2) converts 2 to true since nonzero values convert to true, so true === true is true

15. == allows type conversion on both sides while === doesn't 

16. In file 'part2-question16.js'

17. I noticed that the for loop in modifyArray is what is populating the return result array. Each element 
    in it is the returned value from the callback method applied to the corresponding element to the passed in
    array. Then, looking at the callback method we see that all it does is double the number, so the
    resulting returned result array is [ 2, 4, 6 ]
    
18. In file 'part2-question18.js'
