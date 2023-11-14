# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

### Step 1:Import sys module

### Step 2: Open the file with sys.argv[1]
 
### Step 3: Use the for loop to select the content in file

### Step 4:  Use split function to to separate the file content into words or strings

### Step 5: Count the length of the words using len

### Step 6: Print the number of words

## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: UDHAYA SANKARAN M
RegisterNumber: 212222110051

import sys
fp=open(sys.argv[1], 'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print("No of words in a file",count)
```

### OUTPUT:
![image](https://github.com/Udhayasankaran04/command-line-arguments-to-count-word/assets/119393933/bd7282d1-0d9c-4dda-95b9-880dc469bef0)
![image](https://github.com/Udhayasankaran04/command-line-arguments-to-count-word/assets/119393933/85002f07-ef5e-4094-9316-0267e4c06066)
![image](https://github.com/Udhayasankaran04/command-line-arguments-to-count-word/assets/119393933/edbdb2f7-25e2-4d75-a488-95861c35cc78)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
