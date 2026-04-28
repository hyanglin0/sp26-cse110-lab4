1. `3` will be printed, because the variable `i` was declared with `var`, which means that it is visible inside the entire function `discountPrices`.
2. `150` will be printed, because the variable `discountedPrice` was declared with `var`, which means that it is visible inside the entire function `discountPrices`.
3. `150` will be printed, because the variable `finalPrice` was modified to be 300 discounted by 50% and rounded to the nearest hundredth in the last iteration of the `for` loop.
4. This function will return `[50, 100, 150]`, because the function call returns an array of prices that are discounted by 50% and rounded to the nearest hundredth.
5. The code causes an error, because the variable `i` was declared with `let`, which means that is only visible inside the `for` loop.
6. The code causes an error, because the variable `discountedPrice` was declared with `let`, which means that is only visible inside the `for` loop.
7. `150` will be printed, because the variable `finalPrice` was modified to be 300 discounted by 50% and rounded to the nearest hundredth in the last iteration of the `for` loop.
8. This function will return `[50, 100, 150]`, because the function call returns an array of prices that are discounted by 50% and rounded to the nearest hundredth.
9. The code causes an error, because the variable `i` was declared with `let`, which means that is only visible inside the `for` loop.
10. `3` will be printed, because the length of the array `[100, 200, 300]` is 3.
11. This function will return `[50, 100, 150]`, because the function call returns an array of prices that are discounted by 50%.
12. 
  - A. `student.name`
  - B. `student["Grad Year"]`
  - C. `student.greeting()`
  - D. `student["Favorite Teacher"].name`
  - E. `student.courseLoad[0]`
13. 
  - A. `'32'`; 2 is mapped to '2'.
  - B. `1`; '3' is mapped to 3.
  - C. `3`; null is mapped to 0.
  - D. `'3null'`; null is mapped to 'null'.
  - E. `4`; true is mapped to 1.
  - F. `0`; false and null are mapped to 0.
  - G. `'3undefined'`; undefined is mapped to 'undefined'.
  - H. `NaN`; undefined is mapped to NaN.
14. 
  - A. `true`; '2' is mapped to 2.
  - B. `false`; '2' is greater than '1'.
  - C. `true`; '2' is mapped to 2.
  - D. `false`; the types are different
  - E. `false`; true is mapped to 1.
  - F. `true`; Boolean(2) is true.
15. When comparing values of different types, the == operator converts the values to numbers first before making the comparison, whereas the === operator returns false since it checks the equality without type conversion.
16. See `part2-question16.js`.
17. `[2, 4, 6]`; `modifyArray` iterates through the array `[1, 2, 3]`, and for each element, `doSomething` is called to double the element's value, which is then pushed to `newArr`.
18. See `part2-question18.js`.
19. 
  - `1`
  - `4`
  - `3`
  - `2`