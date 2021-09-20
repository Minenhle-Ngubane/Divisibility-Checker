## Divisibility Checker (Divisibility by 3)

A common test for divisibility by 3 is to add the digits of an integer. If the resulting sum is divisible by 3 then so is the original number. Program this test.

To do this, first write a function **reduce(number)** that returns the sum of the digits of number. **The sum returned must be** < **20** i.e. if the sum is >= 20, the function must add the digits of the resulting sum. **It should repeat this procedure until the sum is < 20**.

Use this function in a program that inputs a number from the user and prints out whether or not the number is divisible by 3.