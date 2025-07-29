PRPGRAM 1
Aim
To print even numbers from 0 to 10 using a for loop.

Tools Used
Programiz

Theory
A for loop iterates from a start value to an end value with a fixed step. By incrementing the loop variable by 2, only even numbers are printed.

Algorithm
1.Start the program.

2.Initialize i to 0.

3.Check if i is less than or equal to 10.

4.Print the value of i.

5.Increment i by 2.

6.Repeat steps 3 to 5 until condition fails.

7.End the program.

Conclusion
The program efficiently prints even numbers from 0 to 10, demonstrating the use of a for loop with a custom increment.

PROGRAM 2
Aim
To print the word "SIT" five times using a for loop.

Tools Used
Programming Language: C++
Programiz

Theory
A for loop repeats a block of code a fixed number of times. Here, the loop runs 5 times, printing "SIT" in each iteration.

Algorithm
1.Start the program.

2.Initialize i to 0.

3.Check if i is less than 5.

4.Print "SIT".

5.Increment i by 1.

6.Repeat steps 3 to 5 until i reaches 5.

7.End the program.

Conclusion
The program demonstrates the use of a for loop to perform repeated output, printing "SIT" exactly five times.

PROGRAM 3
Aim
To print numbers from 1 to 10, skipping the number 5.

Tools Used
Programiz

Theory
The for loop iterates from 1 to 10. The continue statement skips the current iteration when i equals 5, so 5 is not printed.

Algorithm
1.Start the program.

2.Initialize i to 1.

3.Check if i is less than or equal to 10.

4.If i is 5, skip printing and continue to next iteration.

Otherwise, print i.

Increment i by 1.

5.Repeat steps 3 to 6 until condition fails.

6.End the program.

Conclusion
The program uses continue inside a loop to skip a specific value during iteration.


PROGRAM 4
Aim:
To print a right-angled triangle of stars increasing from 1 to 5 rows.

Tools Used:
Programiz

Theory:
A nested for loop prints stars incrementally. The outer loop controls the number of rows, while the inner loop prints stars equal to the current row number.

Algorithm:

1.Initialize rows to 5.

For i from 1 to rows (inclusive):

For j from 1 to i (inclusive), print *.

2.Move to the next line after inner loop finishes.

3.Repeat until all rows are printed.

Pattern:

*
**
***
****
*****
Conclusion:
The program prints a simple right-angled triangle star pattern with increasing stars per row, demonstrating nested loops.



PROGRAM 5
Aim:
To print an inverted right-angled triangle of stars decreasing from 5 to 1 rows.

Tools Used:
Programiz

Theory:
Nested loops print stars decrementally. The outer loop controls the rows from 5 down to 1, and the inner loop prints stars accordingly.

Algorithm:

1.Initialize rows to 5.

2.For i from rows down to 1:

3.For j from 1 to i, print *.

4.Move to the next line after inner loop finishes.

5.Repeat until all rows are printed.

Pattern:
*****
****
***
**
*
Conclusion:
The program prints an inverted right-angled triangle star pattern using nested loops.


PROGRAM 6
Aim:
To print a right-aligned triangle of stars with 5 rows.

Tools Used:
Programiz

Theory:
Two nested loops are used: the first prints spaces to align the stars to the right, and the second prints stars increasing each row.

Algorithm:

1.Initialize rows to 5.

2.For i from 1 to rows:

3.Print rows - i spaces.

4.Print i stars.

5.Move to the next line.

6.Repeat for all rows.

Pattern:
    *
   **
  ***
 ****
*****
Conclusion:
The program demonstrates right-aligned star pattern printing using spaces and nested loops.



PROGRAM 7
Aim:
To print a pyramid star pattern with 5 rows.

Tools Used:
Programiz

Theory:
Each row prints spaces followed by an odd number of stars increasing by 2 every row, forming a symmetrical pyramid.

Algorithm:

1.Initialize rows to 5.

2.For i from 1 to rows:

3.Print rows - i spaces.

4.Print 2 * i - 1 stars.

5.Move to the next line.

6.Repeat until the pyramid is complete.

Pattern:

    *
   ***
  *****
 *******
*********
Conclusion:
The program prints a symmetrical pyramid star pattern using nested loops.



PROGRAM 8
Aim:
To print Floyd’s triangle with consecutive numbers up to 4 rows.

Tools Used:
Programiz

Theory:
Numbers increment consecutively and are printed in increasing counts per row, creating Floyd’s triangle.

Algorithm:

1.Initialize rows to 4 and num to 1.

2.For i from 1 to rows:

3.For j from 1 to i:

4.Print the current number num followed by a space.

5.Increment num.

6.Move to the next line.

7.Repeat until all rows are printed.

Pattern:

1 
2 3 
4 5 6 
7 8 9 10 
Conclusion:
The program generates Floyd’s triangle displaying consecutive numbers in a triangular format.


PROGRAM 9
Aim:
To print numbers from 1 to 20 using a while loop.

Tools Used:
Programiz

Theory:
The while loop executes a block of code repeatedly as long as the given condition is true. Here, it prints numbers starting from 1 and increments until 20.

Algorithm:

1.Initialize num to 1.

2.While num is less than or equal to 20:

3.Print the current value of num.

4.Increment num by 1.

5.End the loop when num exceeds 20.


Conclusion:
The program demonstrates the use of a while loop to print consecutive numbers from 1 to 20.


PROGRAM 10
Aim:
To verify a user-entered password against a predefined password using character-by-character comparison in a while loop.

Tools Used:
Programiz

Theory:
String comparison can be done by checking each character in sequence. If any character differs, the password is invalid. The program first checks if the lengths are equal to avoid unnecessary comparison.

Algorithm:

1.Store the original password "Harry".

2.Input a password from the user.

3.Check if the length of user input matches the original password length:

4.If not, deny access immediately.

5.Initialize i to 0 and isMatch to true.

6.Use a while loop to compare characters at each position:

7.If any character differs, set isMatch to false and break loop.

8.After the loop, if isMatch is true, print "Access granted!"
9.Otherwise, print "Access denied. Wrong password."

Output Example:

Input: Harry
Output: Access granted!

Input: harry
Output: Access denied. Wrong password.

Input: Harryy
Output: Access denied. Wrong password length.

Conclusion:
The program demonstrates manual string comparison and control flow to validate password input securely.



