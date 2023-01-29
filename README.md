# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:From shutil import copy file

### Step 2: From sys import exit
 
### Step 3: Getting input for source file

### Step 4:  Getting input for target file

### Step 5: Giving condition for files

### Step 6: Getting statement from the user to print or not want to print

## PROGRAM:
```
Program For Copying The Contents:
Developed by: GOKUL S
RegisterNumber: 22008488

print("Enter the Name of Source File: ")

sFile = input()

print("Enter the Name of Target File: ")

tFile = input()

fileHandle = open(sFile, "r")

texts = fileHandle.readlines()

fileHandle.close()


fileHandle = open(tFile, "w")

for s in texts:

    fileHandle.write(s)
    
fileHandle.close()

print("\nFile Copied Successfully!")
```

### OUTPUT:

![Screenshot (31)](https://user-images.githubusercontent.com/121148715/215307365-6733c17f-de66-4fc4-86f3-8d2379b68c4c.png)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
