# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:Import the sys module.
<br>
Step 2:Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
<br>
Step 3:Read the file using read() method.
<br>
Step 4:Use split() method to split the file content into words.
<br>
Step 5:Use len() to find the total words.
<br>
Step 6:Run the program to determine the number of words in the file created.
## PROGRAM:
```
# Python program for getting the word count from the contents of a file using command line arguments.
# Developed by: M Ashwin Akash
# Register number: 23009906
import sys
fp= open(sys.argv[1])
data=fp.read()
words=data.split()
print("Total Words:",len(words))
```
### OUTPUT:
![n0](https://github.com/AshwinAkash24/command-line-arguments-to-count-word/assets/144979248/9d460812-7c2b-48d4-95f9-4973f3363e46)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
