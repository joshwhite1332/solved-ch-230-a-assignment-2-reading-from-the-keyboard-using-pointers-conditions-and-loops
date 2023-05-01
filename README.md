Download Link: https://assignmentchef.com/product/solved-ch-230-a-assignment-2-reading-from-the-keyboard-using-pointers-conditions-and-loops
<br>
<h1>Problem 2.1 <em>Reading from the keyboard                                                                     </em></h1>

Write a program which does the following:

<ol>

 <li>reads two doubles from the keyboard,</li>

 <li>prints the sum of the two doubles,</li>

 <li>prints the difference of the two doubles (first minus second),</li>

 <li>prints the square of the first double,</li>

 <li>reads two integers from the keyboard,</li>

 <li>computes the sum and product of the two integers,</li>

 <li>prints the sum and product of the integers,</li>

 <li>reads two chars from the keyboard,</li>

 <li>computes the sum and product of the two chars,</li>

 <li>prints the sum and product of the chars as decimal values and as chars.</li>

</ol>

<em>You can assume that the input will be correct.</em>

<em>Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<table width="537">

 <tbody>

  <tr>

   <td width="290"><strong>Testcase 2.1: input</strong>1.23.625()</td>

   <td width="247"><strong>Testcase 2.1: output</strong>sum of doubles=4.800000 difference of doubles=-2.400000 square=1.440000 sum of integers=7 product of integers=10 sum of chars=81</td>

  </tr>

 </tbody>

</table>

product of chars=1640 sum of chars=Q product of chars=h

<h1>Problem 2.2 <em>Decimal, octal and hexadecimal numbers                                              </em>(</h1>

Write a program which does the following:

<ol>

 <li>reads a char from the keyboard,</li>

 <li>and prints the char as character as well as in decimal, octal and hexadecimal notation.</li>

</ol>

<em>You can assume that the input will be correct.</em>

<em>Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<table width="564">

 <tbody>

  <tr>

   <td width="290"><strong>Testcase 2.2: input</strong>{</td>

   <td width="274"><strong>Testcase 2.2: output</strong>character={ decimal=123 octal=173 hexadecimal=7b</td>

  </tr>

  <tr>

   <td width="290"><strong>Problem 2.3 </strong><em>Time calculation</em></td>

   <td width="274"></td>

  </tr>

 </tbody>

</table>

<h2>Language: C</h2>

Write a program where you can enter integer numbers for weeks, days and hours as input from the keyboard. Your program should compute and output by printing on the screen the total number of hours.

<em>You can assume that the input will be correct.</em>

<h1>Problem 2.4 <em>Area computations                                                                           </em>(1 point)</h1>

<h2>Due by Monday, September 20<sup>th</sup>, 23:00       Graded automatically with testcases only Language: C</h2>

Write a program that reads from the keyboard three float values for the variables a, b and h. Compute and print on the screen the areas of: the square with the side a, the rectangle with the length a and the width b, a triangle with the base a and the height h, and a trapezoid with the bases a, b and the height h.

<em>You can assume that the input will be correct.</em>

<em>Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<h1>Testcase 2.4: inputTestcase 2.4: output</h1>

10square area=100.000000

14.5rectangle area=145.000000

5triangle area=25.000000 trapezoid area=61.250000

<h2>Problem 2.5 <em>Pointers and their content                                                                       </em></h2>

Write a program which reads an integer variable a from the keyboard and prints the value on the screen. Then declare and initialize a pointer ptr_a pointing to a, print the address contained in the pointer variable on the screen, increase the value of a by 5 by using the pointer variable and print the modified value and the address of the variable on the screen as well. <em>You can safely assume that the input will be correct.</em>

<table width="347">

 <tbody>

  <tr>

   <td width="347"><strong>Problem 2.6 </strong><em>Multiple pointers to same data</em></td>

  </tr>

 </tbody>

</table>

Write a program which reads two double variables x and y from the keyboard. Then declare and initilize three pointers ptr_one, ptr_two and ptr_three such that ptr_one and ptr_two will both point to the variable x and ptr_three will point to y. By using printf show that ptr_one and ptr_two contain the same memory address and ptr_three contains a different address.

<em>You can assume that the input will be correct.</em>

<table width="284">

 <tbody>

  <tr>

   <td width="284"><strong>Problem 2.7 </strong><em>Infinite loop by bad coding</em></td>

  </tr>

 </tbody>

</table>

The program below prints

i is 8 i is 8

…

until you stop the execution by pressing Ctrl-C. Fix the program such that it prints 8, 7, 6, 5 and 4 as values for i.

#include &lt;stdio.h&gt; int main()

{

int i = 8; while (i &gt;= 4) printf(“i is %d
”, i); i–;

printf(“That’s it.
”); return 0;

}

<table width="564">

 <tbody>

  <tr>

   <td width="284"><strong>Problem 2.8 </strong><em>Divisible by </em>2 <em>and </em>7<em>?</em></td>

   <td width="280"></td>

  </tr>

 </tbody>

</table>

<h3>Language: C</h3>

Write a program, where you can enter an integer from the keyboard. Determine whether the number is divisible by both 2 and 7. Then either print on the screen

“The number is divisible by 2 and 7” or

“The number is NOT divisible by 2 and 7”.

<em>You can safely assume that the input will be valid.</em>

<em>Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<h1>Testcase 2.8: inputTestcase 2.8: output</h1>

56The number is divisible by 2 and 7

<h2>Problem 2.9 <em>Categorization of characters                                                                   </em></h2>

Write a program where you can enter a character from the keyboard. Then determine whether the character is a digit or a letter or some other symbol and print a corresponding message on the screen.

<em>You can safely assume that the input will be valid.</em>

<em>Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<table width="564">

 <tbody>

  <tr>

   <td width="290"><strong>Testcase 2.9: input </strong>!</td>

   <td width="274"><strong>Testcase 2.9: output</strong>! is some other symbol</td>

  </tr>

  <tr>

   <td width="290"><strong>Problem 2.10 </strong><em>Days and hours</em></td>

   <td width="274"></td>

  </tr>

 </tbody>

</table>

<h3>Language: C</h3>

Write a program where you can enter an integer n from the keyboard. Then a conversion table for 1 to n days should be printed on the screen as in the example below. Make sure that the integer value you entered for n is valid (positive and non-zero). If an invalid integer n was entered then repeat the entering until a valid value will be entered. <em>Use a while loop in your solution.</em>

<ul>

 <li>day = 24 hours</li>

 <li>days = 48 hours</li>

 <li>days = 72 hours</li>

</ul>