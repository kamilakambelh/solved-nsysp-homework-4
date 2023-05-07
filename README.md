Download Link: https://assignmentchef.com/product/solved-nsysp-homework-4
<br>
This homework focuses on system programming and pipe.

<strong>Part 1: </strong>

<ol>

 <li>Write, compile, and run a program named <strong>hostinfo </strong>that prints out system information in the following format. Sample output:</li>

</ol>




<ol start="2">

 <li>Write, compile, and run a program named <strong>mydate </strong>that prints out the day and time in the following format. Sample output:</li>

</ol>




<ol start="3">

 <li>Write a program called <strong>printdir </strong>that prints the current directory. Determine what size buffer to pass to <strong>getcwd() </strong>for dynamic allocation.(<strong>Do not </strong>use pwd().) Sample output:</li>

</ol>




<ol start="4">

 <li>Write a program called <strong>mycat </strong>that is a simple version of the program cat. The program takes exactly one file name as argument; you should open it for reading and display its contents to the screen. Check that there is exactly one argument</li>

</ol>

(argc == 2) and if not, display the usage message ”Usage: mycat filename”. Sample output:




<ol start="5">

 <li>Write <strong>pipe_ls </strong>to practice using <strong>pipe() </strong>and <strong>dup()</strong>. Have your process start ls (using <strong>fork() </strong>and <strong>exec()</strong>) but read the output from ls over a pipe. The ls program writes output on descriptor 1, so some work has to be done to get the pipe connected.</li>

</ol>

Write what you read on the pipe to <strong>stdout</strong>.

Sample output:







<strong>Part 2: </strong>

<ol>

 <li>Edit the <strong>c </strong>file to recognize <strong>cd</strong>, <strong>pwd</strong>, <strong>id</strong>, <strong>hostname </strong>and <strong>builtin</strong>. Write functions implementing these commands, and compile then into your shell. The <strong>builtin </strong>command lists the functions built into your shell.</li>

</ol>

<em>Files provided: </em>

<em>builtin.c, parse.c, shell.c, shell.h </em>Sample output:







<ol start="2">

 <li>Modify the <strong>c </strong>file to recognize standard input and <strong>redirect_out.c </strong>file to recognize standard output. Add code to the <strong>pipe_present.c </strong>file to check for the pipe symbol. Add code to the <strong>pipe_command.c </strong>file to create a process to execute each of the pipe. Modify <strong>is_background.c </strong>to check the “&amp;” symbol. Alter the <strong>run_command.c </strong>file to call these functions.</li>

</ol>

<em>Files provided: redirect_in.c, redirect_out.c, run_command.c, pipe_present.c, pipe_command.c, is_background.c </em>Sample output:




<strong>Part 3: </strong>

<ol>

 <li>The first look up project lab familiarizes you with the format of the dictionary by completing the <strong>c </strong>program that creates the dictionary of fixed-length records (fixrec) from a file of variable-length entries (dict). Add code to <strong>convert.c </strong>to change an editable file into a fixed-length record format.</li>

</ol>

<em>File provided: </em>

<em>convert.c, dict.h, dict </em>Sample output:










<ol start="2">

 <li>Add code to the <strong>c </strong>file to do a simple linear search through a file of fixed length records. Link with <strong>main.c</strong>, the user interface module.</li>

</ol>

<em>File provided: lookup1.c, main.c </em>Sample output:


