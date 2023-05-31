# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Import sys module.
### Step 2:

Open the file with sys.argv[1].
### Step 3:

Use the for loop to select the content in file.
### Step 4:

Use split function to to separate the file content into words or strings.
### Step 5:

Count the length of the words using len.
### Step 6:

Print the number of words.
## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments.
Programmed by: G.Chethan Kumar
Ref.No.: 212222240022
```
```
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```
### OUTPUT:
![pyimg1](https://github.com/Gchethankumar/command-line-arguments-to-count-word/assets/118348224/3deb609f-a527-4123-b584-36046733c341)
![pyimg2](https://github.com/Gchethankumar/command-line-arguments-to-count-word/assets/118348224/662cfda5-0ce5-478d-9b4d-045cd18058e0)
![pyimg3](https://github.com/Gchethankumar/command-line-arguments-to-count-word/assets/118348224/318b6de0-5ac2-47b1-8595-87331e7776f3)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
