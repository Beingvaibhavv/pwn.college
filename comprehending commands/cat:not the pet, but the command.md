# Comprehending Commands

## cat not the pet, but the command
One of the most critical Linux commands is cat. cat is most often used for reading out files, like so:

hacker@dojo:~$ cat /challenge/DESCRIPTION.md
One of the most critical Linux commands is `cat`.
`cat` is most often used for reading out files, like so:
cat will concatenate (hence the name) multiple files if provided multiple arguments. For example:

hacker@dojo:~$ cat myfile
This is my file!
hacker@dojo:~$ cat yourfile
This is your file!
hacker@dojo:~$ cat myfile yourfile
This is my file!
This is your file!
hacker@dojo:~$ cat myfile yourfile myfile
This is my file!
This is your file!
This is my file!
Finally, if you give no arguments at all, cat will read from the terminal input and output it. We'll explore that in later challenges...

In this challenge, I will copy the flag to the flag file in your home directory (where your shell starts). Go read it with cat!

### Solve
**Flag:** pwn.college{ob_QTRQ4apaSmGVIwFXY4r4iuWN.QXxcTN0wSMzAzNzEzW}

just followed the description and got the flag
got the path from the terminal itself
used cat command


```bash
ls
cat flag
```

### New Learnings
learnt to write and use paths on the terminal
used cat command to capture the flag

### References 
none
