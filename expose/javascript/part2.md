1. This will print 2 because i is declared with var, making it a global variable so it is accessible outside of the for block
2. This will print 150 because discountedPrice is declared with var, making it a global variable which is accessible outside of the for block.
3. This will also print 150 because finalPrice is declared globally with var.
4. It will return an array [50, 100, 150] because discounted is declared with var globally.
5. This will cause an error because i is declared after for, which is considered in the for block. Variables defined with let only exist within their code blocks, and 12 is outside of that code block.
6. This will cause an error for the same reason as 5
7. This will retun 150 because finalPrice was defined in the same codeblock as line 14.
8. It will return [50, 100, 150] because all of the local variables defined in the for loop are not used outside of it, so no errors are caused.
9. An error for the same reason as 5. 
10. It will return 3 because length is defined in the same code block as line 12.
11. It will return [50, 100, 150]. No errors are thrown because const arrays can have elements pushed to them.
12. A. student.name
    B. student["Grad Year"];
    C. student.greeting();
    D.student["Favorite Teacher"].name
    E. student.courseLoad[0]
13. A. '32' because addition will cause string conversion
    B. 1 because the math operation will cause Numeric Conversion
    C. 3 because null does numeric Conversion with numbers
    D. '3null' because null does String Conversion with strings
    E. 4 because booleans do Numeric Conversion with numbers
    F. 0 because null and booleans do Numeric Conversions with arithmetic operations
    G. '3undefined' because undefined does String Conversion for append
    H. NaN because undefined becomes NaN in arithmetic
14. A. true, '2' becomes number 2
    B. false, '2' is greater lexographically than the '1' in '12'
    C. true, '2' becomes 2
    D. false, equality without type conversion between diff types
    e. false, true maps to 1
    F. true, 2 is cast to true as a boolean
15. == will change types to check equality, for instance '0' will change to 0 if we do 0 == 0. But === does strict equality, so they must be the same type to be equal
16. See part2-question16.js
17. The array [2, 4, 6] will be returned because doSomething multiplies the given number by 2, and we call doSomething on every value in the given array [1, 2, 3]
18. see part2-question18.js
19. it prints 1 4 3 2 because 1 and 4 have no timeout, and 3 has a lower timeout than 2.
