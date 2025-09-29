# Comprehending Commands

## making directories
We can create files. How about directories? You make directories using the mkdir command. Then you can stick files in there!

Watch:

hacker@dojo:~$ cd /tmp
hacker@dojo:/tmp$ ls
hacker@dojo:/tmp$ ls
hacker@dojo:/tmp$ mkdir my_directory
hacker@dojo:/tmp$ ls
my_directory
hacker@dojo:/tmp$ cd my_directory
hacker@dojo:/tmp/my_directory$ touch my_file
hacker@dojo:/tmp/my_directory$ ls
my_file
hacker@dojo:/tmp/my_directory$ ls /tmp/my_directory/my_file
/tmp/my_directory/my_file
hacker@dojo:/tmp/my_directory$
Now, go forth and create a /tmp/pwn directory and make a college file in it! Then run /challenge/run, which will check your solution and give you the flag!


### Solve
**Flag:** `pwn.college{kMLxXsGAPJEsyvVHMI3usP-YcpD.QXxMDO0wSMzAzNzEzW}`

just followed the instructions and used mkdir command to create a directory


```bash
cd /
cd tmp
mkdir pwn
cd pwn
touch college
cd /
/challenge/run
```

### New Learnings
used mkdir command to create a directory

### References 
none
