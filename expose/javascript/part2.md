# Part 2: A Little More of a Challenge

1. Line 12 will print `3` since the length of prices is 3, the var `i` will start from 0-2 in the for loop. In the last iteration of for loop, `i` = 2, 2++ at the end will become `3`.
2. Line 13 will print `150` since the last update of var `discountedPrice` is at the last iteration of for loop, which did `prices[2] * 0.5` = 300 * 0.5 = 150.
3. Line 14 will print `150` since it rounds the `discountedPrice` which is 150 round to 150.
4. It will return something like `[50, 100, 150]` since the function will calculate each element in `prices` with `discount` and store them into the return var `discounted`.
5. 
