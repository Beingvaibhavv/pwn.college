# file globbing

## matching with ?
Next, let's learn about ?. When it encounters a ? character in any argument, the shell will treat it as a single-character wildcard. This works like *, but only matches one character. For example:

hacker@dojo:~$ touch file_a
hacker@dojo:~$ touch file_b
hacker@dojo:~$ touch file_cc
hacker@dojo:~$ ls
file_a	file_b	file_cc
hacker@dojo:~$ echo Look: file_?
Look: file_a file_b
hacker@dojo:~$ echo Look: file_??
Look: file_cc
Now, practice this yourself! Starting from your home directory, change your directory to /challenge, but use the ? character instead of c and l in the argument to cd! Once you're there, run /challenge/run for the flag!

### Solve
**Flag:** `pwn.college{MPgCNORg04RDnMHljRZXkrPIQl4.QXyIDO0wSMzAzNzEzW}`

just followed the description and got the flag
got the path from the terminal itself


```bash
cd /?ha??enge
/challenge/run
```

### New Learnings
learnt to write and use paths on the terminal

### References 
none
