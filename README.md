Download Link: https://assignmentchef.com/product/solved-cs135-project-5
<br>
<u>Project [5]: Arrays</u>

<h1>Project Goals</h1>

The goals of this project are to:

<ol>

 <li>Get students familiar with the usage of 1D arrays</li>

 <li>Get students familiar with the usage of 2D arrays</li>

</ol>




<strong><u>Important Notes:</u> </strong>

<ol>

 <li><strong>Formatting: </strong>Make sure that you follow the precise recommendations for the output content and formatting: for example do not change the text in the first problem from “Enter the size of the array: ” to “Enter array size: ”. Your assignment will auto-graded and any changes in formatting will result in a loss in the grade.</li>

 <li><strong>Comments:</strong> Header comments are required on all files and recommended for the rest of the program. Points will be deducted if no header comments are included.</li>

 <li><strong>Restriction: </strong>The use of goto statements anywhere within this program is prohibited. Points will be deducted if goto is used.</li>

</ol>




<h1>Problem 1</h1>

Write a program that asks the user to enter an NxM dimensional array containing single digit values (only the digits between 0 and 9) and counts the number of times each one of the 10 digits appears in the array. This program should:

<ul>

 <li>Prompt the user to enter the sizes (number of rows and number of columns) of the array, and read in the dimensions given by the user</li>

 <li>Prompt the user to enter the array row-by-row and read in each value (separated by spaces)</li>

 <li>Display the total number of times each digit appears in the array</li>

 <li>Display the 1D array containing the counts of each digit in one line</li>

 <li>Display the 2D array that the user entered</li>

</ul>

The program should function as follows (items underlined are to be entered by the user):




This program counts occurrences of digits 0 through 9 in an NxM array.

Enter the size of the array (Row Column): 2 6

Enter row 0: 0 1 2 3 4 5

Enter row 1: 0 1 6 7 8 9 Total counts for each digit:

Digit 0 occurs 2 times

Digit 1 occurs 2 times

Digit 2 occurs 1 times

Digit 3 occurs 1 times

Digit 4 occurs 1 times

Digit 5 occurs 1 times

Digit 6 occurs 1 times

Digit 7 occurs 1 times

Digit 8 occurs 1 times

Digit 9 occurs 1 times

The digit counts directly from the 1D array:

2 2 1 1 1 1 1 1 1 1

The original 2D array entered by the user:

0 1 2 3 4 5

0 1 6 7 8 9




<strong>Note: </strong>

<ul>

 <li>The counts for each digit must be stored in a single 1D array and cannot be stored in 10 different separate variables.</li>

</ul>




Save your program as arrays.c





