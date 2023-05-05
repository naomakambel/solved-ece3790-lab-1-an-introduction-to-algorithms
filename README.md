Download Link: https://assignmentchef.com/product/solved-ece3790-lab-1-an-introduction-to-algorithms
<br>
<strong>The purpose of this lab is to give you a simple introduction to algorithms. Specifically, you will implement two algorithms in two different languages and analyze their behaviour for different problem instances.</strong>

<strong>Important: </strong>Please include the following signed statement with your submission.

I (We), [insert name(s)] attest that the work I am (we are) submitting is my (our) own work and that it has not been copied/plagiarized from online or other sources. Any sourced material used for completing this work has been properly cited. [Signature(s)]

<strong>Also Important: </strong>Labs done in pairs must be submitted with a short paragraph outlining each partner’s contribution.

<h1>Introduction</h1>

This programming laboratory will provide you an opportunity to brush up on your programming skills. If you haven’t yet been introduced to Matlab, you will also get a learn-by-doing introduction.

For this first lab, you will be required to implement solutions in <em>two </em>languages: 1) Python, Java, or C/C++ (your choice) and 2) Matlab. It is not the purpose of this course to teach you these languages, however if you have questions/troubles with your code please don’t hesitate to ask.

A crash course in Matlab programming can be found on the course webpage. If you are learning Matlab for the first time, it is highly suggested that you read the posted supplemental material before coming to the lab.

<h1>Problem 1 – Matrix Multiplication</h1>

<h2>Functions</h2>

Implement a matrix-matrix-product function called matrixmultiply that takes as arguments matrices A and B and returns the product C = A*B. Your implementation should directly implement the triply-nested for-loop algorithm presented in Lecture 1. The following notes apply:

<ul>

 <li>it is not necessary for the matrices to be square</li>

 <li>your function should identify and report erroneous problem instances</li>

 <li>you are free to add any function arguments required for your language of choice (e.g., matrix sizes)</li>

 <li>you can use derived types or classes to represent matrices but will have to clearly explain what you’re using and where it comes from (if you’re using a third-party library)</li>

</ul>

<strong>Note: </strong>Implement your matrix multiplication function in two languages, one of which must be Matlab.

<h2>Main Program</h2>

Write a main program Lab 1 Problem 1 that:

<ul>

 <li>reads the sizes of matrices A and B from the command line (or other user input), allocates and fills A and B as random matrices, and evaluates the product C = A*B</li>

 <li>evaluates the computational time of the <em>matrix product </em>(excluding other operations) and clearly displays the elapsed time</li>

 <li>verifies the matrix product against a built-in/library routine (think carefully about how can you succintly show that the result is correct)</li>

 <li>evaluates the computational time of the <em>built-in/library </em>routine and clearly displays the elapsed time</li>

</ul>

<strong>Note: </strong>Implement your main program in two languages, one of which must be Matlab.

<h2>Validation and Data Collection</h2>

Once you have completed writing your function and main program you need to:

<ul>

 <li>show that your function works for both square and rectangular matrices (you will need to decide what is convincing)</li>

 <li>use both your method and the built-in/library method to collect timing data for various square matrix sizes, for example <em>n </em>= 100<em>,</em>200<em>,</em>400<em>,</em>800<em>,… </em>and plot time versus problem size for the two methods.</li>

</ul>

<strong>Note: </strong>You should validate, collect data, and produce plots for <strong>two languages</strong>. The plots can be produced by a common tool (e.g., you could use Matlab to produce plots for both implementations).

<h2>Evaluation and Discussion</h2>

Answer the following questions:

<ol>

 <li>What computer hardware did you use to run the algorithms produced in this lab (CPU type, number of cores, amount of memory)?</li>

 <li>How did you verify that your algorithm works? How can you be sure it works for all problem instances?</li>

 <li>How does your algorithm perform versus the built-in/library function? What factors/reasons contribute to any difference in performance?</li>

 <li>How does the performance of your algorithm change as a function of problem size? Is the <em>change </em>the same or different from the built-in function? Why?</li>

 <li><em>Derive </em>the order-of-growth of <em>your </em>matrix multiplication algorithm. Justify why or why not the results you measured agree with your assessment of the order-of-growth. You can do this on just the square matrix-matrix multiplication for simplicity (i.e.</li>

</ol>

<em>C<sup>n</sup></em><sup>×<em>n </em></sup>= <em>A<sup>n</sup></em><sup>×<em>n</em></sup><em>B<sup>n</sup></em><sup>×<em>n</em></sup>). Is this a tight upper bound? Justify.

