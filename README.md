Download Link: https://assignmentchef.com/product/solved-embsys100-module-5-bit-banding-region
<br>
The goals for the assignment this week:

<ol>

 <li>Practice the use of bit-banding region.</li>

 <li>Examine the assembly code generated for a function with multiple parameters.</li>

 <li>Go thru a design problem exercising key concepts we viewed so far (pointers, arrays, functions, design, API, testing…etc.)</li>

 <li>Bonus: Apply usage of pointers and the understanding of Endianness.</li>

</ol>

Problems:

<ol>

 <li>Using bit-band region for peripherals:

  <ol>

   <li>Convert the Blinking Led demo to use the corresponding bit-band address instead of the register address used in the peripheral region.</li>

   <li>What instructions does the compiler produce in assembly for the “writing” to the GPIO bit when using bit-band address?</li>

   <li>What were the instructions produced when writing to the GPIOx_ODR bit[5] directly?</li>

  </ol></li>

</ol>




<ol start="2">

 <li>Create a function with multiple arguments (5 arguments for example) and call that function from within another function. Trace thru the assembler and note:

  <ol>

   <li>How does the <strong>calling</strong> function pass the values to the <strong>called</strong> function?</li>

   <li>What extra code did the compiler generate before calling the function with the multiple arguments?</li>

   <li>What extra code did the compiler generate inside the <strong>called</strong> function with the multiple list of arguments?</li>

   <li>Any other observations?</li>

  </ol></li>

</ol>

<ol start="3">

 <li>Following the queue data structure approach, design, implement and test a stack data structure:

  <ol>

   <li>The following is the list of requirements:

    <ol>

     <li><em>The stack should have a predefined size </em></li>

     <li><em>The stack supports “int” data types. </em></li>

    </ol></li>

  </ol></li>

</ol>

<ul>

 <li><em>Provide a function to initialize the stack internals. iv.</em><em> Provide a function to push an element onto the stack </em></li>

</ul>

<ol>

 <li><em> Provide a function to pop an element off the stack. vi.</em><em> Provide a function that returns 1 if stack is empty. </em>vii. <em>Provide a function that returns 1 if stack is full.</em></li>

 <li>Provide a list of the test cases and their implementation inside of main.c</li>

 <li>Separate the stack code from the rest of the test code (create stack.h &amp; stack.c)</li>

 <li><strong><u>Bonus:</u></strong> Using the power of pointers and type casting, create a function that can determine if a computer is big-endian or little-endian. Test your function in the simulator and modify the Project Options (as shown in the figure below) against:

  <ol>

   <li>Device STM32F401RE</li>

   <li>Cortex M4 (Little endian option)</li>

   <li>Cortex M4 (Big Endian option)</li>

  </ol></li>

</ol>