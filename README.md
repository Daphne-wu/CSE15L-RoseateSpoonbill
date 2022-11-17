# CSE15L-RoseateSpoonbill
Thursday 1pm CSE15L Week 4 Lab
Using makefile and bash scripting and Debuggers (jdb) to run unit tests. Diagnose and fix bugs and commit/push code.
Using a Script to Run Many Files (output redirection, echo, and diff)



Futher descriptions:

Make a fresh clone of https://github.com/ucsd-cse15l-w22/markdown-parse
In the checkout, run make test. Notice that one test fails.
Use jdb with MarkdownParse to run just that markdown file from the command line using the main method of MarkdownParse. Take use jdb commands to get the following information and take screenshots of it:
The stack trace when the exception is happening
The local variables in getLinks when the exception is happening
Next, use jdb to run the JUnit tests. It should be similar to the java command in the makefile. You can refer to the lecture videos for a good way to do this. Again, use jdb commands to find:
The stack trace when the exception is happening
The local variables in getLinks when the exception is happening
Then, diagnose and fix the bug so that all the tests pass. Make a commit with the fix and push it, then link to the commit in your notes.

More debugging Instructions:
using ieng6.

Change findCloseParen so that it has an infinite loop (for example, remove the increment closeParen++, or change the condition). Re-run make test and verify that a test is in an infinite loop.

Practice using jdb with suspend to pause the program and show the stack trace during the loop. You should be able to identify:

Which test is triggering the infinite loop
Which line the program stopped on when the program was suspended
What the current values of all the variables are in getCloseParen at the moment the program suspended
Take a screenshot or copy/paste of your jdb session and indicate in your notes each of the three items above and how your jdb session informs you of that.
