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
12. 
