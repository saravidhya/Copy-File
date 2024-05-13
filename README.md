# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Load the CSV into a DataFrame.

### Step 2: 
 Print the number of contents to be displayed using df.head().

### Step 3: 
The number of rows returned is defined in Pandas option settings.
### Step 4:  
Check your system's maximum column with the pd.options.display.max_column statement.

### Step 5: 
Increase the maximum number of rows to display the entire DataFrame

### Step 6: 
End the program.

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
