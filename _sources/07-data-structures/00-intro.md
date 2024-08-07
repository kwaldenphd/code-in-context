# Data Structures in Python

<p align="center"><img src="https://github.com/kwaldenphd/python-data-structures/blob/main/images/Python_Data_Structures.png?raw=true" width="1000"></p>

Up to this point, we've been working with what are called "primitive" data types in Python. These include `integer`, `float`, `string`, and `Boolean`.

But we can imagine scenarios where we want to be able to work with more complex data structures or more complex ways of storing and accessing information in a programming language.

In this lab, we're going to focus on some of the one-dimensional (or linear) data structures available to us in Python. These include `strings`, `lists`, `tuples`, `sets`, and `dictionaries`.

<table><tr><th>Name</th><th>Syntax</th><th>Example</th><th>Description</th></tr>
  <tr><td>String</td><td><code>str(), ""</code><td><code>"Hello world!"</code></td><td>Sequence of characters</td></tr>
  <tr><td>List</td><td><code>list(), []</code><td><code>["apple", "banana", "pear"], [1, 3, 5, 7]</code></td><td>Sequence of objects/values</td></tr>
  <tr><td>Dictionary</td><td><code>dict(), {}</code><td><code>{'first_name': 'Knute', 'last_name':'Rockne', 'class':'1918'}</code></td><td>Key-value pairs</td></tr>
  <tr><td>Set</td><td><code>set(), {}</code><td><code>{"apple", "banana", "pear"}, {1, 3, 5, 7}</code></td><td>Unordered group of unique values</td></tr>
  <tr><td>Tuple</td><td><code>tuple(), ()</code><td><code>("apple", "banana", "pear"), (1, 3, 5, 7)</code></td><td>Ordered group of values that can include duplicates</td></tr>
  </table>

This chapter provides an overview of foundational programming concepts in the areas of data structures and data storage, with a focus on Python syntax. 

Topics covered include:
- Linear and associative arrays
- Indexing
- String objects and methods
- Lists and list methods
- Dictionaries
- Tuples
- Sets

## Ackwnowledgements

Elements of this lab procedure were adapted from materials developed by:
- [Dr. Peter Bui](http://www3.nd.edu/~pbui/) for the [CSE 10101 "Elements of Computing I" course](https://www3.nd.edu/~pbui/teaching/cdt.30010.fa16/).
  * [Reading 05: Lists, Strings](https://www3.nd.edu/~pbui/teaching/cdt.30010.fa16/reading05.html)
  * [Notebook 05: Lists, Strings](https://www3.nd.edu/~pbui/teaching/cdt.30010.fa16/notebook05.html)
  * [Reading 06: Dictionaries, Sets](https://www3.nd.edu/~pbui/teaching/cdt.30010.fa16/reading06.html)
- [Dr. Janet Davis](https://cs.whitman.edu/~davisj/) for the the [CSC 105 "The Digital Age" course](https://www.cs.grinnell.edu/~davisjan/csc/105/2012S/). 
  * [Laboratory: Programming in Python](http://www.cs.grinnell.edu/~davisjan/csc/105/labs/python1.html)
- [Dr. Corey Pennycuff](https://www3.nd.edu/~cpennycu/) for the [CSE 10101 Elements of Computing (Fall 2019)](https://www3.nd.edu/~cpennycu/2019/fa-CSE10101-CDT30010.html).
- [Dr. Lindsay K. Mattock](http://lindsaymattock.net/) for the the [SLIS 5020 Computing Foundations course](http://lindsaymattock.net/computingfoundations.html).

## Application

Your answers to this chapter's application questions should be added to the notebook template.
- [Google Colab link](https://colab.research.google.com/drive/1Esk-yAc-DA-2Jr6vWk6j1IW6NXoeILWE?usp=sharing) (ND users only)

Your Google Colab notebook should be located in the `wk8-data-structures` [Google Drive folder](https://drive.google.com/drive/folders/1btaMEcpz_IoKgNZU4fTmf4l_n9dsga1V?usp=drive_link) (ND users only)

Submit the Colab link on Canvas for the assignment submission.

## Section Contents 

```{tableofcontents}
```