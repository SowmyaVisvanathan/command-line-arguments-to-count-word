# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First import sys.
### Step 2: 
Keep the variable count as empty.
### Step 3: 
Open the file and access the file in reading mode.
### Step 4:  
Iterate the loop using for loop in line.split().
### Step 5: 
Using if condition increment the value.
### Step 6: 
Print the variable count and close the file
## PROGRAM:
```
import sys 
count = {}

with open (doc2, 'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count [word] = 1 
            else:
                count [word]+=1

print (count) 
f.close()
```
### OUTPUT:
![output](/out2.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
