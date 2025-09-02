# **ALPHABET SOUP PROBLEM**

• Create a function that takes a string and returns a string with its letters in alphabetical order.

• Its purpose is to take in a string value and alphabetically arrange it from A -> Z.

Example:

alphabet_soup("karol")
#

#output: aklor


# **EMOTICON PROBLEM**

• Create a function that changes specific words into emoticons. 

• Its purpose is to take in a sentence as a string, replace the words smile, grin, sad, and mad with their corresponding emoticon.

Example:

emotify("I am mad but I have a smile. You have a grin but you are sad.")

#
#Output: I am >:( but I have a :). You have a :D but you are :((.


# **UNPACKING LIST PROBLEM**

• Unpack the list writeyourcodehere into three variables, being first, middle, and last, with middle being everything in between the first and last element. 

• Its purpose is to print all three variables.

Example:


writeyourcodehere = [1,2,3,4,5,6] 

f = min(writeyourcodehere) 

l = max(writeyourcodehere) 

writeyourcodehere.remove(f) 

writeyourcodehere.remove(l) 

#

print("First:")

print(f) 

print(" ")

print("Middle:")

print (writeyourcodehere)

print(" ")

print("Last:") 

print(l)

#

#Output:

First:
1
 
Middle:
[2, 3, 4, 5]
 
Last:
6
