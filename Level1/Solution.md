### #Main Problem
1. Locate the file called "-" and find the password for next level in there
---
<p>This is a bit tricky since the file is named "-" usually - in linux is used in flags and parameters, so i 
 have to tell the program that this is a file :D !</p>

---
### #Theory:
<p>To solve this level I just need to learn about paths, there are two type of path in filesystem absolute file system
relative path.</p>

<p>**Fun fact: I can use either paths**</p>

### #Finding the Password:
<p>It's too much time-consuming to put ScreenShot, so I will just write the step and command</p>

1. Use `ls` command to find the file in the home directory.
2. now I use relative path to specify its location in cat command,
   it should look something like this: `cat ./"-"`
3. Copyed the password for login into next level.

### #Things I have learned
1. There are two ways I can specify the location of a file.
2. "-" is not preferred to name a file cuz it's used in flags and parameters