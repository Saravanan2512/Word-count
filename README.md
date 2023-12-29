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
 Read the text using read() function.
### Step 3: 
Then use the laptop to assign the i value in the file.
### Step 4:  
Then nxt split the words
### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.
### Step 6: 
Giving print statement for getting output
## PROGRAM:
```
''' 
Program to sort the elements in the list using the Selection Sort algorithm.
Developed by: SARAVANAN G
RegisterNumber: 23005445
'''
num_word=0
with open ("sarabpython.txt",'r') as f:
 for i in f:
   word=i.split()
   num_word+=len(word)
print("number of words ={}".format(num_word))


```

### OUTPUT:
![image](https://github.com/Saravanan2512/Word-count/assets/144979117/a7c3f5c0-ac83-48a5-ab4e-5cde277f86d3)

![Screenshot 2023-12-29 114828](https://github.com/Saravanan2512/Word-count/assets/144979117/7aa75304-4685-454a-8016-ffec4f50ea9a)


## RESULT:
Thus the program is written to find the word count from a text.
