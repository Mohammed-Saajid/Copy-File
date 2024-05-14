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

### Step 5: 

End the program.



## PROGRAM:

```
#To write a python program for reading content from a CSV file.
#Developed by: MOHAMMED SAAJID S
#Register Number: 212223240093

with open("text1.txt","r") as fp:
    msg1=fp.read()
with open("copytxt","w") as fp1:
    fp1.write(msg1)

```

### OUTPUT:



![pythonexp11ii](https://github.com/Mohammed-Saajid/Copy-File/assets/141727149/44f59c76-7b2f-405a-a9fc-95d5afeab2a2)

![pythonexp11iii](https://github.com/Mohammed-Saajid/Copy-File/assets/141727149/d25ad1e7-5772-4432-ba1f-1a934a8b7aa3)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
