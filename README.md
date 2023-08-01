# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required the from which we need to copy the text.
### Step 2: 
 Using keyword "with" to open the required file
### Step 3: 
Again using the with keyword to open the empty file
### Step 4:  
The empty file is open by using 'W' which is used to write only.
### Step 5: 
The for function is used to take each line from the main file.
### Step 6: 
Write() is used to write the lines of main file to the empty file or to the directed file.
## PROGRAM:
``````
<<<<<<< HEAD
#Developed by: Abishai K C
#Register NUmber: 23001564
f = open("C:\\User\\abish\\Desktop\\sample\\Hello world.txt","r")
=======
f = open("C:\\User\\abish\\Desktop\\sample\\Hello world.txt","r"
>>>>>>> 0c33cc2a6510fabfb45973d2a4ac00dae47f7871
d1 = f.read()
f2 = open("copy_file.txt","w+")
f2.write(d1)
f2.seek(0)
d2 = f2.read()
print(d2)
f.close()
f2.close()
``````
### OUTPUT:

![file copying](https://github.com/Abishai95141/copy-file/assets/139335314/efb7aaf0-9bde-4639-a194-99135259fa4a)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
