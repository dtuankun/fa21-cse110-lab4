## Part 2

1. i = 3, because var can be accessible outside the block-scope, and after the end of the loop it is 3 which is the size of array.
2. discountedPrice = 150, because it is declared with var, and it is calculated with the last loop which is `prices[2] * (1-0.5)`
3. finalPrice = 150, because discountedPrice is 150, so `Math.round(150 * 100) / 100` is 150 too
4. [50, 100, 150] in an array format, because the calculation basically cut 50% of the price and push it back into the `discounted` variable of array type.
5. It will give an error of i is undefined because i is declared in the for scope with a let
6. It will give an error of discountedPrice is undefined because it is declared in the for scope with a let
7. 150, because the let is declared in the discountPrices function scope, so it is in the same scope and we get access to it
8. [50, 100, 150] in an array format, because the calculation basically cut 50% of the price and push it back into the `discounted` variable of array type.
9. It will give an error of i is undefined because i is declared in the for scope with a let
10. length = 3 because it is defined with const and accessed within the scope
11. [50, 100, 150] in an array format, because the calculation basically cut 50% of the price and push it back into the `discounted` variable of array type.
12.

```js
// A
student.name;

// B
student['Grad Year'];

// C
student.greeting();

// D
student['Favorite Teacher'].name;

// E
student.courseLoad[0];
```

13. Arithmetic

    1. 32, since 2 maps to the string '2'
    2. 1, since '3' maps to integer
    3. 3, since null maps to 0
    4. 3null, since null maps to the string 'null'
    5. 4, since true maps to 1
    6. 0, since false maps to 0 and null to 0
    7. 3undefined, since undefined maps to string 'undefined'
    8. NaN, since '3' become 3 and we can't calculate undefined so it became Not a number

14. Comparison

    1.  true, '2' maps to 2
    2.  false ('2' comes after '12' in string order)
    3.  true, since it is not strict equality so it will be converted to the same type first
    4.  false, because it is different type and uses strict equality
    5.  false, because true maps to 1
    6.  true, because Boolean(2) = true

15. The == converts the variable values to the same type before performing comparison (type coercien). === does not do any type conversion and will return true if it is the same type and values.

16. In separate file
17. It will return [2, 4, 6]. Because the modify array function will call `doSomething` function with every array parameter value, which is [1, 2, 3] and it will be multiplied by 2 and be pushed back to newArr and returned as an array.
18. In separate file
19. 1 4 3 2 (each separated by new line), because the console log 3 will immediately run but the 4 will be printed first, and the 2 will be printed after a second
