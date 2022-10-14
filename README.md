# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: 
First we need to open the required file from one file to another file.
### Step 2: 
Using key word "with" to open the required file.
 
### Step 3:
Again using the with keyword to open the empty file.

### Step 4: 
The empty file is open by using "w" which is used to write only.

### Step 5: 
The for fuction is used to take the each line from the main file.

### Step 6: 
Write() is used to write the lines of main file to the empty file or do the directed file.

### Step 7: 
Print the output.

## PROGRAM:
```
Developed By : Kamalesh SV
Register Number : 22001133
with open("file.txt","r") as fp:
    with open("file1.txt","w") as fp1:
        v = fp.read()
        fp1.write(v)
```
### OUTPUT:

![OUTPUT](./output1.png)
![OUTPUT](./output2.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
