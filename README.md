
# Practice with Data Types

### Introduction

In the past few lessons,you learned about working with different types of data in Python: strings, numbers (ints and floats), and booleans.  Now, you'll put that knowledge into action.

Imagine that you're at a business event and exchanged business cards with a few people. One of the business cards belongs to Art Vandelay, a new travel agent. Here, you'll use your programming skills to format this information correctly. 

### Learning Objectives
* Manipulate strings with built-in methods
* Practice coercing data types and changing numbers

### Here to mingle 

The next morning you take out the business card, ready to format it using your programming skills, and here is what we find.

![](https://learn-verified.s3.amazonaws.com/data-science-assets/biz-card-mistakes.jpg)

### String Transformations

When storing text in a spreadsheet or database programmatically, you will often preprocess the data to ensure that it is properly formatted. For example, you might ensure that a telephone number matches the required format, or that a field on a web form is filled out. 

Here's a simple example of how you might go about doing this:


```python
name = "art vandelay" # "ART VANDELAY"
name.upper()
```

If you haven't already, put your cursor into the cell above and press `shift + enter` to run the code in the cell. You should see an updated output produced by the `.upper()` string method. 

Another important note is the hashtag `#`. In python, hashtags indicate a comment. Comments are notes used to provide additional information but are ignored by the computer when running the code. 


```python
'hello' ### whattttt
```

After pressing shift+enter on the cell above, you'll see that Python ignores the comment. In Flatiron coding labs, a comment will be provided to indicate what you are aiming to have the code return. This allows you to then easily check your answer upon running your code.

### Get going with strings

With that, use the appropriate string method to transform each string to match the desired output in the comment.

Use the `title` method to capitalize the first letter of each word in "art vandelay"`.


```python
"art vandelay" # 'Art Vandelay'
```

Now use the `uppercase` method to capitalize all of the letters of "Ceo".


```python
"Ceo" # 'CEO'
```

Next, write a method that verifies whether an email addresses is valid. To make this introductory example simple, assume that every email address should end with ".com".  With that, use your knowledge of string methods to check if the email address ends with ".com" and return `True` or `False` accordingly. 


```python
"art.vandelay@vandelay.co" # False
```

As you can see below, the website "vandelay.com" is not preceded by `"www."`. You can perform string concatenation to fix this! string concatenation allows you to join two strings. It works just like numerical addition. For example, ```"This is the start" + "and this is the end"``` would return ```"This is the start and this is the end"```. Use string concatenation to change the website `'vandelay.com'` to the string `'www.vandelay.com'` by prepending `'www.'`.


```python
'vandelay.com' # 'www.vandelay.com'
```

### String Slicing

Finally, Mr. Vandelay gave us his phone number. Extract the area code by selecting the first three characters of the string. You can do this using brackets to select characters from the string as in ```"George"[:4]``` which would return ```"Geor"```.


```python
"7285553334" # 728
```


```python
"7285553334" # 728
```

### Summary

Congratulations! You just completed your first lab! You practiced working with string methods to operate on and answer questions about strings. You also used methods that return Booleans and sliced strings. So much of working with data is ensuring that it is properly formatted and in this lab, you started practicing your data wrangling skills.
