CRT Day 1 - Python Basics 📚
Day 1 of CRT (Campus Recruitment Training) focused on learning Python fundamentals and developing logical thinking through basic programming problems. We covered variables, data types, input and output operations, type conversion, operators, conditional statements, and loops. We also practiced mathematical and logical problems to improve our problem-solving skills.
📚 Topics Covered
- Introduction to Python
- Variables and Data Types
- Input and Output ("input()", "print()")
- Type Conversion ("int()", "float()")
- Operators
- Conditional Statements ("if", "elif", "else")
- "for" Loop
- "range()" Function
- Output Formatting using f-strings
- 💻 Programs Practiced
1. Even or Odd Number
2. Positive, Negative, or Zero
3. Largest of Two or Three Numbers
4. Prime Number Checking
5. Prime Numbers in a Range
6. Even Number Output Formatting
7. Reverse number
🧠 Prime Number Logic
A prime number is a number greater than 1 that has exactly two factors: 1 and itself. To check whether a number is prime, we check if it is divisible by any number from 2 to "n-1". If a divisor is found, the number is not prime. Otherwise, it is prime.
n = int(input("Enter a number: "))
if n < 2:
    print("Not Prime")
else:
    for i in range(2, n):
        if n % i == 0:
            print("Not Prime")
            break
    else:
        print("Prime")
Example Output
Enter a number: 7
Prime
🎯 Learning Outcomes
- Learned the fundamentals of Python programming.
- Understood variables, data types, and type conversion.
- Practiced conditional statements and loops.
- Learned to solve basic mathematical and logical problems.
- Improved problem-solving and programming skills.
- Understood how to format output using f-strings.
🚀 Conclusion
CRT Day 1 helped me strengthen my foundation in Python programming and logical problem-solving. The practice problems provided a better understanding of conditional statements, loops, and mathematical operations, which will be useful for coding practice and future placement preparation.
Skills: Python | Programming Basics | Loops | Conditional Statements | Problem Solving
