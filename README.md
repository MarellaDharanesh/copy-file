# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:
##Step 1:
First we need to open the required file form which we need to copy the text.Again using the with keyword to open the empty file.

## Step 2:
Using keyword "with" to open the requied file.

## Step 3:
Again using the with keyword to open the empty file.

## Step 4:
The empty file is open by using 'W' which is used to write only.

## Step 5:
The four function is used to take each line from the main file.

## Step 6:
The four function is used to take each line from the main file.

## Step 7:
Print the output.
## PROGRAM:
```
'''
Program for copying the contents from one file to another file.
Developed by: Marella Dharanesh
#RegisterNumber:22000785
'''
with open("git.txt","r") as f1:
    with open("MyFile.txt","a") as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:
![WhatsApp Image 2023-01-24 at 19 50 27](https://user-images.githubusercontent.com/118707669/214319760-57de48b6-0ebd-41e3-bd33-f82029bc54db.jpg)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
