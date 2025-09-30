# Practicing Piping

## Redirecting more output
Aside from redirecting the output of echo, you can, of course, redirect the output of any command. In this level, /challenge/run will once more give you a flag, but only if you redirect its output to the file myflag. Your flag will, of course, end up in the myflag file!

You'll notice that /challenge/run will still happily print to your terminal, despite you redirecting stdout. That's because it communicates its instructions and feedback over standard error, and only prints the flag over standard out!

### Solve
**Flag:** `pwn.college{Mq8SY3c1_0Pb6H0ddW_LK1OsAfG.QX1YTN0wSMzAzNzEzW}`

just followed the description and got the flag
got the path from the terminal itself


```bash
/challenge/run > myflag
cat myflag
```

### New Learnings
learnt to write and use paths on the terminal

### References 
none
