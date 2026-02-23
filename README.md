# practical7

Experiment 7: Study of Looping Statements in Python

Aim:

To study and implement different looping statements in Python (while and for loops) to perform repetitive tasks such as printing sequences, calculating factorial, and generating Fibonacci series.

⸻

Theory:

Loops are control flow statements used to execute a block of code repeatedly until a specified condition is satisfied.

In Python, major types of loops are:
1. While Loop
• Executes a block of code as long as the given condition is true.
• Used when the number of iterations depends on a condition.
  Working of While Loop:
1. The condition is evaluated.
2. If the condition is True, the statements inside the loop are executed.
3. After execution, the condition is checked again.
4. This process continues until the condition becomes False.
5. When the condition becomes False, the control exits the loop.

Loops help reduce redundancy, improve efficiency, and simplify complex repetitive tasks such as mathematical computations and pattern generation.

⸻

Algorithm:

⸻

Experiment : Print Numbers from 1 to 5
1. Start
2. Initialize variable i = 1
3. While i <= 5
4. Print i
5. Increment i by 1
6. Stop

⸻

Experiment : Print Numbers from 1 to n
1. Start
2. Input number n
3. Initialize i = 1
4. While i <= n
5. Print i
6. Increment i
7. Stop

⸻

Experiment : Factorial of a Number
1. Start
2. Input number n
3. Initialize fact = 1
4. While n > 0
5. Multiply fact = fact × n
6. Decrement n by 1
7. Display factorial
8. Stop

⸻

Experiment : Fibonacci Series
1. Start
2. Input number of terms n
3. Initialize a = 0, b = 1
4. Print a and b
5. Repeat from 3rd term to n
6. Compute c = a + b
7. Print c
8. Update a = b, b = c
9. Stop

⸻



Algorithm: Reverse of a Number (Using While Loop)
1. Start
2. Input number n
3. Initialize rev = 0
4. While n > 0
5. Find remainder r = n % 10
6. Update rev = (rev × 10) + r
7. Update n = n // 10
8. Repeat steps 4–7 until n becomes 0
9. Display rev
10. Stop

⸻

Algorithm: Palindrome Number (Using While Loop)
1. Start
2. Input number n
3. Store original number in temp = n
4. Initialize rev = 0
5. While n > 0
6. Find remainder r = n % 10
7. Update rev = (rev × 10) + r
8. Update n = n // 10
9. After loop, compare rev with temp
10. If rev == temp, print “Number is Palindrome”
11. Else, print “Number is Not Palindrome”
12. Stop



Algorithm: Choose a Number from a List
1. Start
2. Create a list of numbers (for example: L = [10, 20, 30, 40, 50])
3. Input a number n from the user
4. Initialize a flag variable found = False
5. For each element in the list
6. If element equals n
7. Set found = True
8. Break the loop
9. After loop, check the value of found
10. If found == True, print “Number found in the list”
11. Else, print “Number not found in the list”
12. Stop



Experiment : Sum of First n Natural Numbers
1. Start
2. Input number n
3. Initialize sum = 0, i = 1
4. While i <= n
5. Add i to sum
6. Increment i
7. Display sum
8. Stop



⸻

Overall Conclusion

Thus, the experiment was successfully completed. We studied and implemented looping statements in Python using both while and for loops. We learned how loops help in performing repetitive tasks efficiently, such as generating number sequences, computing factorials, finding sums, and producing Fibonacci series. Looping structures make programs shorter, clearer, and more efficient by eliminating repetitive code.

⸻
