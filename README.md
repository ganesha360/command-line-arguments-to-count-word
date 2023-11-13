# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys
### Step 2: 
 Initially make count = 0
### Step 3: 
Open the content file using command line arguments.
### Step 4:  
By using for loop name the function as "line"
### Step 5: 
Split the line using .split
### Step 6: 
Count the length of the word and print it
## PROGRAM:
```PYTHON
Program for getting the word count from the contents of a file using command line arguments
Developed by: GANESH R
RegisterNumber: 212222240029

import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```
### OUTPUT:

![PY6](https://github.com/ganesha360/command-line-arguments-to-count-word/assets/120884552/afb06c87-7547-4420-9d72-d45160fdc1ac)

![PY7](https://github.com/ganesha360/command-line-arguments-to-count-word/assets/120884552/7e3f78dc-780e-486d-ad38-6a9b8c99d3a0)

![PY8](https://github.com/ganesha360/command-line-arguments-to-count-word/assets/120884552/482491e5-6b48-4817-b312-852ff1b7a209)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
