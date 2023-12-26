# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Create a file with .txt file extension

### Step 2: Add some texts in that file
 
### Step 3:Create a python file
### Step 4: Write a code to count the number of words in that file. Step 

### Step 5: Run the program

### Step 6::Display the output 

## PROGRAM:
```
def program():
    count=0
    with open("text.txt","r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Total number of words:",count)
program()
```
### OUTPUT:
![mat ex 5a](https://github.com/pochireddyp/Word-count/assets/150232043/8b6a879a-ed3e-40cb-aa2f-35210b9811b3)
![image](https://github.com/pochireddyp/Word-count/assets/150232043/99e00830-6637-48cb-bbf0-eb7b2ac12a60)



## RESULT:
Thus the program is written to find the word count from a text.
