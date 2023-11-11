# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module

### Step 2: 
Open the file with sys.argv[1]
 
### Step 3: 
Use the for loop to select the content in file

### Step 4:
Use split function to to separate the file content into words or strings

### Step 5: 
Count the length of the words using len

### Step 6:
Print the number of words

## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: HARISH G
RegisterNumber: 23000630

import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```

### OUTPUT:
![image](https://github.com/Harish2404lll/command-line-arguments-to-count-word/assets/141472096/77e53109-4973-4c84-a3d9-632f6f3b8b8c)

![image](https://github.com/Harish2404lll/command-line-arguments-to-count-word/assets/141472096/0843d4db-a34b-4c1b-a191-e4c0b6299529)

![image](https://github.com/Harish2404lll/command-line-arguments-to-count-word/assets/141472096/90a35392-341f-4738-84ba-fb652c4e7729)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
