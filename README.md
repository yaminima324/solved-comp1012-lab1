Download Link: https://assignmentchef.com/product/solved-comp1012-lab1
<br>
<h2 id="exercise-0-gaining-access-to-lab-computers"> Gaining Access to Lab Computers</h2>

If you have not done so, you must claim your U of M computer account using Iridium. From a logged in computer (maybe this is a good time to meet the person sitting next to you in the lab!) open a web browser and go to <a href="http://signum.umanitoba.ca" target="_blank" rel="noopener">SignUM</a>. Click on <code>Click here to begin</code>. You will have to identify yourself, and then provide answers to a number of personal questions so that you can later log in even if your forget your password. This will enable you to access lab computers. Record your <code>UMnetID</code> and password or otherwise take steps to remember them. If you have already claimed your ID, you can also change your password or answers to security questions using SignUM. The same user UMnetID will be used to log into the course UMLearn website.

To login, you must enter your <strong>complete U of M email address</strong>. Your email address is composed of: your UMnetID, followed by the <strong><span class="citation" data-cites="*">@*</span>* symbol, and then </strong>myumanitoba.ca<strong>. For example, a student with UMnetID of chan139, the U of M email address is: </strong><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="e7848f8689d6d4dea78a9e928a">[email protected]</a>anitoba.ca**.

<h2 id="exercise-1-ensuring-that-python-works-on-your-lab-computer">Exercise 1: Ensuring that Python works on your lab computer</h2>

For this course we are using Anaconda Python. You can acquire it for your personal computer from <a href="https://www.anaconda.com/download/" target="_blank" rel="noopener">this link</a>.

<ol type="1">

 <li>Click on the <code>Start</code> button, choose</li>

 <li><code>INS Programs</code>, and then</li>

 <li><code>Programming</code>.</li>

 <li>In the <code>Programming</code> sub-menu, you should see <code>Spyder (Python IDE)</code>.</li>

</ol>

Click on it to start the Spyder IDE. Note that the lab installation does <strong>not</strong> start the Launcher app.

<h2 id="exercise-2-interactive-mode">Exercise 2: Interactive Mode</h2>

Execute some math in the interactive console (IPython) that is in the lower right-hand corner of the window.

Don’t just copy and paste these! Type them in by hand to get your finger memory working with typing expressions.

Try some of the following:

<ul>

 <li><code>42 + 42</code></li>

 <li><code>5 / 2</code></li>

 <li><code>"I can write anything here"</code></li>

 <li><code>print("I can write anything here")</code></li>

 <li><code>a = 3</code></li>

 <li><code>a ** 2</code></li>

 <li><code>print("Hello, my name is {} {}.".format("Inigo", "Montoya"))</code></li>

</ul>

<h2 id="exercise-3-programming-1-mark">Exercise 3: Programming (1 mark)</h2>

In Spyder, write a Python program (script) that has a variable <code>num</code> that is set to the value 35607. Your program is to display the last and second-last digit of the value stored in <code>num</code>. For example, when <code>num</code> contains the value 35607, your program should print <code>the last digit of 35607 is 7</code> and <code>the second last digit of 35607 is 0</code> respectively.

Your program should be able to work with whatever number is stored in the variable <code>num</code>. Test your program with <code>num=35607</code> and <code>num=6198</code>.

<h2 id="advanced-exercise-4-using-log10x">(Advanced) Exercise 4: Using <code>log10(x)</code></h2>

Continuing with exercise 3, look up the <code>log10</code> function from the <code>math</code> <a href="https://docs.python.org/3.7/library/math.html">library</a> and use it to print the first digit in <code>num</code>. For example, if <code>num=35607</code>, then the output will be <code>3</code>.

Here is a <a href="https://www.tutorialspoint.com/python3/number_log10.htm">page</a> to demonstrates how to use <code>log10</code>.

<h2 id="advanced-exercise-5-output-formatting">(Advanced) Exercise 5: Output formatting</h2>

If you finish all of the other exercises before the lab time is complete, try working on the following material that may not yet have been covered in class:

<ul>

 <li>Use String formatting to print out a number that has a maximum of 3 decimal places. Use the following resources to help solve this problem.

  <ul>

   <li><a href="https://pyformat.info/" target="_blank" rel="noopener">https://pyformat.info/</a></li>

   <li><a href="https://docs.python.org/3/library/string.html#format-examples" target="_blank" rel="noopener">https://docs.python.org/3/library/string.html#format-examples</a></li>

   <li><a href="https://docs.python.org/3/library/string.html#formatstrings" target="_blank" rel="noopener">https://docs.python.org/3/library/string.html#formatstrings</a></li>

  </ul></li>

 <li>Change the program <a href="AreaOfTriangle.py">AreaOfTriangle.py</a> to output <code>The area of the triangle is 1.333</code> (3 decimal points). Decimal displays only work on decimal types, you may need to convert your datatype, or use a <code>{f}</code> placeholders.</li>

</ul>

<h1 id="saving-your-work">Saving your work</h1>