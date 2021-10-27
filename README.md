# 3u-loops

Loops
---

**For the following programs, leave the prompt in the input function empty.**

---
Create a python file called **loops1.py** and upload it to this repo. At the beginning of the python file, write a description of the program(s) in a comment. 

Use a loop to write a program that reads a word from the user and outputs whether the word is a palindrome. The outputs will either be "palindrome" or "not a palindrome". 

A palindrome is a word that is identical forward and backward. For example ‘anna’ and ‘level’ are palindromes.


&nbsp;&nbsp; **Sample Input 1**

    level

&nbsp;&nbsp; **Sample Output 1**

    palindrome

&nbsp;&nbsp; **Sample Input 2**

    lead

&nbsp;&nbsp; **Sample Output 2**

    not a palindrome
    
---
Create a python file called **loops2.py** and upload it to this repo. At the beginning of the python file, write a description of the program(s) in a comment. 

Write a program that takes in a number N that represents a number of students. Each of the next pair of inputs represents a name and a mark. Your program outputs the name of the student with the highest mark. If there are multiple students with the same mark, it outputs all of their names separated with a comma followed by a space. Make sure there is no extra white space at the end of your output.


&nbsp;&nbsp; **Sample Input 1**

    5
    Tanya
    89
    Imad
    90
    Michael
    90
    Amreen
    90
    Sean
    89

&nbsp;&nbsp; **Sample Output 1**

    Imad, Michael, Amreen

&nbsp;&nbsp; **Sample Input 2**

    5
    Tanya
    89
    Imad
    91
    Michael
    90
    Amreen
    90
    Sean
    89
    
&nbsp;&nbsp; **Sample Output 2**

    Imad
    
---

Create a python file called **loops3.py** and upload it to this repo. At the beginning of the python file, write a description of the program(s) in a comment. 

Write a program that reads an integer between 1 and 50 from the user and outputs all the factors of that integer - one per line.
 
Hint: Loop over all the numbers less than or equal to the input number. 

&nbsp;&nbsp; **Sample Input 1**

    27

&nbsp;&nbsp; **Sample Output 1**

    1
    3
    9
    27

&nbsp;&nbsp; **Sample Input 2**

    1

&nbsp;&nbsp; **Sample Output 2**

    1
    
&nbsp;&nbsp; **Sample Input 3**

    11

&nbsp;&nbsp; **Sample Output 3**

    1
    11
    
    ---

Create a python file called **loops4.py** and upload it to this repo. At the beginning of the python file, write a description of the program(s) in a comment. 

Write a program that reads a number representing the number of grades to be entered and letter grades from the user and displays their grade point average rounded to 2 decimal places.

|A+ |A  |A- |B+ |B  |B- |C+ |C  |C- |D+ |D  |F  |
|---|---|---|---|---|---|---|---|---|---|---|---|
|4.0|4.0|3.7|3.3|3.0|2.7|2.3|2.0|1.7|1.3|1.0|0.0|



&nbsp;&nbsp; **Sample Input**

    
    5
    A+
    A
    B-
    C-
    A-

&nbsp;&nbsp; **Sample Output**

    3.22
    
---
Create a python file called **loops5.py** and upload it to this repo. At the beginning of the python file, write a description of the program(s) in a comment. 

Write a program that reads a string from the user a number to shift the string by and then implements the Caesar cipher to encode the string. Your program should display the encoded string. The program should be case sensitive. Non - alpha characters remain the same.

Using the cipher every letter in the original message is shifted down a fixed number of places. For example, if the shift is 3 then A becomes D, B becomes E and so on.  The last three letters are wrapped around the beginning: X becomes A, Y becomes B and Z becomes C.

The following string method might be useful:

**s.index(char) returns the index of char in s**

&nbsp;&nbsp; **Sample Input 1**

    Secret Message
    3

&nbsp;&nbsp; **Sample Output 1**

    Vhfuhw Phvvdjh

&nbsp;&nbsp; **Sample Input 2**

    Hello World!
    4

&nbsp;&nbsp; **Sample Output 2**

    Lipps Asvph!
    
---
Create a python file called **loops6.py** and upload it to this repo. At the beginning of the python file, write a description of the program(s) in a comment. 

Write a program that reads a number from 3 - 18 from the user and determines the number of rolls of three dice that sum is that number.

&nbsp;&nbsp; **Sample Input 1**

    11
   
&nbsp;&nbsp; **Sample Output 1**

    27

&nbsp;&nbsp; **Sample Input 2**

    16

&nbsp;&nbsp; **Sample Output 2**

    6
