# Average-of-the-N-Numbers

Input: 4

Output: 2.5

Question: Average of the N Numbers

Write a program that reads a number N and prints the average of N numbers from 1.

The average of N numbers from 1 can be calculated as,

Average = Sum of N numbers from 1 / Count of numbers (N)

Example: If N = 3, the average of 3 numbers from 1
Average = (1 + 2 + 3) / 3 = 2.0

Approach: 
Read the input number N.

Calculate the sum of N numbers from 1.

Calculate the average by dividing the sum by N.

Print the average.

Step-by-Step Explanation

Step 1: Read the input number

Read the input value representing the number N. We can use the input() function to read the input and int() to convert it into an integer.

PYTHON
Step 2: Calculate the sum of N numbers

Initialize two variables, sum_of_numbers and counter, to 0.

Use a while loop to calculate the sum of N numbers from 1. The loop should run until the counter is less than number.

Inside the loop, increment the counter by 1.
Add the value of counter to sum_of_numbers.

Step 3: Calculate the average and print the result

Calculate the average by dividing the sum_of_numbers by number.

Print the average.
