# cmsc203-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CMSC203 Assignment 3 Solved](https://mantutor.com/product/cmsc203-solved-8/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113907&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC203 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Write a Java program to encrypt and decrypt a phrase using two similar approaches, each insecure by modern standards.

The first approach is called the Caesar Cipher, and is a simple “substitution cipher” where characters in a message are replaced by a substitute character.

• Using loops

• String and character processing

• ASCII codes

Data Manager class – CryptoManager.java

• Implement each of the methods specified in this file. This version as provided will print error messages in the console, because they are just the skeletons.

• Each of the methods are static, so there is no need to create an instance of the Data Manager.

• Document each of your methods with a simple description and document the class with a simple description and your name using in-line comments (//…). (Just a short sentence fragment will suffice for each documentation string.)

• The methods are described below.

• public static boolean stringInBounds (String plainText);

This method determines if a string is within the allowable bounds of ASCII codes according to the LOWER_BOUND and UPPER_BOUND characters. The parameter plainText is the string to be encrypted. The method returns true if all characters are within the allowable bounds, false if any character is outside.

• public static String encryptCaesar(String plainText, int key);

This method encrypts a string according to the Caesar Cipher. The integer key specifies an offset and each character in plainText is replaced by the character the specified distance away from it. The parameter plainText is an uppercase string to be encrypted. The parameter key is an integer that specifies the offset of each character. The method returns the encrypted string.

• public static String decryptCaesar(String encryptedText, int key);

This method decrypts a string according to the Caesar Cipher. The integer key specifies an offset and each character in encryptedText is replaced by the character “offset” characters before it. This is the inverse of the encryptCaesar method. The parameter encryptedText is the encrypted string to be decrypted, and key is the integer used to encrypt the original text. The method returns the original plain text string.

• public static String encryptBellaso(String plainText, String bellasoStr);

This method encrypts a string according to the Bellaso Cipher. Each character in plainText is offset according to the ASCII value of the corresponding character in bellasoStr, which is repeated to correspond to the length of plaintext. The method returns the encrypted string.

• public static String decryptBellaso(String encryptedText, String bellasoStr); This method decrypts a string according to the Bellaso Cipher. Each character in encryptedText is replaced by the character corresponding to the character in bellasoStr, which is repeated to correspond to the length of plainText. This is the inverse of the encryptBellaso method. The parameter encryptedText is the encrypted string to be decrypted, and bellasoStr is the string used to encrypt the original text. The method returns the original plain text string.

• Add additional methods if you wish to make your logic easier to follow.

GUI Driver class – (provided)

• A Graphical User Interface (GUI) is provided. Be sure that the GUI will compile and run with your methods. The GUI will not compile if your method headers in CryptoManager.java are not exactly in the format specified. When you first run the application, your methods will all throw exceptions, which will be caught by the GUI and printed out in the console.

• Do not modify the GUI.

• The GUI takes care of capitalizing your input strings.

JUnit Test/Test Driver

• Once your methods are implemented, run the test driver. Ensure that the driver file results in the following output, as shown in RED (of course the output will not be in red when you run the test driver):

“THIS TEST SHOULD SUCCEED” Is it in bounds? true

“THIS TEST THAT SHOULD FAIL BECAUSE { IS OUTSIDE THE RANGE” Is it in bounds? false

“This test should fail because of lowercase letters” Is it in bounds? false

Caesar cipher of “THIS IS ANOTHER TEST” should return “WKLV#LV#DQRWKHU#WHVW”:

WKLV#LV#DQRWKHU#WHVW

Bellaso cipher of “THIS IS ANOTHER TEST” should return “WUVR9F#N!RF88U-‘HED”:

WUVR9F#N!RF88U-‘HED

Caesar decryption of “WKLV#LV#DQRWKHU#WHVW” should return “THIS IS ANOTHER TEST”:

THIS IS ANOTHER TEST

Bellaso decryption of “WUVR9F#N!RF88U-‘HED” should return “THIS IS ANOTHER TEST”: THIS IS ANOTHER TEST

• Run the JUnit test file (provided). Ensure that the JUnit tests all succeed. • Include CryptoTest.java and CryptoManagerTest.java with the rest of your submission.

The first approach is called the Caesar Cipher, and is a simple “substitution cipher” where characters in a message are replaced by a substitute character. The substitution is done according to an integer key which specifies the offset of the substituting characters. For example, the string ABC with a key of 3 would be replaced by DEF.

If the key is greater than the range of characters we want to consider, we “wrap around” by subtracting the range from the key until the key is within the desired range. For example, if we have a range from space (‘ ‘) to ‘_’ (i.e., ASCII 32 to ASCII 95), and the key is 120, we note that 120 is outside the range. So we subtract 95-32+1=64 from 120, giving 56, which in ASCII is the character ‘8’. If the key is even higher, we can subtract the range from the key over and over until the key is within the desired range.

Since our specified range does not include lower-case letters, the GUI (provided) will change strings to upper case. You can find the ASCII table at http://www.asciitable.com/, or many other places on the Internet.

So for the string ABCDEFG and the key word CMSC, the key word is first extended to the length of the string, i.e., CMSCCMS. Then A is replaced by ‘A’ offset by ’C’, i.e., ASCII 65+67=132. The range of the characters is also specified, and again we’ll say ‘ ‘ to ‘_’ (i.e., ASCII 32 to ASCII 95). The range is then 95-32+1=64. In our example, the offset is “wrapped” by reducing 132 by the range until it is the allowable range. 132 is adjusted to 132-64=68, or character ‘D’ in the encrypted phase. Then the same logic is applied to the second letter of the plain text ‘B’ shifted by the second letter of the key word ‘M’. This results in the character ‘O’ as the second letter in the encrypted phase, and so on. In each approach, if the resulting integer is greater than 95 (the top of our range), the integer is “wrapped around” so that it stays within the specified range. The result is “DOVGHSZ”.

Your program will implement several methods that are specified in the file “CryptoManager.java”. A Graphical User Interface is provided, as well as a test file, that you should use to make sure your methods work correctly. Be sure to follow the naming exactly, as the tests will not work otherwise.

• Turn in pseudo-code for each of the methods specified in CryptoManager.java. Your pseudo-code should be part-way between English and java. There is no need to spell out all the details of variable declaration, etc., but by the same token, the pseudo-code needs to have enough detail that a competent Java programmer could implement it.

• Turn in a test table with o at least two tests for the Caesar Cipher o at least two tests for the Bellaso Cipher o at least one string that will fail because it has characters outside the acceptable ones.

• Learning Experience: highlight your lessons learned and learning experience from working on this project. o What have you learned? o What did you struggle with? o What will you do differently on your next project? o Include what parts of the project you were successful at, and what parts (if any) you were not successful at.

• GitHub: In your repository (see Lab 1), upload the files initially provided in Blackboard for the project. When you are finished with the design and programming, upload your Word file and java file. You will want to upload these files as contents of a directory so that future uploads can be kept separate. Take and submit a screen shot of the GitHub repository.

Notes:

• Proper naming conventions: All constants, except 0 and 1, should be named. Constant names should be all upper-case, variable names should begin in lower case, but subsequent words should be in title case. Variable and method names should be descriptive of the role of the variable or method. Single letter names should be avoided.

Indentation: It must be consistent throughout the program and must reflect the control structure

Submission Detail

Submit the following files:

• Word document with a name FirstInitialLastName_Assignment3.docx should include:

o Pseudocode for each of the methods specified in CryptoManager.java.

o Test Plan o Screen snapshots of outputs from Eclipse based on your Test Plan o Screen snapshot of GitHub submission o Lessons Learned o Check List

• A zip file will only contain the .java files and will be named:

FirstInitialLastName_Assignment3_Moss.zip. This .zip will not have any folders in it – only .java files.

Here’s an example for Assignment 3:

R_Brown_Assignment2.docx

R_Brown_Assignment2_Moss.zip [a compressed file containing only the following]

CryptoManager.java

CryptoTest.java

CryptoManagerTest.java

Test your program with at least 3 test cases. Make sure your tests cover all the possible scenarios.

Input text Input Key Encrypted (method1) Encrypted (method2) Decrypt (method1) Decrypt (method2)

Grading Rubric

See attachment: CMSC203 Assignment 3 Rubric_Summer20.xlsx

Assignment 3 Check List

# Y/N Comments

1. Assignment files:

• FirstInitialLastName_ Assignment#_Moss.zip &lt;Yes or No&gt;

• FirstInitialLastName_Assignment#.docx/.pdf &lt;Yes or No&gt;

• Source java files &lt;Yes or No&gt;

2. Program compiles &lt;Yes or No&gt;

3. Program runs with desired outputs related to a Test Plan &lt;Yes or No&gt;

4. Documentation file:

• Comprehensive Test Plan &lt;Yes or No&gt;

• Screenshots for each Test case listed in the Test Plan &lt;Yes or No&gt;

• Screenshots of your GitHub account with submitted Assignment# (if required) &lt;Yes or No or N/A&gt;

• UML Diagram (if required) &lt;Yes or No or N/A&gt;

• Algorithms/Pseudocode (if required) &lt;Yes or No or N/A&gt;

• Flowchart (if required) &lt;Yes or No or N/A&gt;

• Lessons Learned &lt;Yes or No&gt;

• Checklist is completed and included in the Documentation &lt;Yes or No&gt;
