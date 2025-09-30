# Practicing Piping

## redirecting output
First, let's look at redirecting stdout to files. You can accomplish this with the > character, as so:

hacker@dojo:~$ echo hi > asdf
This will redirect the output of echo hi (which will be hi) to the file asdf. You can then use a program such as cat to output this file:

hacker@dojo:~$ cat asdf
hi
In this challenge, you must use this output redirection to write the word PWN (all uppercase) to the filename COLLEGE (all uppercase).

### Solve
**Flag:** `pwn.college{8Dqdni2Bxk5m9win-fbX7AJiuzS.QX0YTN0wSMzAzNzEzW}`

just followed the description and got the flag
got the path from the terminal itself


```bash
echo PWN > COLLEGE
```

### New Learnings
learnt to write and use paths on the terminal

### References 
none
