# file globbing

## Matching paths with []
Globbing happens on a path basis, so you can expand entire paths with your globbed arguments. For example:

hacker@dojo:~$ touch file_a
hacker@dojo:~$ touch file_b
hacker@dojo:~$ touch file_c
hacker@dojo:~$ ls
file_a	file_b	file_c
hacker@dojo:~$ echo Look: /home/hacker/file_[ab]
Look: /home/hacker/file_a /home/hacker/file_b
Now it's your turn. Once more, we've placed a bunch of files in /challenge/files. Starting from your home directory, run /challenge/run with a single argument that bracket-globs into the absolute paths to the file_b, file_a, file_s, and file_h files!

### Solve
**Flag:** `pwn.college{8JWffqRsaOhnXRnoAaxqIh1sqyh.QX0IDO0wSMzAzNzEzW}`

just followed the description and got the flag
got the path from the terminal itself


```bash
/challenge/run /challenge/files/file_[abhs]
```

### New Learnings
learnt to write and use paths on the terminal

### References 
none
