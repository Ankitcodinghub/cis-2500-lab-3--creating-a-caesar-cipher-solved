# cis-2500-lab-3--creating-a-caesar-cipher-solved
**TO GET THIS SOLUTION VISIT:** [CIS*2500 Lab 3- Creating a Caesar Cipher Solved](https://www.ankitcodinghub.com/product/cis2500-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114972&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CIS*2500 Lab 3- Creating a Caesar Cipher Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Read about Caesar Ciphers from the wikipedia http://en.wikipedia.org/wiki/Caesar_cipher.

Create a program called copy_text that takes two command line arguments: the first argument is the name of the file to be copied; the second argument is the name of the new file. If the second argument is missing, copy the file to stdout. If both arguments are missing, the program should read from stdin and print to stdout.

Example:

copy_text original.txt theCopy.txt

The most common of the Caesar Ciphers still in use is Rot13, which uses a shift of 13. Write a program that takes in input from a file and prints it into a new file encoded using Rot13. Only Rot13 letters, leave digits, white space and punctuation unchanged. The file names should be command line arguments as specified for the copy_text program from Question 1.

Name this program rot13.c

Encode a message from a file using the Caesar Cipher with a shift as entered as a command line argument. The results should be placed in a new file. If the shift is 0, the program should just produce a copy of the file (similar behavior as question 1). The program should accept positive and negative shift values (positive shifts add the absolute shift amount; negative shifts subtract the absolute shift amount). If a command line argument is entered that is not a number, or is a number whose absolute value is greater than or equal to 26, print an appropriate error message to the screen; but do not create a new file (use fprintf(stderr, “%s “, “your message”)to accomplish this).

The program should take in a three command line arguments:

• the shift number o an integer between -25 and 25 inclusive

• -F input_file_name o the name of the input file

o there is usually a space between -F and the file name

§ but there doesn’t have to be – you have to handle both cases

• -O output_file_name o the name of the output file

o again, there is usually a space between -O and the file name

§ but there doesn’t have to be – you have to handle both cases

The shift number does not have a option name; it is just a number

• If the -O argument is missing, output should go to stdout.

• If the -F argument is missing, the program should read from stdin.

• If no shift number is present, the program should use a Rot13 encoding.

Name this program encode.c If you have this program working, you do not need to hand in rot13.c, which will be marked by running encode.c with no shift number.

NOTES (IMPORTANT INFO … READ CAREFULLY)

2. Your source code should be properly formatted and meaningful variable names should be used.

3. Your source code should contain brief comments describing the functionality and the major components of each procedure. Any complex structures should also be commented.

4. If you hand in an assignment that does not compile you will get a mark of zero.

5. All work in this course is to be done independently.

7. You should also submit your source code file (.c and .h files) and a makefile to the L3 submission link in the course website. Note: this is not a substitute for in person grading.
