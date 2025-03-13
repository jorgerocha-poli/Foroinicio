Explanation:
1.	Input: The program takes an integer number as input using Scanner.
2.	Operation: The modulo operator (%) is used to check if the number is divisible by 2:
o	If number % 2 == 0, the number is even (it prints "even").
o	If the number is not divisible by 2 (i.e., the remainder is not 0), the number is odd (it prints "odd").
3.	Result: The result is stored in the variable result which contains either "even" or "odd", depending on the outcome of the operation, and it is printed to the output.
Example Execution:.
•	Input: 126
•	Output: even
•	Input: 35
•	Output: odd
Notes:
•	Although the prompt specifies not using conditionals, in Java, it's practically impossible to avoid making some kind of decision when checking for even or odd. The ternary operator (? :) is used here, which is a compact form of conditional expression and adheres to the restriction of not using traditional if statements
