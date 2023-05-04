Download Link: https://assignmentchef.com/product/solved-csci-3070u-analysis-and-design-of-algorithms
<br>



<h1>Part 1</h1>

Find upper bounds, O(n) notation, for the following recurrences.  Use the Equation editor in MS Word in order to ensure that your answers are readable, except for recursion tree where I’d recommend you create an image like in the week 2 slides.  Show your work.  Be sure to solve at least one of the problems using each of recursion tree, substitution, and master method.

<ol>

 <li>T(n) = 2T(n/2) + n/log n</li>

 <li>T(n) = 7T(n/2) + n<sup>2</sup></li>

 <li>T(n) = T(n/2) + T(n/4) + T(n/8) + n</li>

 <li>T(n) = 2T(n/4) + √n</li>

</ol>




<h1>Part 2</h1>

Rank the following functions by their order of growth.  Be sure to put similar functions into the same category (f and g are in the same category iff f(n) = Θ(g(n))).  The result should be a table.  The first column should be the category (and will span multiple answers if there is more than one function in that category).

The second column should be the function itself.  You do not need to justify your answers for this question.




<table width="260">

 <tbody>

  <tr>

   <td width="130">n<sup>2</sup></td>

   <td width="130">3n<sup>2</sup>+7n+15</td>

  </tr>

  <tr>

   <td width="130">2log<sub>2</sub>n</td>

   <td width="130">log10 n</td>

  </tr>

  <tr>

   <td width="130">n<sup>3</sup>-log n</td>

   <td width="130">4<sup>n</sup></td>

  </tr>

  <tr>

   <td width="130">n<sup>71</sup>+5<sup>n</sup> +17n</td>

   <td width="130">18n</td>

  </tr>

  <tr>

   <td width="130">2<sup>n</sup></td>

   <td width="130">3 log2 n</td>

  </tr>

  <tr>

   <td width="130">√n<sup>3</sup></td>

   <td width="130">n!</td>

  </tr>

  <tr>

   <td width="130">¾n<sup>4</sup></td>

   <td width="130">n<sup>3</sup></td>

  </tr>

 </tbody>

</table>

<h1>Part 3</h1>

Using divide and conquer, create an algorithm to solve the problem that follows.  You can use C, C++, Java, or Python to solve this problem (ask the instructor if you have another programming language in mind).  Include the asymptotic upper bound for your algorithm in your response (including the cost of subdivision and combining the results).

<em>You have a long string containing many characters (such as this paragraph), and you want to search for a substring within this string.  For example, one may want to search for “characters” or “want to” or “bstring wi” or “language”.  All but the last example should be found. </em>

<em> </em>Keep in mind that if you use divide and conquer to solve this problem there is one complication.  The string to be found could be split between two of the subproblems (assuming your algorithm divides the string into two smaller strings).  You’ll need to handle that case as well.


