# String Application

## Comprehension Check

<table>
 <tr><td>
<img src="https://github.com/kwaldenphd/internet/blob/main/images/clipboard.png?raw=true" alt="Clipboard icon" width="50"/></td>
  <td><a href="https://docs.google.com/forms/d/e/1FAIpQLSdFMybseRW8-rommWKphdCFBgqWtpxCY1z8wT2_qk3NaJ8awQ/viewform?usp=sf_link">Strings in Python Comprehension Check</a></td>
  </tr>
  </table>
  
## Application Questions


Q1: Write a program that converts integer, float, or boolean values to a string, using the `str()` function.

Q2: Write a program that prompts the user to enter a 6-letter word, and then prints the first, third, and fifth letters of that word.

Q3: Modify the program provided below to search for the character `q` or `u` in the string. Does it always return the index number you expect? What index is returned if you ask for the index of the letter u (i.e., what happens when the desired character appears more than once in the string)?

```Python
# program you're modifying for Q8
# assign string variable
color = "turquoise"

# get index number of t character
index_number = color.index("t")

# show index number as part of print statement
print ("The index number for the letter t within the word " + color + " is " + index_number)
```