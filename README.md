Download Link: https://assignmentchef.com/product/solved-cpe211-project-7
<br>
<strong>                                              </strong>

<h2>&lt;Project 7 Directions&gt;</h2>







Using your favorite text editor, type your solution and save it as a file named <strong>Project_07.cpp</strong> within your <strong>CPE211_FALL18/Project_07</strong> directory.  If there are syntax errors, correct them and compile again.  Once your program successfully compiles, run it and verify that the output for your modified program matches the output from the solution executable.




<strong><em><u>NOTE: make sure that you do not change the order in which the information is entered.  An</u></em></strong><strong><em> <u>automatic script is used to process all lab submissions, and if the order of the input</u> <u>information is modified, the script will not work properly with your program.</u></em></strong>

<strong> </strong>

<h2>&lt;Project 7 Hints&gt;</h2>




<ul>

 <li>Go over the slides for this project</li>

 <li>Run the sample solution (not just the comparison script)</li>

</ul>




<ul>

 <li>Use a priming read to read the first character of the input file (outside of outer loop)</li>

 <li>Verify if the input file is empty or not. For an empty input file print out the appropriate message</li>

 <li>Use 2 nested loops to read in the characters.

  <ul>

   <li>The outer loop is looking for the end of the file and is checked on a line by line basis</li>

   <li>The inner loop is reading a line character by character and looking for the new line character that signals the end of the line</li>

  </ul></li>

 <li>Be careful with the termination of the inner loop when a new line character is read – make sure that it is counted in the other category.</li>

 <li>Set up of the nested loop logic is important. Make sure that all characters read are counted and that no characters are skipped.  This looping structure requires some thought to be done correctly</li>

</ul>




<ul>

 <li>Use the header file <strong>cctype</strong> to make use of some functions that tell the type of character stored in a char variable. See Below.</li>

 <li>Technically correct programs will have at least 5 header files.</li>

</ul>




<ul>

 <li>Use integer variables to hold the counted values. Need two sets of variables to hold the character type counts.  One set is for the characters on each line.  The other one is for holding the totals of each type of character for the entire input file.</li>

 <li><strong>The sample output is <u>left justified</u> with a field width of 15 for the line number column and 10 for the next 4 columns. </strong></li>

 <li>For an empty input file, the empty input file message only is printed.</li>

</ul>




<ul>

 <li>After a new line character is read, the individual line counts are output and the total amounts for the program are updated with the counts from the individual lines.</li>

 <li>Look at the slides for further information on the project</li>

</ul>




<ul>

 <li><strong>To reset a file stream variable, place the following statement as shown into your program at the location where you want to reset the stream:</strong></li>

</ul>

File_stream_var.clear();




Where File_stream_var is the name of the file stream variable you use in your program (i.e. inFile, outFile, etc).




<ul>

 <li><strong>There are 50 dashes</strong> separating the line counts from the totals line</li>

 <li><strong>cctype</strong> header file contains the following functions. These functions return true or false values and each requires a character as the argument in the function call o isalpha(charVar) – returns true if the character in charVar is a letter o isdigit(charVar) – returns true if the character in charVar is a digit(number)</li>

</ul>