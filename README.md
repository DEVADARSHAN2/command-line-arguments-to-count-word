# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name using command arguments.
### Step 2: 
Now read the content in the file.
### Step 3: 
Use split().
### Step 4:  
Now read the no.of words in file.
### Step 5: 
Print number of words present in given file.
### Step 6: 
End of the program.
## PROGRAM:
```
DEVELOPED BY: DEVDARSHAN A S
REGISTER NO: 212222110007

import sys
fp= open(sys.argv[1])
data=fp.read()
words=data.split()
print("Total Words:",len(words))
```
### OUTPUT:
![image](https://github.com/DEVADARSHAN2/command-line-arguments-to-count-word/assets/119432150/d46de6a1-cb88-40db-8e50-cfd8d33b6d76)
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
