Download Link: https://assignmentchef.com/product/solved-cse2240-lab-4
<br>
<h1>About this lab</h1>

For this lab, you are going to convert a c code (Blinky.c) to an ARM assembly code.

The ARM assembly code will be <strong><u>checked and graded</u></strong> during the <strong><u>first 15 minutes of next lab session (April 18th)</u></strong> (20 points).

<h1>About coding</h1>

The function of this c code is to let the LEDs blink, so does the covert ARM assembly code. Next week, we are going to run the ARM assembly code on <em>KEIL STM STM32C Eval BD &amp; ULINK-ME</em> board (device MCBSTM32CUME). We will see something real then.

For this lab, our main work will be converting the code. Thus, instead of showing these values on LEDs, we are going to store these values in memory (make sure these values won’t mess up in memory). You can decide where to store (the memory address) these values. 10 values will be fine.  <strong>Hint </strong>

<h2>For this lab</h2>

<ul>

 <li>Before start coding, do some research for operator “&lt;&lt;” and “|=”.</li>

 <li>The value of RCC-&gt;APB2ENR and GPIOE-&gt;CRH is given in the c code. For ARM assembly, assign AD_val with 0x100.</li>

 <li>You could rename GPIOE-&gt;BSRR to R0 with command “GPIOE-&gt;BSRR RN R0” for your convenience.</li>

</ul>

<h2>For next lab</h2>

<ul>

 <li>You could do some research for pins appear in the c code (like LED_NUM, AD_val,</li>

</ul>

RCC-&gt;APB2ENR, GPIOE-&gt;CRH, GPIOE-&gt;BSRR). They may just be variables for this lab, but will be meaningful for next lab. Better understanding of these pins will help you a lot next week.

<strong>Submission </strong>

ARM assembly .s code.

<h1>Demo</h1>

Show the code and the values you store in the memory next week in lab session as mentioned above.

<strong> </strong>





