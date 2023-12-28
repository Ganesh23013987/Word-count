# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Decleare number of words is 0
### Step 2: 
open it with words.txt file
### Step 3: 
Give range for i
### Step 4:  
Then nxt split the words
### Step 5: 
count the number of words
### Step 6: 
Giving print statement for getting output
## PROGRAM:
```
'''
To write a python program for getting the word count from a text.
Developed by: Ganesh.D
RegisterNumber:23013987
'''
num=0
with open("C:/Users/BSS/Documents/words.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```

### File1.txt:
<img width="308" alt="cmd line arg  in file" src="https://github.com/Ganesh23013987/Word-count/assets/147473768/d4ac8230-463c-43a9-81e6-96f979290b47">

### OUTPUT:
<img width="475" alt="cmd line arg output" src="https://github.com/Ganesh23013987/Word-count/assets/147473768/b15a800b-e661-4b5a-9299-7161e0936d17">



## RESULT:
Thus the program is written to find the word count from a text.
Then, the program code is successfully executed.
