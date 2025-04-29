# cs2110-homework-5--intro-to-assembly-solved
**TO GET THIS SOLUTION VISIT:** [CS2110 Homework 5- Intro to Assembly Solved](https://www.ankitcodinghub.com/product/cs-2110-homework-5-intro-to-assembly-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109747&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2110 Homework 5- Intro to Assembly Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
&nbsp;

1 Overview

1.1 Purpose:

So far in this class, you have seen how binary or machine code manipulates our circuits to achieve a goal. However, as you have probably figured out, binary can be hard for us to read and debug, so we need an easier way of telling our computers what to do. This is where assembly comes in. Assembly language is symbolic machine code, meaning that we don’t have to write all of the ones and zeros in a program, but rather symbols that translate to ones and zeros. These symbols are translated with something called the assembler. Each assembler is dependent upon the computer architecture on which it was built, so there are many different assembly languages out there. Assembly was widely used before most higher-level languages and is still used today in some cases for direct hardware manipulation.

1.2 Task:

The goal of this assignment is to introduce you to programming in LC-3 assembly code. This will involve writing small programs, translating conditionals and loops into assembly, modifying memory, manipulating strings, and converting high-level programs into assembly code.

You will be required to complete the four functions listed below with more in-depth instructions on the following pages:

1. mult.asm

2. selectionsort.asm

3. printvowels.asm

4. linkedlist.asm

1.3 Criteria:

Your assignment will be graded based on your ability to correctly translate the given pseudocode into LC-3 assembly code. Check the deliverables section for deadlines and other related information. Please use the LC-3 instruction set when writing these programs. More detailed information on each instruction can be found in the Patt/Patel book Appendix A (also on Canvas under LC3 Resources). Please check the rest of this document for some advice on debugging your assembly code, as well some general tips for successfully writing assembly code.

You must obtain the correct values for each function. While we will give partial credit where we can, your code must assemble with no warnings or errors (Complx will tell you if there are any). If your code does not assemble, we will not be able to grade that file and you will not receive any points. Each function is in a separate file, so you will not lose all points if one function does not assemble. Good luck and have fun!

2 Detailed Instructions

2.1 Part 1: Implementing Multiply

To start you off with this homework, we are implementing the multiply function! Store the result of the operation in the label ANSWER. Arguments A and B are stored in memory, and you will load them from there to perform this operation. Assume the values of A and B are positive integers. Implement your assembly code in mult.asm.

Suggested Pseudocode:

a = (argument 1); b = (argument 2); ANSWER = 0; while (b &gt; 0) { ANSWER = ANSWER + a; b–;

}

// note: when the while-loop ends, the value stored at ANSWER is a times b.

2.2 Part 2: Selection Sort

The second assembly function is to selection-sort all elements of an array in memory. Use the pseudocode to help plan out your assembly and make sure you are sorting it properly! Implement your assembly code in selectionsort.asm. For more information on selection sort and a good visual representation, check out this link.

Suggested Pseudocode:

x = 0;

len = length of array; while(x &lt; len – 1) { // current swapping index in the array

z = x; // index of minimum value in unsorted portion of array

y = x + 1; // current index in array

while (y &lt; len) { if (arr[y] &lt; arr[z]) {

z = y;

} y++;

}

if (z != x) { // update the index of the minimum value

temp = arr[x]; arr[x] = arr[z]; arr[z] = temp;

} x++; // perform a swap

}

2.3 Part 3: Printing Vowels

The third assembly function is to print the vowels in a null-terminated string. The label STRING will contain the address of the first character of the string. Remember that strings are just arrays of consecutive characters. Implement your assembly code in printvowels.asm Assume every character in the string is UPPERCASE.

To check for these vowel characters, refer to the ASCII table and remember that each of these characters are represented by a word (16-bits) in the LC-3’s memory. This is a null-terminated string, meaning that a 0 will be stored immediately after the final character in memory!

NOTE:

0 is the same as ’’

0 is different from ’0’

Suggested Pseudocode:

string = “TWENTY ONE TEN”; i = 0;

while(string[i] != ’’){ if(string[i] == ’A’ || string[i] == ’E’ || string[i] == ’I’ || string[i] == ’O’ || string[i] == ’U’){

print(string[i]);

} i++;

}

Hint: Take a look at the trap vectors in Appendix A for printing characters to the console.

2.4 Part 4: Make elements of a Linked List into a string

For the final problem, your goal is to create a string from the elements of a linked list and store that string at the label named ANSWER (don’t forget about the null terminating character mentioned in Part 3). In order to do so, look at the label we have given you:

• LL: The address of a Linked List object. Similar to Java, our linked list is an object with two attributes – head and length. These two attributes are stored in memory like so:

Address of Length of

LL

Head Node Linked List

Every node in our linked list is another object with two attributes – next node and value. These two attributes are stored in memory like so:

So together, our data structure would look something like this:

Memory Memory

Memory x4000 Memory x4001

x4008 ’A’

Address of Value at next node head node

Memory x4008 Memory x4009

x0000 ’B’

Address Value at of next next node node(null)

Now that you understand what data structure we are dealing with, we have provided the following pseudocode to help you begin your coding! This code will be implemented in the linkedlist.asm file.

Suggested Pseudocode:

length = LL.length; curr = LL.head; //HINT: What can an LDI instruction be used for?

ANSWER = char[length]; //This character array will already be setup for you i = 0;

while (curr != null) { ANSWER[i] = curr.value; curr = curr.next; i++;

}

3 Deliverables

Turn in the files

1. mult.asm

2. selectionsort.asm

3. printvowels.asm

4. linkedlist.asm

Note: Please do not wait until the last minute to run/test your homework, history has proved that last minute turn-ins will result in long queue times for grading on Gradescope. You have been warned.

4 Running Autograder and Debugging LC-3 Assembly

When you turn in your files on gradescope for the first time, you might not receive a perfect score. Does this mean you change one line and spam gradescope until you get a 100? No! You can use a handy tool known as tester strings.

1. First off, we can get these tester strings in two places: the local grader or off of gradescope. To run the local grader:

• Mac/Linux Users:

(a) Navigate to the directory your homework is in. In your terminal, not in your browser

(b) Run the command sudo chmod +x grade.sh

(c) Now run ./grade.sh

• Windows Users:

(a) On docker quickstart, navigate to the directory your homework is in (b) Run ./grade.sh

When you run the script, you should see an output like this:

Copy the string, starting with the leading ’B’ and ending with the final backslash. Do not include the quotation marks.

Side Note: If you do not have docker installed, you can still use the tester strings to debug your assembly code. In your gradescope error output, you will see a tester string. When copying, make sure you copy from the first letter to the final backslace and again, don’t copy the quotations.

2. Secondly, navigate to the clipboard in your docker image and paste in the string.

3. Next, go to the Test Tab and click Setup Replay String

4. Now, paste your tester string in the box!

5. Now, complx is set up with the test that you failed! The nicest part of complx is the ability to step through each instruction and see how they change register values. To do so, click the step button. To change the number representation of the registers, double click inside the register box.

6. If you are interested in looking how your code changes different portions of memory, click the view tab and indicate ’New View’

7. Now in your new view, go to the area of memory where your data is stored by CTRL+G and insert the address

5 Appendix

5.1 Appendix A: ASCII Table

Figure 1: ASCII Table — Very Cool and Useful!

5.2 Appendix B: LC-3 Instruction Set Architecture

5.3 Appendix C: LC-3 Assembly Programming Requirements and Tips

1. Your code must assemble with NO WARNINGS OR ERRORS. To assemble your program, open the file with Complx. It will complain if there are any issues. If your code does not assemble you WILL get a zero for that file.

2. Comment your code! This is especially important in assembly, because it’s much harder to interpret what is happening later, and you’ll be glad you left yourself notes on what certain instructions are contributing to the code. Comment things like what registers are being used for and what less intuitive lines of code are actually doing. To comment code in LC-3 assembly just type a semicolon (;), and the rest of that line will be a comment.

3. Avoid stating the obvious in your comments, it doesn’t help in understanding what the code is doing.

Good Comment

ADD R3, R3, -1 ; counter–

BRp LOOP

Bad Comment ; if counter == 0 don’t loop again

ADD R3, R3, -1 ; Decrement R3

BRp LOOP ; Branch to LOOP if positive

4. DO NOT assume that ANYTHING in the LC-3 is already zero. Treat the machine as if your program was loaded into a machine with random values stored in the memory and register file.

5. Following from 3. You can randomize the memory and load your program by doing File – Randomize and Load.

6. Use the LC-3 calling convention. This means that all local variables, frame pointer, etc… must be pushed onto the stack. Our autograder will be checking for correct stack setup.

7. Start the stack at xF000. The stack pointer always points to the last used stack location. This means you will allocate space first, then store onto the stack pointer.

8. Do NOT execute any data as if it were an instruction (meaning you should put .fills after HALT or RET).

9. Do not add any comments beginning with @plugin or change any comments of this kind.

10. Test your assembly. Don’t just assume it works and turn it in.

5.4 Appendix D: Rules and Regulations

5.4.1 General Rules

1. Starting with the assembly homeworks, any code you write should be meaningfully commented for your benefit. You should comment your code in terms of the algorithm you are implementing; we all know what each line of code does.

3. Please read the assignment in its entirety before asking questions.

5. If you find any problems with the assignment it would be greatly appreciated if you reported them to the author (which can be found at the top of the assignment). Announcements will be posted if the assignment changes.

5.4.2 Submission Conventions

1. All files you submit for assignments in this course should have your name at the top of the file as a comment for any source code file, and somewhere in the file, near the top, for other files unless otherwise noted.

3. Do not submit compiled files, that is .class files for Java code and .o files for C code. Only submit the files we ask for in the assignment.

4. Do not submit links to files. The autograder does not understand it, and we will not manually grade assignments submitted this way as it is easy to change the files after the submission period ends.

5.4.3 Submission Guidelines

2. You are also responsible for ensuring that what you turned in is what you meant to turn in. After submitting you should be sure to download your submission into a brand new folder and test if it works. No excuses if you submit the wrong files, what you turn in is what we grade. In addition, your assignment must be turned in via Canvas/Gradescope. Under no circumstances whatsoever we will accept any email submission of an assignment. Note: if you were granted an extension you will still turn in the assignment over Canvas/Gradescope.

5.4.4 Syllabus Excerpt on Academic Misconduct

Academic misconduct is taken very seriously in this class. Quizzes, timed labs and the final examination are individual work.

Homework assignments are collaborative, In addition many if not all homework assignments will be evaluated via demo or code review. During this evaluation, you will be expected to be able to explain every aspect of your submission. Homework assignments will also be examined using computer programs to find evidence of unauthorized collaboration.

You are expressly forbidden to supply a copy of your homework to another student via electronic means. This includes simply e-mailing it to them so they can look at it. If you supply an electronic copy of your homework to another student and they are charged with copying, you will also be charged. This includes storing your code on any site which would allow other parties to obtain your code such as but not limited to public repositories (Github), pastebin, etc. If you would like to use version control, use github.gatech.edu

5.4.5 Is collaboration allowed?

Figure 2: Collaboration rules, explained colorfully
