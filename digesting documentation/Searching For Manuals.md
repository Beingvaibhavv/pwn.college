# digesting documentation

## Searching For Manuals
This level is tricky: it hides the manpage for the challenge by randomizing its name. Luckily, all of the manpages are gathered in a searchable database, so you'll be able to search the man page database to find the hidden challenge man page! To figure out how to search for the right manpage, read the man page manpage by doing: man man!

HINT 1: man man teaches you advanced usage of the man command itself, and you must use this knowledge to figure out how to search for the hidden manpage that will tell you how to use /challenge/challenge

HINT 2: though the manpage is randomly named, you still actually use /challenge/challenge to get the flag!


### Solve
**Flag:** `pwn.college{IntwTsHD5QPHw2gG5Rd4zXCiYsI.QX2EDO0wSMzAzNzEzW}`

just followed the description and got the flag
got the path from the terminal itself
read man man page and identified the the ntwswgdzis condition
read ntwswgdzis page and got the flag

```bash
cd /
man man
man ntwswgdzis
/challenge/challenge ----ntwswg 525
```

### New Learnings
learnt to write and use paths on the terminal
used man command to capture the flag

### References 
none
