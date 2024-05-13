# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 
### Step 1:
Create a text file with some content in it.
### Step 2: 
Open the created text file.
### Step 3: 
Create another empty text file.
### Step 4:  
Copy the content of text file to empty file using write function.

## PROGRAM
```
#To write a python program for reading content from a CSV file.
#Developed by: VIDHIYA LAKSHMI S
#Register Number: 212223230238

with open("text1.txt", 'r') as fp:
    msgl=fp.read()
with open("copy.txt", 'w') as fpl:
    fpl.write(msgl)


```
### OUTPUT:

![image](https://github.com/saravidhya/Copy-File/assets/87062069/3091bc8e-3672-481e-8448-7a29cc2d1095)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
