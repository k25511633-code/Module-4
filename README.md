## Classes and Objects in Python: Calculate the Area of a Circle
## Aim
To write a Python program that calculates the area of a circle based on the radius provided by the user. This program uses a class named cse and a method mech to perform the calculation.

## Algorithm

Get user input: Take the radius of the circle as input from the user.
Define the class: Create a class named cse.
Define the method: Inside the class, define the method mech to calculate the area of the circle using the formula:
Area = pi *r^2
Execute the program: Create an object of the class and call the method with the radius value.

## Program
```
import math

class cse:
    def mech(self, radius):
        area = math.pi * radius ** 2
        print(f"Area of circle: {area:.2f}")


r = float(input())

obj = cse()
obj.mech(r)
```
### Output

<img width="1034" height="262" alt="{7FA31A39-0066-42E7-9D9B-9E9C5DF1AC43}" src="https://github.com/user-attachments/assets/27c80547-3afe-4b23-8b93-8dc7f6adca72" />


## Result
Thus the program executed successfully.

## Dictionary Operations in Python: Merging Two Dictionaries
## Aim
To write a Python program that merges two dictionaries and combines their key-value pairs.

## Algorithm

Define two dictionaries dict1 and dict2 with some key-value pairs.
Define a function merge() that merges the two dictionaries using the ** unpacking operator.
The merged result will combine keys from both dictionaries. If a key exists in both, the value from dict2 will overwrite that from dict1.
Call the merge() function and print the merged dictionary.
## Program

dict1={'Ten': 10,'Twenty': 20,'Thirty': 30} 
dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50} def 
merge (dict1,dict2): 
res={**dict1 , **dict2} return 
res 
dict3=merge(dict1,dict2) 
print(dict3)
## Output

<img width="1005" height="197" alt="{1DC80B0A-CD84-4D41-8C32-D81D414168AF}" src="https://github.com/user-attachments/assets/403358f9-7dd8-441b-b27d-390513eaa401" />


## Result
thus,the program has been executed successfully.

## Dictionary-Python Program to Sort a Dictionary by Keys and Values
This Python program demonstrates how to sort a dictionary:

Alphabetically by keys
Alphabetically by values
## Aim
To write a Python program that sorts a dictionary's:

Keys in alphabetical order
Values in alphabetical order
## Algorithm
Start the program.
Define a dictionary with key-value pairs.
Sort by Keys:
Use sorted(dictionary.items())
Convert the result to a dictionary using dict()
Sort by Values:
Use sorted(dictionary.items(), key=lambda item: item[1])
Convert the result to a dictionary using dict()
Display the original and sorted dictionaries.
End the program.
## Program
```
def dictionairy():  
 key_value ={}   
 key_value[2] = 56      
 key_value[1] = 2
 key_value[5] = 12
 key_value[4] = 24
 key_value[6] = 18     
 key_value[3] = 323
 s=sorted(key_value.items(),key=lambda x:x[1])
 print ("Keys and Values sorted in alphabetical order by the value")
 print(s)
 
def main():
    
    dictionairy()           
```
## Sample Output

<img width="1003" height="249" alt="{2FEBBE62-74F5-4B16-B79C-436AC715572F}" src="https://github.com/user-attachments/assets/0c9f94b7-b685-48a5-a7b9-089b4e2d0e77" />


## Result
The program successfully sorts the dictionary by its keys and values in alphabetical order and prints both sorted versions along with the original dictionary.

Exception Handling in Python: Avoiding Index Errors
## Aim
To write a Python program that handles an IndexError when trying to access an element beyond the available range of a list.

## Algorithm
Define a list list1 with some integer elements.
Use a try-except block:
In the try block, attempt to access an index that is out of range (e.g., list1[5]).
In the except block, catch the error and print a custom message "You're out of list range".
Print the result based on whether the index access succeeds or fails.
## Program
```
try:
    # Taking 3 elements input from the user
    L = []
    for i in range(3):
        item = ['laptop','mobile','pen']
        L.append(item)

    # Trying to access index 4
    print(L[4])

except IndexError:
    print("check index range")
```
## Output
<img width="979" height="269" alt="{2A8278F5-A5AA-43F9-9472-15714540F053}" src="https://github.com/user-attachments/assets/6eb85032-9c7a-4d1a-bde1-a9888693bb63" />

## Result
Thus the program executed successfully.

## File Handling in Python: Count Lines Not Starting with 'T'
## Aim
To write a Python program that counts the number of lines in a text file story.txt that do not start with the alphabet 'T'.

## Algorithm
Open the file story.txt in read mode.
Initialize a counter count to zero.
Iterate through each line of the file:
Check if the first character of the line is not 'T'.
If the line does not start with 'T', increment the count by 1.
After processing all lines, print the count value, which represents the number of lines that do not start with 'T'.
## Program
```
def returnSum(myDict):
    final=0
    for i in myDict.values():
        final+=i
    return final
#driver functions

myDict = {'a': 100, 'b': 200, 'c': 300}
print("Sum :",returnSum(myDict))
```
## Output

<img width="493" height="202" alt="{0DCE645B-C886-4FA9-9B0C-E1AED4A06B03}" src="https://github.com/user-attachments/assets/5b676bb2-a579-4e5c-9043-1f7bc589e4a1" />

## Result
Thus,the program has been executed successfully.
