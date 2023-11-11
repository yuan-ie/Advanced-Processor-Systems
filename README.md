# ece_4612
Advanced Processor Systems

## Project 1:

#### _Task 1:_
> Write MIPS code to copy the content of array Y which contains your full name, to array X.

To complete this task:
1. create a sring with my full name and store that into array Y.
2. copy character by character of the array and store that into array X.
3. print out both the contents of array Y and X to check if they match.

#### _Task 2:_
> Find the factorial of a number.

Requirements:
- Display in the I/O window the prompt “Enter a number to find factorial: “
- Take a number from the I/O window
- Calculate the factorial of the number
- Display the result to the I/O window

#### _Task 3:_
> Print a diamond shape to I/O window.

Requirements:
- take an integer input from I/O window
- display in the I/O window a diamond whose side containing the number of stars (*) specified by users

To complete this task:
1. take the input (integer) from the user
2. divide it into four parts:
  1. first part (one star):
     a. the number of space characters is __input - [line #]__. print the spaces and a star right after.
  3. second part (loop with two stars):
       for every line after line 1 to line [input]:
      - the number of spaces before the first star is decremented each time.
      - print a star.
      - the number of spaces after the first star is increased by 2 (starting from one space of the first iteration)
      - print a star.
  4. third part (loop with two stars):
       for every line after line [input] to line [2*input - 1]:
      - the number of spaces before the first star is incremented each time.
      - print a star.
      - the number of spaces after the first star is increased by 2 (starting from one space of the first iteration)
      - print a star.
  5. fourth part: same as first part.
