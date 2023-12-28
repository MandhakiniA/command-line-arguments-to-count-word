# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Import the sys module.

### Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

### Step 3:
Read the file using read() method.

### Step 4:
Use split() method to split the file content into words.

### Step 5:
Use len() to find the total words

### Step 6:
Run the program to determine the number of words in the file created.


## PROGRAM:
```
Developed by : A.Mandhakini
Registered number : 23010115
```
~~~
import sys
file= open(sys.argv[1])
data=file.read()
words=data.split()
print("Total Words:",len(words))
~~~
### OUTPUT:
![image](https://github.com/MandhakiniA/command-line-arguments-to-count-word/assets/150005194/53b2b8da-e55f-4a02-aeaf-589f692b4b94)
![image](https://github.com/MandhakiniA/command-line-arguments-to-count-word/assets/150005194/c32d7aef-e4c8-421d-b2ce-b851f470e2c4)





## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
