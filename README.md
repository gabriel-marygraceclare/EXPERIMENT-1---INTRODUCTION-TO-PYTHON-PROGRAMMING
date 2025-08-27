## Python Programming Assignment

This repository contains the following Programming Assignments

### Experiment 1: Introduction to Python Programming
Alphabet Soup Problem, Emoticon Problem and Unpacking Problem
Link: https://github.com/gabriel-marygraceclare/EXPERIMENT-1---INTRODUCTION-TO-PYTHON-PROGRAMMING/blob/main/PA%201%20-%20Introduction%20to%20Python%20Programming.ipynb
### Alphabet Soup Problem
In this section, we are required to create a function that takes a string and return the string arranged in alphabetical order

1. I started with creating a list from the string "hello" that I have provided wherein the list() converts the string into a list of individual character

```python
alphabet_soup = list("hello")
```

2. Then I used .sort() to arrange the provided list in alphabetical order 

```python
alphabet_soup.sort()
```

3. Then I created an empty string which will be used to store the sorted word once the characters were joined together

```python
string = ""
```

4. Then I created a for loop that will check each item in the list and temporarily store it in x. I use the operator += to join the letters together. And during the loop, the current letter store in x will be added to the end of the variable string.

```python
for x in alphabet_soup:
    string += x
```

5. Lastly, all the sorted letters will be printed

```python
print(string)
```

6. Then I repeated the same procedure to a different word.

```python
alphabet_soup = list("hacker")
alphabet_soup.sort()
string = ""

for x in alphabet_soup:
    string += x

print(string)
```

### Emoticon Problem
In this section, we are required to create a function that changes specific words and replace the words with their corresponding emoticon.

1. I started by declaring four string variables named a, b, c and d. Each of the string contains a short sentence.

```python
a = "Make me smile"
b = "You have a grin on your face"
c = "You look sad"
d = "I am mad"
```

2. Then, I created a motified version of the strings a1, a2, a3 and a4. I used .repplace() replace the certain words in the sentence with emoticons.

```python
a1 = a.replace("smile", ":)")
a2 = b.replace("grin", ":D")
a3 = c.replace("sad", ":((")
a4 = d.replace("mad", ">:(")
```

3. Lastly, after replacing certain words with emoticons, I used print() to display the updated version of the sentences stored in a1, a2, a3 and a4.

```python
print(a1)
print(a2)
print(a3)
print(a4)
```

### Unpacking List Problem
In this section, we are required to unpack the given list into three variables: first, middle and last. The first variable will store the first element while the last variable will store the last element, and the middle variable will contain all the elements in between.

1. In the first part, we created a list called numbers which will be used to extract the elements of first, middle and last.

```python
numbers = [1, 2, 3, 4, 5, 6]
```

2. Then we printed the first, middle and last elements. 

```python
print("first:", numbers[0],"     " "middle:", numbers[1:5], "     " "last:", numbers[5])
```
