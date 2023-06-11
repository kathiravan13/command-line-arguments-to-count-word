# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:Step 1:
Import the sys module.

Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

Step 3:
Read the file using read() method.

Step 4:
Use split() method to split the file content into words.

Step 5:
Use len() to find the total words.

Step 6:
Use len() to find the total words.

## PROGRAM:
'''Program to count the words in a file
Developed by: kathiravan.p
Register Number: 212222230063
'''
import sys
count=0
fp=open(sys.argv[1],'r')
for line in fp:
    list1=line.split()
    count+=len(list1)
print("no of words in a file",count)
### OUTPUT:

![5b](https://github.com/kathiravan13/command-line-arguments-to-count-word/assets/119831303/18f5c211-fc03-4e72-b450-941303c46505)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
