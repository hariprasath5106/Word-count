# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
ALGORITHM:
Step 1: Define the variable to count the number of words in the file and defined with 0.
Step 2: Open the text file using the with open keyword.
Step 3: Using r command i.e:read mode.
Step 4: Using for loop iterate the file to split the space in the words.
Step 5: The splited and stored in the variable, use len() function of the splited word variable.
Step 6: End the program.

## PROGRAM:
```
'''
Developed by: HARI PRASATH S
Register number: 212222240034
'''
fname = input('Enter file name: ')
num_word = 0
with open(fname, 'r') as f:
    for line in f:
        word = line.split ()
        num_word += len(word)
print('Number of words: ', num_word)
```
### OUTPUT:
![282809777-143c3ae5-8a47-41f7-b6db-bb206a9553cc](https://github.com/hariprasath5106/Word-count/assets/111515488/f64ea50d-ef52-4378-a983-8cae83836466)
![282809654-b3dbf776-df92-45d1-9867-524776bc7cf5](https://github.com/hariprasath5106/Word-count/assets/111515488/4438dedf-f941-452d-9094-ed73d3c29949)


## RESULT:
Thus the program is written to find the word count from a text.
