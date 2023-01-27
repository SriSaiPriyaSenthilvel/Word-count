# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Get an input as enter the file name.

### Step 2: Have the number of words as zero initially.
 
### Step 3: Open the file in read mode.

### Step 4:  Iterate the number of words using for loop.

### Step 5: Find the length of the words given in the file and store in the variable num_words.

### Step 6: Print the following variable using print function.

## PROGRAM:
```
Python program to find the count of number of words present in the given file.
Program developed by: Sri Sai Priya.S
Reference number: 22006141

fname=input("Enter the file name:")
num_words=0
with open(fname,'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print("Number of words: ",num_words)
```
### OUTPUT:
![output](/Screenshot%20from%202023-01-27%2011-06-19.png)


## RESULT:
Thus the program is written to find the word count from a text.
