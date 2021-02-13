Name: Lauren Grieb

First, I went to ~/cis520/pintos/src/tests and ran the code "grep -r alarm-multiple *" as well as
"grep -r test_alarm_multiple *" to see which files needed to be modified. In addition, I added a 
new file named alarm-mega in the same location that alarm-multiple was in. The code was duplicated
and the number of iterations was changed from 7 to 70. After that, I started modifing the pre-existing
files. The file alarm-wait.c was given a new function, test_alarm_mega, with 70 iterations to test.
The corresponding files tests.c and tests.h also added this new function so it can get utilized.
Finally, I did a check and using "grep -r alarm-mega *" and "grep -r test_alarm_mega *" I made sure
all of the same files that appeared for alarm-multiple matched. That way I knew all of the correct
files had been modified. I ran it with a log file to output to and the code worked as the log file
displayed 70 iterations.