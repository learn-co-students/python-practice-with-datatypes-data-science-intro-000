
# Practice with datatypes

### Introduction

In the past few lessons, we have learned about working with different types of data in Python: strings, numbers (ints and floats), and booleans.  Now let's put that knowledge into action.

In this lesson we'll imagine that you just stopped by an Python programming conference and met a few people there.  You exchanged some information with a very industrious person who you met, and want to use your programming skills to format this information correctly.  

### Learning Objectives
* Manipulate strings with built-in methods
* Practice coercing data types and changing numbers

### Here to mingle 

The next morning you take out the business card, ready to format it using your programming skills, and here is what you find.

![](./biz-card-mistakes.jpg)

Yea, he may not be the best person to get to know.  But we know that when people fill out forms, they misenter information all of the time.  As a celebrity once said, "I'm really getting into the Internet lately, I just wish it were more organized."

And as data scientists, we also see the need of organizing and cleaning data to then make sense of it.  So let's get to work.

### Solving your first lab

This is your first lab, and here you'll see that we have provided some data for you.  Next to the data, you will see a comment indicating what the data should look after you change it.  Let's do the first one together.  For example, let's say we want to capitalize all of the letters of "art vandlay" (to remind ourselves of how he made his introduction).  You'll see the following:


```python
"art vandelay" # 'ART VANDELAY'
```




    'art vandelay'



That hash tag to the right is a comment.  Comments are used for programmers to annotate their code.  But a comment has no impact on the code.


```python
'hello'
### whattttt
```




    'hello'



If you press shift+enter to run the code in the cell, you will see that Python happily ignores the comment.  So in labs, we provide the comment to indicate what you should see as the return value of your code.  When you press shift+enter, and the output below matches the comment to the right of your code, you did it correctly.

> In future labs, Learn will check your code to ensure that you did it correctly.  But for your first lab, this works fine.

And change it to the following:


```python
"art vandelay".upper() # 'ART VANDELAY'
```




    'ART VANDELAY'



### Get going with strings

First use the `title` method to capitalize the first letter of each word in "art vandelay"`.


```python
"art vandelay" # 'Art Vandelay'
```




    'art vandelay'



Now let's uppercase all of the letters of "Ceo".


```python
"Ceo" # 'CEO'
```




    'Ceo'



Now write a method that answers a question about our email addresses.  Every email address should end with ".com".  Use your knowledge of string methods to check if the email address ends with ".com" and return `True` or `False` accordingly. 


```python
"art.vandelay@vandelay.cop" # False
```




    'art.vandelay@vandelay.cop'



As you can see, the website "vandelay.com" is not preceded by `"www."`.  Use the plus sign to change the website 'vandelay.com' to the string `'www.vandelay.com'`.


```python
'vandelay.com' # 'www.vandelay.com'
```




    'vandelay.com'



### Working with numbers

Finally, Mr. Vandelay gave us his phone number, but he actually has a second number different ones listed.  All three numbers are the same except for the ending.  Coerce the string of his phone number to an `int` and add one, then add two to change the number.  


```python
"7285553334" # 7285553335
```




    '7285553334'




```python
"7285553334" # 7285553336
```




    '7285553334'



### Summary

Your first lab done!  Sweet.  In this lab, you practiced working with string methods to operate on and answer questions about strings.  You wrote methods that return Booleans.  And you changed strings to an `int` to then perform addition.  So much of working with data, is ensuring that our data is properly formatted so we can then operate on it and in this lab you saw how to use code to just that.
