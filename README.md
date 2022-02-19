# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
To write a python program for copying the contents from one file to another file.

### Step 2: 
Give a new file name to create a copy of a file content.
 
### Step 3:
Read the file and close the file.

### Step 4:
Now write the content in the new file.

### Step 5: 
When done print "File copied successfully".
### Step 6: 
End of the program.

## PROGRAM:
~~~python
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
~~~

### OUTPUT:
![word1](https://user-images.githubusercontent.com/93978702/154787601-610eea03-a1e7-4cda-8efd-3160ae859a2e.jpg)
![text1](https://user-images.githubusercontent.com/93978702/154787619-b61a4771-d3f5-4efd-873d-6767b86315e6.jpg)
![word2](https://user-images.githubusercontent.com/93978702/154787624-e6174516-f3eb-4116-8dcd-0827f2baa804.jpg)





## RESULT:
Thus the program is written to copy the contents from one file to another file.
