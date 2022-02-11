# Numeral Systems

1. Write a program that converts a number in base B (`2 <= B <= 36`) to a number in base 10.

   You may assume that the returned number is less than 2 billions.
   
   Write the following function: `func toBase10(num string, fromBase int) int`. Write tests for the function.

   Test examples:
 
   ```go
   {num: "123", fromBase: 10, want: 123},
   {num: "111101", fromBase: 2, want: 61},
   {num: "ABCD", fromBase: 16, want: 43981},
   ```

2. Write a program that converts a number in base 10 to a number in a given base B (`2 <= B <= 36`).

   Write the following function: `func fromBase10(num int, toBase int) string`. Write tests for the function.
   
      Test examples:
 
   ```go
   {num: 123, toBase: 10, want: "123"},
   {num: 61, toBase: 2, want: "111101"},
   {num: 43981, toBase: 16, want: "ABCD"},
   ```
