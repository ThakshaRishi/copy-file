# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open fname (the file whose contents need to be copied).
### Step 2: 
Open newfile (the file to be pasted in).
### Step 3: 
Read the text from the contents need to be copied.
### Step 4:  
Write the text into the other file.
### Step 5: 
Get the input from the user
### Step 6: 
Print the output.
## PROGRAM:
```
#Developed by: Thaksha Rishi
#Register Number: 212223100058
def copy(fname,newfile):
    with open(fname,'r') as fp, open(newfile,'w') as fp1:
            data=fp.read()
            fp1.write(data)
fname=input("Enter an existing file: ")
newfile=input("Enter a name for the new file: ")
copy(fname,newfile)
```
### OUTPUT:
![Alt text](<Screenshot 2024-01-02 235027.png>)
![Alt text](<Screenshot 2024-01-02 235115.png>)
![Alt text](<Screenshot 2024-01-02 235124.png>)


## RESULT:
Thus the program is written to copy the contents from one file to another file.