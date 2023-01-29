# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

## Step 5:
The content in the original file will be copied in the new file.

## Step 6:
End the program.

## PROGRAM:
## Developed by : SIVAMOHANASUNDARAM. V
## Register No : 22004168
~~~py
with open("sample.txt", "r") as firstfile:
    with open("sample2.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)
~~~

### OUTPUT:
![1](/copy%20sample.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.