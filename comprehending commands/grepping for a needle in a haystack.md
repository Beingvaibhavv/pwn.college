# Comprehending Commands

## grepping for a needle in a haystack
Sometimes, the files that you might cat out are too big. Luckily, we have the grep command to search for the contents we need! We'll learn it in this challenge.
There are many ways to grep, and we'll learn one way here:
hacker@dojo:~$ grep SEARCH_STRING /path/to/file
Invoked like this, grep will search the file for lines of text containing SEARCH_STRING and print them to the console.
In this challenge, I've put a hundred thousand lines of text into the /challenge/data.txt file. grep it for the flag!
HINT: The flag always starts with the text pwn.college.


### Solve
**Flag:** `pwn.college{AnqTAnlhN9cPGjBZyrvEyf4ugNl.QX3EDO0wSMzAzNzEzW}`

just followed the description and got the flag
got the path from the terminal itself
used grep command


```bash
ls
cd /
cd challenge
grep pwn.college data.txt
```

### New Learnings
learnt to write and use paths on the terminal
used grep command to capture the flag

### References 
none
