# cs-2110-homework-5-intro-to-assembly-solved
**TO GET THIS SOLUTION VISIT:** [CS 2110 Homework 5 Intro to Assembly Solved](https://www.ankitcodinghub.com/product/cs-2110-homework-5-intro-to-assembly-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110881&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS 2110 Homework 5 Intro to Assembly Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Tam Truong, John Ever, Nimish Mishra, Kevin Mankowski, Haojun Yuan

Contents

1 Overview 2

1.1 Purpose 2

1.2 Task 2

1.3 Criteria 2

2 Detailed Instructions 3

2.1 Part 1: Square 3

2.2 Part 2: Array Modify 4

2.3 Part 3: Remove Vowels 5

2.4 Part 4: Toggle Case 6

3 Deliverables 6

4 Running the Autograder and Debugging LC-3 Assembly 8

5 Appendix 11

5.1 Appendix A: ASCII Table 11

5.2 Appendix B: LC-3 Instruction Set Architecture 12

5.3 Appendix C: LC-3 Assembly Programming Requirements and Tips 13

6 Rules and Regulations 14

6.1 General Rules 14

6.2 Submission Conventions 14

6.3 Submission Guidelines 14

6.4 Syllabus Excerpt on Academic Misconduct 14

6.5 Is collaboration allowed? 15

1 Overview

1.1 Purpose

So far in this class, you have seen how binary or machine code manipulates our circuits to achieve a goal. However, as you have probably figured out, binary can be hard for us to read and debug, so we need an easier way of telling our computers what to do. This is where assembly comes in. Assembly language is symbolic machine code, meaning that we don’t have to write all of the ones and zeros in a program, but rather symbols that translate to ones and zeros. These symbols are translated with something called the assembler. Each assembler is dependent upon the computer architecture on which it was built, so there are many different assembly languages out there. Assembly was widely used before most higher-level languages and is still used today in some cases for direct hardware manipulation.

1.2 Task

The goal of this assignment is to introduce you to programming in LC-3 assembly code. This will involve writing small programs, translating conditionals and loops into assembly, modifying memory, manipulating strings, and converting high-level programs into assembly code.

You will be required to complete the four functions listed below with more in-depth instructions on the following pages:

1. square.asm

2. arrayModify.asm

3. removeVowels.asm

4. toggleCase.asm

1.3 Criteria

Your assignment will be graded based on your ability to correctly translate the given pseudocode into LC-3 assembly code. Check the deliverables section for deadlines and other related information. Please use the LC-3 instruction set when writing these programs. More detailed information on each instruction can be found in the Patt/Patel book Appendix A (also on Canvas under “LC-3 Resources”). Please check the rest of this document for some advice on debugging your assembly code, as well some general tips for successfully writing assembly code.

You must obtain the correct values for each function. While we will give partial credit where we can, your code must assemble with no warnings or errors (Complx will tell you if there are any). If your code does not assemble, we will not be able to grade that file and you will not receive any points. Each function is in a separate file, so you will not lose all points if one function does not assemble. Good luck and have fun!

2 Detailed Instructions

2.1 Part 1: Square

To start you off with this homework, we are implementing a function that takes a positive integer A, and calculate the square. Store the result of the operation in the label ANSWER. Argument A is stored in memory, and you will load it from there to perform this operation. Implement your assembly code in square.asm.

Suggested Pseudocode:

a = (argument 1); ANSWER = 0; for (int i = 0; i &lt; a; i++) { ANSWER += a;

} return ANSWER;

2.2 Part 2: Array Modify

The second assembly function is to implement certain array modifications to an array. You will be modifying an array out of place, meaning that the original array will remain the same and your code will produce a resulting array with said modifications. The resulting array will have enough space for the final answer. Use the pseudocode to help plan out your assembly and implement your assembly code in arrayModify.asm.

In this assembly code, you will need to look through the array x. If the index is odd, then take the value of that index, subtract by 10, and save the updated value in array y at that index. If the index is even, then take the value of that index, multiply by 2, and save the updated value in array y at that index.

Suggested Pseudocode:

i = 0; // first index len = Len(ARR_X);

while (i &lt; len) { if (i % 2 == 0) {

//if we are at an even index, subtract 10 and save it to the array at that index ARR_Y[i] = ARR_X[i] – 10; } else {

//if we are at odd index, multiply by 2 and save it to the array at that index

ARR_Y[i] = ARR_X[i] * 2;

} i++;

}

2.3 Part 3: Remove Vowels

The third assembly function is to modify a null-terminated string by removing all vowels. (a/A, e/E, i/I, o/O, u/U) Your function should work for both uppercase and lowercase letters. You should iterate through the string, and return a new string that has all of the vowels removed.

Assume that the strings are random: they can contain characters, numbers, spaces and symbols.

To modify a character, refer to the ASCII table and remember that each of these characters are represented by a word (16-bits) in the LC-3’s memory. This is a null-terminated string, meaning that a 0 will be stored immediately after the final character in memory!

NOTE:

• 0 is the same as ‘’

• 0 is different from ‘0’

Suggested Pseudocode:

STRING = (argument 1); ANSWER = “”; for (int i = 0; i &lt; a.length; i++) { if (string[i] == ’’){ break;

} if (string[i] == ’A’ || string[i] == ’a’) { continue;

} else if (string[i] == ’E’ || string[i] == ’e’) { continue;

} else if (string[i] == ’I’ || string[i] == ’i’) { continue;

} else if (string[i] == ’O’ || string[i] == ’o’) { continue;

} else if (string[i] == ’U’ || string[i] == ’u’) { continue;

}

ANSWER += STRING[i];

}

ANSWER += ’’ return ANSWER;

2.4 Part 4: Toggle Case

For the final problem, your goal is to look through a null-terminated string, and change the uppercase to a lowercase; a lowercase to an uppercase. The label ANSWER will contain the address of the answer string that you will use to store the modified string. You will read the value from a provided string, if the letter at that index is uppercase, then change it to a lowercase. If the letter at that index is lowercase, then change it to an uppercase.

The label STRING will contain the address of the first character of the string to be read from. Remember that this string is null-terminated. The result string will be stored at the label ANSWER (ANSWER will contain the address of the first character of the result string. Implement your assembly code in toggleCase.asm

Assume every character in the string is an English alphabetic letter and not a number. You must also ignore the spaces in between.

NOTE:

• 0 is the same as ‘’

• 0 is different from ‘0’

• ”A” in ASCII is 65

• ”Z” in ASCII is 90

• ASCII table: https://www.asciitable.com/

Suggested Pseudocode:

string = “Assembly is interesting”; // given string

Array[string.len()] answer; // array to store the result string i = 0;

while (string[i] != ’’) { if (string[i] == ” “) { answer[i] = ” “;

} else if (string[i] &gt;= “A” &amp;&amp; string[i] &lt;= “Z”) { answer[i] = string[i].lowerCase();

} else {

answer[i] = string[i].upperCase();

} i++;

}

3 Deliverables

Turn in the following files on Gradescope:

1. square.asm

2. arrayModify.asm

3. removeVowels.asm

4. toggleCase.asm

Note: Please do not wait until the last minute to run/test your homework. Last minute turn-ins will result in long queue times for grading on Gradescope. You have been warned.

4 Running the Autograder and Debugging LC-3 Assembly

1. First off, we can get these replay strings in two places: the local grader, or off of Gradescope. To run the local grader:

• Mac/Linux Users:

(a) Navigate to the directory your homework is in (in your terminal on your host machine, not in the Docker container via your browser)

(b) Run the command sudo chmod +x grade.sh

(c) Now run ./grade.sh

• Windows Users:

(a) In Git Bash (or Docker Quickstart Terminal for legacy Docker installations), navigate to the directory your homework is in

(b) Run chmod +x grade.sh

(c) Run ./grade.sh

When you run the script, you should see an output like this:

Side Note: If you do not have Docker installed, you can still use the tester strings to debug your assembly code. In your Gradescope error output, you will see a tester string. When copying, make sure you copy from the first letter to the final backslash and again, don’t copy the quotations.

2. Secondly, navigate to the clipboard in your Docker image and paste in the string.

3. Next, go to the Test Tab and click Setup Replay String

4. Now, paste your tester string in the box!

5. Now, Complx is set up with the test that you failed! The nicest part of Complx is the ability to step through each instruction and see how they change register values. To do so, click the step button. To change the number representation of the registers, double click inside the register box.

6. If you are interested in looking how your code changes different portions of memory, click the view tab and indicate ’New View’

7. Now in your new view, go to the area of memory where your data is stored by CTRL+G and insert the address

8. One final tip: to automatically shrink your view down to only those parts of memory that you care about (instructions and data), you can use View Tab → Hide Addresses → Show Only Code/Data.

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

5. Following from 3, you can load the file with randomized memory by selecting “File” ¿ “Advanced Load” and selecting randomized registers/memory.

6. Do NOT execute any data as if it were an instruction (meaning you should put .fills after HALT or

RET).

7. Do not add any comments beginning with @plugin or change any comments of this kind.

8. Test your assembly. Don’t just assume it works and turn it in.

6 Rules and Regulations

6.1 General Rules

2. If you find any problems with the assignment it would be greatly appreciated if you reported them to the author (which can be found at the top of the assignment). Announcements will be posted if the assignment changes.

6.2 Submission Conventions

1. Do not submit links to files. The autograder does not understand it, and we will not manually grade assignments submitted this way as it is easy to change the files after the submission period ends. You must submit all files listed in the Deliverables section individually to Gradescope as separate files.

6.3 Submission Guidelines

2. You are also responsible for ensuring that what you turned in is what you meant to turn in. After submitting you should be sure to download your submission into a brand new folder and test if it works. No excuses if you submit the wrong files, what you turn in is what we grade. In addition, your assignment must be turned in via Canvas/Gradescope. Under no circumstances whatsoever we will accept any email submission of an assignment. Note: if you were granted an extension you will still turn in the assignment over Canvas/Gradescope.

6.4 Syllabus Excerpt on Academic Misconduct

Academic misconduct is taken very seriously in this class. Quizzes, timed labs and the final examination are individual work.

Homework assignments are collaborative, In addition many if not all homework assignments will be evaluated via demo or code review. During this evaluation, you will be expected to be able to explain every aspect of your submission. Homework assignments will also be examined using computer programs to find evidence of unauthorized collaboration.

You are expressly forbidden to supply a copy of your homework to another student via electronic means. This includes simply e-mailing it to them so they can look at it. If you supply an electronic copy of your homework to another student and they are charged with copying, you will also be charged. This includes storing your code on any site which would allow other parties to obtain your code such as but not limited to public repositories (Github), pastebin, etc. If you would like to use version control, use github.gatech.edu

6.5 Is collaboration allowed?
