# cs39003-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CS39003 Assignment 2 Solved](https://www.ankitcodinghub.com/product/compiler-laboratory-cs39003-3rd-year-cse-5th-semester-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113928&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS39003 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1. Write a C program consisting of the following functions to create a library. You cannot use any standard library function.

• int printStr(char *) – prints a string of characters. The parameter is terminated by ’’. The return value is the number of characters printed.

• int readInt(int *n) – reads a signed integer in ‘%d’ format. Caller gets the value through the pointer parameter. The return value is OK (for success) or ERR (on failure).

• int printInt(int n) – prints the signed integer (n) with left-alignment. Printing sign for a negative number is mandatory while for a positive number it is not required. On success, function will return the number of characters printed and on failure it will return ERR.

• int readFlt(float *f) – reads a floating point number in ‘%f’ format (for example, –123.456). Caller gets the value through the pointer parameter. The return value is ERR or OK.

• int printFlt(float f) – prints the floating point number (f) with left-alignment. Printing sign for a negative number is mandatory while for a positive number it is not required. However, decimal point should be printed to differentiate it from an integer number. Returns the number of characters printed (on success) or ERR (on failure).

Use only the following header file for your C program.

/* Header file for Assginemnt 2: Name it as myl.h */

#ifndef MYL H

#define MYL H

#define ERR 0

#define OK 1

int printStr(char *); int printInt(int); int readInt(int *); int readFlt(float *); int printFlt(float);

#endif

1

2. Name of your .c file as ass2 roll.c, where roll is your roll number. Include only ”myl.h” as your header file. It should not contain the function main(). Write your main() function in a separate file. Use Makefile to test your library. Move your main.c, myl.h, Makefile and ass2 roll.c in folder asgn2 roll. Zip the folder and upload as a single file in the moodle server.

2
