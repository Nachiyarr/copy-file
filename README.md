# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a new file.

### Step 2:
Open the both the files using the function"with".
 
### Step 3: 
Open the first file created in read mode.

### Step 4:
Open the second file created in append mode.

### Step 5:
Then use for loop.


### Step 6: 
Calling the function to copy the contents fron file one to file two.

## PROGRAM:

#Program to copy one contents from one file to another

#Developed by:Alagu nachiyar k

#Register no:22002084
```
with open('nachi.txt','r') as f9:
    with open('zia.txt','a') as f8:
        for line in f9:
            f8.write(line)
            
 ```


### OUTPUT:

![program 6](https://user-images.githubusercontent.com/113497340/192235366-de0cf59a-a42f-47ff-96eb-f47c9f18210f.png)

![txt1copy1](https://user-images.githubusercontent.com/113497340/192235444-3c4682d4-5992-48a9-b5e4-a04c1cd3071f.png)

![file2](https://user-images.githubusercontent.com/113497340/192235514-4514cea3-08b5-4d82-8d86-de7abb80f28e.png)





## RESULT:
Thus the program is written to copy the contents from one file to another file.
