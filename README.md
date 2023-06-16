# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the input as file name from the user.
### Step 2: 
assign number of words = 0 
### Step 3: 
open file and read it.
### Step 4:  
split the words separately by using split(
### Step 5: 
calculate the sum of the words in file.
### Step 6: 
Print the number of words.
## PROGRAM:
```
# Program to count the words in a file
# Developed by: Chandrasekar S
# Register number: 212222230025

fname=input("enter the file name:")
num_words=0
with open(fname,'r') as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print("Number of words:",num_words) 
```

### OUTPUT:
![image](https://github.com/ChandrasekarS22008273/Word-count/assets/119643845/d3cc1714-f95d-4a7c-aedc-91b2c8b62c81)



## RESULT:
Thus the program is written to find the word count from a text.
