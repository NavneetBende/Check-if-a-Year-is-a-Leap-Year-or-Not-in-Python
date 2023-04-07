# Check-if-a-Year-is-a-Leap-Year-or-Not-in-Python

Check if a Year is a Leap Year or Not in Python
Leap-year-or-not-using-python
Check if a Year is a Leap Year or Not in Python
Given an integer input year, the objective of the code is to Check if a Year is a Leap Year or Not in Python Language. To do so  we’ll check if the year input satisfies either of the two conditions of leap year.

Example
Input : 2020
Output : It's a Leap Year.
Check Whether a Year is a Leap Year or Not in Python
Given an integer input as the year, the objective is to Check if a Year is a Leap Year or Not in Python Language. To do so we’ll check each condition mentioned below in the blue box. It either of the conditions is satisfied, the year is a leap year. It’s not otherwise. Here are some methods to check whether or not it’s a leap year

Method 1: Using if-else statements 1
Method 2: Using if-else statements 2
We’ll discuss all the above mentioned methods in detail in the upcoming sections. Before going for the approach read out the blue box below for better understanding of the concept.

Conditions for a Leap Year
Here are the two conditions that any year must satisfy to be called a leap year
1. The year must be perfectly divisible by 400.
2. The number must be divisible by 4 but not by 100.

Related Pages
Greatest of two numbers

Greatest of the Three numbers

Prime number

Prime number within a given range

Sum of digits of a number

Method 1: Using if-else Statements 1
In this method we’ll use the if-else statements to check whether or not the input integer satisfies either of the conditions. To learn more about control statements in python, check out if-else control statements in Python.

Working
For a User Input year we do

Check if the year variable is divisible by 400.
Check if the year variable is divisible only by 4 and not 100.
If the above mentioned conditions are satisfied, prints “Leap Year”, print “Not a Leap Year” otherwise.
Let’s implement the above logic in Python Language.

Python Code
Run
year = 2000
if (year%400 == 0) or (year%4==0 and year%100!=0):
  print("Leap Year")
else:
  print("Not a Leap Year")
Output
Leap Year

Method 2: Using if-else Statements 2
In this method we’ll use the if-else statements to check whether or not the input integer satisfies either of the conditions. This method is a modified and simpler version of the previous method.

Working
For a User Input year we do

The input is stored in an int type variable say year.
year is checked for being a leap year or not with the following condition if( ((year % 4 == 0)&&(year % 100 != 0)) || (year % 400==0) )
If the above condition is true then input is a leap year otherwise input is not a leap year.
Let’s implement the above logic in Python Language.

Python Code
Run
year = 2000
if( ((year % 4 == 0) and (year % 100 != 0)) or (year % 400==0) ):
    print("Leap Year")
else:
    print("Not leap Year")
Output:
Leap Year
Prime Course Trailer

Related Banners
Get PrepInsta Prime & get Access to all 200+ courses offered by PrepInsta in One Subscription

Get Prime
