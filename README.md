# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
To write a python program for getting the word count from a text file.
### Step 2:
Open the required file by using the function "with".
### Step 3:
Then use the laptop to assign the i value in the file.
### Step 4:
Using split function to spilt the words.
### Step 5:
Finding the given length of the words by using len() fuction.
### Step 6:
Calling the function and Printing the number of words.
## PROGRAM:
num_words=0
with open('/content/drive/MyDrive/mk',"r") as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
  print("Number of words:",num_words)
### OUTPUT:
![Screenshot 2023-12-25 113113](https://github.com/karthik-2106/Word-count/assets/150319557/60aa53ee-5e21-43d9-8f4e-004ee805f223)
![Screenshot 2023-12-25 113136](https://github.com/karthik-2106/Word-count/assets/150319557/5658b0c7-d739-43a0-923d-443ae891336d)

## RESULT:
Thus the program is written to find the word count from a text.
