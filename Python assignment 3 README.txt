Python Fundamentals: Control Flow and Functions
A collection of three console-based Python programs demonstrating core programming constructs: iterative control flow (while, for), flow-control statements (break, continue, loop else), and modular design with functions.
1. Number Guessing Game (while loop and control statements)
The computer picks a random number from 1 to 10, and the player gets 3 attempts to guess it. The program gives "too high" or "too low" hints, rejects out-of-range guesses without counting them, and ends the game on a correct guess or when attempts run out. It uses break, continue, and the loop else clause.
2. Multiplication Table Generator (for loop)
The user enters a number, and the program prints its multiplication table from 1 to 10, one line per multiple, using for and range().
3. BMI Calculator (functions)
The user enters weight in kilograms and height in meters. A function, calculate_bmi(weight, height), applies the formula weight / height² and returns the result, which is printed to two decimal places.
Skills practiced
• Repeating tasks with loops (while for "until something happens", for for "a set number of times")
• Controlling loop behavior with break, continue, and else
• Making decisions with if / elif / else
• Taking user input and converting types with int() and float()
• Writing reusable functions with parameters and return values
• Formatting output with f-strings
Development Approach
1. Requirement analysis: Broke each problem statement into inputs, processing steps, and expected outputs, using the sample output as the acceptance criteria.
2. Design: Outlined the logic in plain-language steps before writing code (for example, the order of the range check, attempt counter, and comparison in the guessing game).
3. Implementation: Built each program incrementally, running it after each addition rather than writing everything at once.
4. Validation: Compared program output against the sample outputs in the assignment brief and tested edge cases such as out-of-range guesses and running out of attempts.
5. Debugging: Diagnosed and fixed issues using Python's error messages and by tracing the program flow line by line (see Challenges and Learnings).assignmentassignment

