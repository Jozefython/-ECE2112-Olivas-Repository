KAROL JOZEF S. OLIVAS

2ECE-C

ECE2112 - Programming Assignment # 1



# 🅰️ALPHABET SOUP PROBLEM

• Create a function that takes a string and returns a string with its letters in alphabetical order. It takes in a string value and alphabetically arrange it from A -> Z.

• The code contains a user-defined function that turns the given string to an ```array``` of characters, ```sorts``` them, and ```prints``` them one by one using a ```while``` function.

**Example:**

```python 
alphabet_soup("karol")

# Output: aklor
```


# 😍EMOTICON PROBLEM

• Create a function that changes specific words into emoticons. It takes in a sentence as a string, replace the words smile, grin, sad, and mad with their corresponding emoticon.

• The code contains a user-defined function that contains ```if``` functions that checks whether the given string contains the following words, and once it does, it ```replaces``` them with the corresponding emoticons.

**Example:**

```python 
emotify("I am mad but I have a smile. You have a grin but you are sad.")

# Output: I am >:( but I have a :). You have a :D but you are :((.
```

# 📦UNPACKING LIST PROBLEM

• Unpack the list writeyourcodehere into three variables, being first, middle, and last, with middle being everything in between the first and last element. Then it prints all three variables.

• The code contains an array of numbers, then two variables that take the minimum and maximum values of the array. After that, the array was modified so that the first and last values of the array will be removed. It then prints the first (minimum) value, middle values (array), and the last (maximum) value

**Example:**

```python 
writeyourcodehere = [1,2,3,4,5,6] 

f = min(writeyourcodehere) 

l = max(writeyourcodehere) 

writeyourcodehere.remove(f) 

writeyourcodehere.remove(l) 



print("First:")

print(f) 

print(" ")

print("Middle:")

print (writeyourcodehere)

print(" ")

print("Last:") 

print(l)



# Output:

First:
1
 
Middle:
[2, 3, 4, 5]
 
Last:
6
```
