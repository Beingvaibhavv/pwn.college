
# Comprehending Commands

## touching files
Of course, you can also create files! There are several ways to do this, but we'll look at a simple command here. You can create a new, blank file by touching it with the touch command:

hacker@dojo:~$ cd /tmp
hacker@dojo:/tmp$ ls
hacker@dojo:/tmp$ touch pwnfile
hacker@dojo:/tmp$ ls
pwnfile
hacker@dojo:/tmp$
It's that simple! In this level, please create two files: /tmp/pwn and /tmp/college, and run /challenge/run to get your flag!


### Solve
**Flag:** `pwn.college{QHv3ibvy-Kd1Q096Jka-ZMPAgC7.QXwMDO0wSMzAzNzEzW}`

just followed the description and got the flag
got the path from the terminal itself
created two files using touch


```bash
cd /
cd /tmp
touch pwn
touch college
cd /
/challenge/run
```

### New Learnings
learnt to write and use paths on the terminal
used touch command to create new files

### References 
none
