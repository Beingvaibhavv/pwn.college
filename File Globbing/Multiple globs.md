# file globbing

## Multiple globs
So far, you've specified one glob at a time, but you can do more! Bash supports the expansion of multiple globs in a single word. For example:

hacker@dojo:~$ cat /*fl*
pwn.college{YEAH}
hacker@dojo:~$
What happens above is that the shell looks for all files in / that start with anything (including nothing), then have an f and an l, and end in anything (including ag, which makes flag).

Now you try it. We put a few happy, but diversely-named files in /challenge/files. Go cd there and run /challenge/run, providing a single argument: a short (3 characters or less) globbed word with two * globs in it that covers every word that contains the letter p.

### Solve
**Flag:** `pwn.college{wp7kXibj8Ig7m3U04_43_rtw80Q.0lM3kjNxwSMzAzNzEzW}`

just followed the description and got the flag
got the path from the terminal itself


```bash
cd /challenge/files
/challenge/run *p*
```

### New Learnings
learnt to write and use paths on the terminal

### References 
none