<ol start="6">

 <li>Under what conditions would order of growth <em>not </em>be useful for estimating the actual run-time scaling?</li>

</ol>

<strong>Note: </strong>Evaluation and discussion should occur for <strong>two languages </strong>corresponding to your validation/data collection for those languages. There is no need to repeat discussions that are common to both language implementations, just focus on any differences.

<strong>Hand in:</strong>

Hand in all code, plots, a table showing your measured times (two languages, two functions each language), and your answers to the discussion questions.

<h1>Problem 2 – Merge Sort</h1>

<h2>Functions</h2>

Implement an in-place merge sort function called mergesort that takes as arguments an

array A and returns the sorted array in A. The following notes apply:

<ul>

 <li>your function can be implemented for sorting one specific type of data (it does not need to work for general inputs)</li>

 <li>your function should identify and report erroneous problem instances (erroneous might depend on your previous design decision)</li>

 <li>you are free to add any function arguments required for your language of choice (e.g., array size)</li>

</ul>

<strong>Note: </strong>Implement your merge sort function in two languages, one of which must be Matlab.

<h2>Main Program</h2>

Write a main program Lab 1 Problem 2 that:

<ul>

 <li>reads the size of the array/list to be sorted from the command line (or other user input), allocates and fills A as a random list and sorts it using your merge sort function</li>

 <li>evaluates the computational time of the <em>sorting </em>(excluding other operations) and clearly displays the elapsed time</li>

 <li>verifies the <em>sorting</em>; you may consider writing a utility function for this</li>

 <li>evaluates the computational time for sorting the same list using a <em>built-in/library </em>routine and clearly displays the elapsed time</li>

</ul>

<strong>Note: </strong>Implement your main program in two languages, one of which must be Matlab.

<h2>Validation and Data Collection</h2>

Once you have completed writing your function and main program you need to:

<ul>

 <li>show that your function works</li>

 <li>use both your method and the built-in/library method to collect timing data for various array/list sizes, for example <em>n </em>= 1000<em>,</em>2000<em>,</em>4000<em>,</em>8000<em>,… </em>and plot time versus problem size for the two methods.</li>

</ul>

<strong>Note: </strong>You should validate, collect data, and produce plots for <strong>two languages</strong>. The plots can be produced by a common tool (e.g., you could use Matlab to produce plots for both implementations).

<h2>Evaluation and Discussion</h2>

Answer the following questions:

<ol>

 <li>How did you verify that your algorithm works? How can you be sure it works for all problem instances?</li>

 <li>How does your algorithm perform versus the built-in/library function? What factors/reasons contribute to any difference in performance? Just use the default sort function from the language you are using.</li>

 <li>How does the performance of your algorithm change as a function of problem size? Is the <em>change </em>the same or different from the built-in function? Why?</li>

 <li><em>Derive </em>the order-of-growth of <em>your </em>merge sort implementation. Justify why or why not the results you measured agree with your assessment of the order-of-growth.</li>

 <li>Relate this result to what the algorithm is doing in plain English. As an example, for bubble sort (<em>O</em>(<em>n</em><sup>2</sup>)) we might say, “Each entry in a list of length <em>n </em>needs to be compared to/swapped with ∼ <em>n </em>other entries in the list. This means that for <em>n </em>list entries and ∼ <em>n </em>checks/swaps per list entry, we see some function of <em>n</em><sup>2 </sup>checks/swaps”.</li>

 <li>Prove (<em>with math</em>) that the base of the logarithm in Big-O analysis doesn’t matter. (Hint: What else doesn’t matter in Big-O analysis?)</li>

</ol>

<strong>Note: </strong>Evaluation and discussion should occur for <strong>two languages </strong>corresponding to your validation/data collection for those languages. There is no need to repeat discussions that are common to both language implementations, just focus on any differences.