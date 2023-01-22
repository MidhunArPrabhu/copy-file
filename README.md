# COPY-FILE 

## AIM :

To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED : 
- PC
- Anaconda - Python 3.7

## ALGORITHM :

### Step 1 :

Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2 :

Read the file and store in a variable.

### Step 3 : 

Now create a new file in which we want to paste the content using write access mode.

### Step 4 :

Use write function to copy the read file that has been stored in the variable.

### Step 5 :
The content in the original file will be copied in the new file.

### Step 6 :

End the program.


## PROGRAM :
```python
Developed by: MIDHUN AZHAHU RAJA P
RegisterNumber: 22008311


with open("sample1.txt", "r") as firstfile:
    with open("sample2.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)
```

### OUTPUT :

### SAMPLE1.TXT :

![output_txt1](https://user-images.githubusercontent.com/118054670/213934264-4916aaed-ee28-45d2-9394-8bff9a33e7ef.png)

### SAMPLE2.TXT :
 
![output_txt2](https://user-images.githubusercontent.com/118054670/213934270-465b7a02-4909-4d3a-8b54-24001322d06f.png)



## RESULT :

Thus the program is written to copy the contents from one file to another file.
