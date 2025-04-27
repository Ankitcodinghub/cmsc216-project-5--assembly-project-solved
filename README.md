# cmsc216-project-5--assembly-project-solved
**TO GET THIS SOLUTION VISIT:** [CMSC216 Project 5#-Assembly Project Solved](https://www.ankitcodinghub.com/product/cmsc216-project-5-assembly-project-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;86525&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC216 Project 5#-Assembly Project Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this project you will write AVR assembly code that corresponds to C code provided.

</div>
</div>
<div class="layoutArea">
<div class="column">
In the code distribution you’ll see two .c files for each function you need write; you’ll fill in the third (a .S file).

<ul>
<li>x_reference.c – A reference C implementation of what you should write.</li>
<li>x_driver.c-Amain()thatinvokesyourcode(orthereference,dependingontheMakefile)withvarious inputs to print the output.</li>
<li>x.S – Here is where you will define the function that in AVR assembly mimics the reference code. The Makefile has several rules. For example, for palindrome.S:
<pre>       make palindrome_s     /* builds executable */
       make palindrome_s.run /* runs the program using simulator */
       make palindrome_s.gdb /* runs the debugger */
</pre>
Although the base name of the assembly file is palindrome, we use palindrom s. You can also see the expected output for a test based on the reference code (C code). For example, for palindrome.S:

<pre>       make palindrome_r.run /* runs the reference code (C code) */
</pre>
Noticetheuseof r.Bytheway,thedrivercodecontainsthepublictests.

3 Specifications

For each C routine, create an assembly program that produces the same output, given identical input. Your primary goal should be to produce a working version of each program. Your secondary goal is to make it no more complicated than it needs to be.

The input is provided by main(); you will not be expected to read integers or halt (cli/sleep) at the end of your functions. You need only implement the routine, and the _driver.c will invoke the routine as needed.

3.1 Palindrome

Ask if it seems unclear. Palindromes are words or phrases that are the same forward as backwards, the C code shows an example of how to do it.

You may optimize the code, since array subscript operations are not straightforward. (You need to get to a pointer to read from memory, the pointer is in X, Y, or Z, and although you can access at a constant offset from a pointer (“LDD Rd, Z+q”) there is no single AVR instruction for array subscripting (variable pointer + variable offset).)
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
3.2 Fibonacci

Given n as a (uint16_t) parameter, it returns the nth Fibonacci number. This routine must be implemented in

a recursive fashion otherwise you will lose most of the credit.

3.3 Integer Square Root

Compute the square root of an integer, using the bitwise algorithm at https://en.wikipedia.org/wiki/ Integer_square_root.

You will need the logical shift instructions. To shift left by one, “lsl r24”. To shift left by two, repeat the instruction. Same for shifting right.

3.4 Reverse Prefix Sum

Transform an array by adding the value at an index to the sum of the remainder of the array. Return the sum. The return value may be a 16-bit integer, but the array is of 8-bit integers. (Do not concern yourself with behavior on overflow, just assume it will not happen.) The reverse prefix sum routine must be implemented in a recursive fashion otherwise you will lose most of the credit.

3.5 Rules

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
<div class="column">
<ol>
<li>You may refer as much as you like to the output of avr-gcc -S. You may run “make isqrt_reference.s” for example. We expect you to use this information only to help with individual fragments, for example, to learn how to add two words together, call shift instructions, find which instructions to execute, etc. We expect you to avoid copying any code from the compiler output.</li>
<li>(Restated…) You are expected to write the assembly code; this is preparation for exam questions. You can look at the compiler’s output if you need inspiration, but turning in something conspicuously sim- ilar to the compiler’s output will lose (at least) style points. The output of the compiler is inefficient, uncommented, and has an identifiable style that is more complicated than what humans would write. Notice that you don’t need to look at the compiler’s output in order to implement the project.</li>
<li>Don’t change the C code.</li>
<li>You don’t have to worry about the maximum length of 80 for a line of code. (You might write long comments.)</li>
<li>Your comments should be descriptive of the intent, not of the action. A comment per line after a semi- colon descriptive of what is happening is necessary. (I.e., “stash n for later use” is an ok comment. “move r24 into r20” is not.) A description of the variable that each register represents is useful.</li>
<li>Obey the callee-save and caller-save conventions; you must not clobber registers that the C driver does not expect you to clobber. If you have close control over only calling functions that you have person- ally written, you may be able to get away with skipping saving some caller-save registers; do not take advantage of this feature.</li>
</ol>
</div>
</div>
</div>
