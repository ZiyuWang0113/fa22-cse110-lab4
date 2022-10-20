# Part 2: A Little More of a Challenge

1. Line 12 will print `3` since the length of prices is 3, the var `i` will start from 0-2 in the for loop. In the last iteration of for loop, `i` = 2, 2++ at the end will become `3`.
2. Line 13 will print `150` since the last update of var `discountedPrice` is at the last iteration of for loop, which did `prices[2] * 0.5` = 300 * 0.5 = 150.
3. Line 14 will print `150` since it rounds the `discountedPrice` which is 150 round to 150.
4. It will return something like `[50, 100, 150]` since the function will calculate each element in `prices` with `discount` and store them into the return var `discounted`. It is a `var` type.
5. Line 12 will have error: `ReferenceError` since the scope of let `i` is only in for loop block, the access outside block is error.
6. Line 13 will have error: `ReferenceError` similar to #5 that let `discountedPrice` is in for loop block.
7. Line 14 will print `150` since let `finalPrice` is declared in the same block scope, so it is accessible.
8. It will return something like `[50, 100, 150]` since the function will calculate each element in `prices` with `discount` and store them into the return var `discounted`. However, unlike #4, it is a `let` type.
9. Line 11 will have error: `ReferenceError` since `i` is let which is only in for loop block.
10. Line 12 will print `3` since const `length` is in the function scope which is not changed, the log will output `length`.
11. It will return something like `[50, 100, 150]` since the function will calculate each element in `prices` with `discount` and store them into the return var `discounted`. However, unlike #8, it is a `const` type.
12. `student.name`; `student['Grad Year']`; `student.greeting()`; `student['Favorite Teacher].name`; `student.courseLoad[0]`
13. A - '32', interger map to exact string representation

    B - 1, numeric conversion happens in mathematical
    
    C - 3, numeric conversion happens in mathematical and null maps to 0
    
    D - '3null', string conversion happens when we need string form of value and null becomes `null`
    
    E - 4, numeric conversion happens in mathematical and true maps to 1
    
    F - 0, numeric conversion happens in mathematical and false, null map to 0
    
    G - '3undefined`, string conversion and undefined maps to `undefined`
    
    H - NaN, numeric conversion happens in mathematical and undefined maps to NaN
14. A - true, '2' maps to 2

    B - false, string '2' comes later that '1' so '2' > '1'
    
    C - true, 2 == 2 after '2' maps to 2
    
    D - false, types are different
    
    E - false, true maps to 1
    
    F - true, Boolean(2) is true since 2 != 0
15. `==` can convert types before comparing but `===` do not convert, so `===` will return always false when types are different.
16. ``` 
    for(let property in statistics){
        if(property[0] == 'r' || statistics[property] % 2 == 1){
            console.log(statistics[property]);
        }
    }
    ```
17. The result should be ` [2, 4, 6]` as the `newArr`. The process is: call `modifyArray`, pass in two parameters, in the for-loop, call the `callback` function to times 2 for each `array[i]` and push it into the `newArr`. So after the for-loop, the `newArr` will be double of `[1,2,3]`.
18. I think there are different ways: 1. while(true) and put codes in the while loop 2. use `setInterval`.
19. Output is:
    ```
    1
    4
    3
    2 (delay 1 second)
    ```
    1,4,3 output at the same time with 2 at delay 1000 milliseconds that the timer wait before the function is executed.
