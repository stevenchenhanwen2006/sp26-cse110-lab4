1. Line 12 prints 3 because the for loop is executed 3 times because prices.length == 3.
   i is initialized as a var variable with a value of 0, and during each iteration
   of the for loop i is incremented by 1. So i == 3 by the end of the for loop because there is 3 iterations in total.
2. Line 13 prints 150 because discountedPrice stores the last iteration of the discountedPrice in the
   for loop after the for loop. The value of discountedPrice = prices[2] * (1-0.5), so it's 300 * 0.5 = 150.
3. Line 14 prints 150 because we multiplied the discountedPrice by a 100, rounded it and divided it by 100,
   because discountedPrice is an integer, that is equivalent of storing discountedPrice in finalPrice, so finalPrice is also 150
4. The function will return [50,100,150] because it returns the array discounted, which contains a list of finalPrice stored during
   each iteration of the for loop.
5. Line 12 returns an error because the scope of the variable i is inside the for loop
6. Line 13 returns an error because the scope of the variable discountedPrice is inside the for loop
7. Line 14 prints 150 because finalPrice is declared outside of the for loop, so it can be accessed outside the for loop.
   The value of finalPrice is updated in the for loop
8. The function will return [50,100,150] because it returns the array discounted, which is declared outside of the for loop and contains a list of finalPrice stored during each iteration of the for loop.
9. The function returns an error because the scope of the variable i is inside the for loop
10. The function will print 3 because length = prices.length, and prices.length == 3.
11. The function returns [50,100,150] because const variable only prevents you from changing the reference, but you are still able
    to modify what's inside the array.
12. A. student.name  
    B. student['Grad Year']  
    C. student.greeting()  
    D. student['Favorite Teacher'].name  
    E. student.courseLoad[0]
13. A. '32', the output is a string because javacript treats the plus sign between a string and a number as string concatenation  
    B. 1, the output is a number because javascript automatically converts string to number in mathematical expressions or functions  
    C. 3, null is converted to 0 in mathematical expressions  
    D. '3null', null is converted to 'null' in string concatenation  
    E. 4, true is converted to 1 in mathematical expressions  
    F. 0, false is converted to 0 and null is converted to 0 in mathematical expressions  
    G. '3undefined', undefined is converted to 'undefined' in string concatenation
    H. NaN, undefined is converted to NaN in mathematical expressions, so the whole thing gives an error
14. A. true, the string is converted to numbers when comparing different types  
    B. false, for string comparison, '12' is less than '2' because '1' comes before '2' in Unicode  
    C. true, the string is converted to numbers so 2 == '2' returns true  
    D. false, this is a strict equality so the type must be equal as well as the value  
    E. false, true as a boolean is converted to 1, and 1 != 2  
    F. true, Boolean(2) is a boolean of true value because any number except 0 is converted to true, and true === true
15. The difference between == and === operators is that == only compares values after type convertion if needed, while === compares
    values and types.
16. see part2-question16.js
17. The function returns [2,4,6] because during each iteration of the for loop, we called doSomething inside the modifyArray function,
    which multiplies each element in the array [1,2,3] by 2.
18. see part2-question18.js
19. The numbers are printed as 1,4,3,2, and 2 is printed 1 second after 1,4,3 are printed. This is because 1 and 4 are printed synchronously,
    while 3 and 2 are printed via asynchronous callbacks, and 2 has a 1000 milliseconds delay.
    
    