## How to convert between binary and decimal numbers

## By Dylan Reeves

### The purpose of this tutorial is explain how to convert between a binary number and a decimal number for those that are needing to know how binary numbers work and how they are related.

### What are binary numbers?
* Numbers that use a base of two
* Consist of only 1s and 0s
* In most cases, represent a bit, in which the highest number is 256, or 8 individual numbers.
* From right to left, each number represents 2 to the power of a number starting with 0. For example, in the binary number 10001011, the number furtherst to the right is 2^0, which is 1, the number next to that is 2^1, which is 1. The number on the farleft is 2^7, which is 128.

### Decimal to binary
In this guide, we will teach you how to convert a decimal number to a binary number. Don't worry, there are a couple of ways. Let's start with the more well know way.
* Divide the number by 2.
* Note the remainder of the number.
* Repeat until the quotient is 0.
* Write the remainders, but with the last remainder you received being the first number, and the first remainder being the last.
Another way to do it is to use your knowledge of the powers of 2 to substract from the number. Note, this works better with smaller numbers, or numbers smaller than 256.
* Let's use 94 as an example.
* With our knowledge of powers of 2, we know that 2^6 is 64.
* 94 - 64 = 30
* Write a 1 down for the answer. This is the start of the binary number.
* Now, 2^5 is 32, but that would result in a negative number, so we can't do it.
* Write down 0 next to the 1. So far, the binary number is 10, and the decimal is still 30.
* The next power is 2^4, which is 16. 30 - 16 = 14. Now the binary is 101.
* Next power: 2^3, which is 8. 14 - 8 = 6. Now the binary is 1011.
* Next power: 2^2, 4. 6 - 4 = 2. Binary is 10111.
* Next power: 2^1, 2. 2 - 2 = 0. Binary is 101111.
* And because we can't subtract 1 from 0, the answer is 1011110.

### Binary to decimal
In this guide, we will teach you how to convert a binary number to decimal. There are two ways to do this: doubing and positional. We will use the number 10011011 as example.
* Doubling - The process of using a tracker that is doubled everytime to keep track of your numbers:
  * You will start with 10011011 and the number 0. 0 will be your final answer in the end.
  * The equation for this is (sum x 2 + position number) with sum being the current 0, and position number being the number at the current spot on the binary number.
  * We will start at the left. Since the far left has a one, we will have 0 x 2 + 1 = 1. Remember that.
  * Next position has a zero. The number will now be 1 x 2 + 0 = 2.
  * Next is also a zero. The number will now be 2 x 2 + 0 = 4.
  * Next is a one. That means something is now being added again, so the number will now be 4 x 2 + 1 = 9.
  * Next has a one. Number is 9 x 2 + 1 = 19.
  * Next is a zero. Number is now 19 x 2 + 0 = 38.
  * Next is a one. Number is now 38 x 2 + 1 = 77.
  * Finally, the final number is one. That means the final answer is 77 x 2 + 1 = 155.
  
* Positional - The process of correlating the position of the binary number to the powers of 2:
  * Starting with 10011011 again, it's easier to make a chart of this, as this can get a little hard to keep track of.
  * We know that the number at the furthest of the number is 2^7, which means the number is 128.
  * We can then repeat this process for all positions with a 1.
  * The numbers we should receive are 128, 16, 8, 2, and 1.
  * Add them all together, and you should still receive 155.
  
##Conclusion
Binary numbers can be confusing for many. This guide was created with the purpose of making the process of learning them easier for oneself, and can be applied into the future.
Note that this does not account for negative binary numbers.

This is a test line.
