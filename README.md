
# Practice with datatypes

### Introduction

In the past few lessons, we have learned about working with different types of data in Python: strings, numbers (ints and floats), and booleans.  Now let's put that knowledge into action.

In this lesson we'll imagine that we were at a nice social gathering and exchanged business cards with a few people.  One of the business cards belongs to Art Vandelay, a new travel agent. We want to use our programming skills to format this information correctly. 

### Learning Objectives
* Manipulate strings with built-in methods
* Practice coercing data types and changing numbers

### Here to mingle 

The next morning we take out the business card, ready to format it using our programming skills, and here is what we find.

![](https://learn-verified.s3.amazonaws.com/data-science-assets/biz-card-mistakes.jpg)

Yeah, Mr. Vandelay may not be the best person to get to know or the best at designing business cards, but like Mr. Vandelay, we know that people enter incorrect information on forms all the time.

So as data scientists, we often need to clean and organize data before we can make sense of it.  Let's get to work. 

### Solving our first lab

This is our first lab, and here we'll see that there is some data already provided for us.  Next to the data, we will see a comment indicating what the data should look like after we change it.  

For example, let's say we want to capitalize all of the letters of "art vandlay".  We'll see the following:


```python
"art vandelay" # "ART VANDELAY"
```

Notice that there is no output below the gray code above.  This is because Jupyter notebooks do not automatically run our code - so they do not automatically know the output.  To display the output, we must **run** the code by clicking on the gray cell and then pressing shift + enter.  Let's try it in the cell above and see our output appear below.

Ok, once we see the output take a look at the cell below with the hash tag to the right of the string, `'hello'`.  This is a comment like the above.  Comments are used for programmers to annotate their code, but a comment has no impact on the code.  We can see this by running the cell below (again, press shift + enter).


```python
'hello' ### whattttt
```

After pressing shift+enter on the cell above, we see that still Python happily ignores our comment. So here (and in future labs), a comment will be provided to indicate what we should see as the return value of our code. When we press shift+enter, and the output below matches the comment to the right of our code, we did it correctly.

> In future labs, Learn will check our code to ensure that we did it correctly.  But for our first lab, this works fine.

To get our output to match the comment we will change it to the following:


```python
"art vandelay".upper() # 'ART VANDELAY'
```

### Get going with strings

First use the `title` method to capitalize the first letter of each word in "art vandelay"`.


```python
"art vandelay" # 'Art Vandelay'
```

Now let's uppercase all of the letters of "Ceo".


```python
"Ceo" # 'CEO'
```

Next, write a method that answers a question about our email addresses.  Every email address should end with ".com".  We can use our knowledge of string methods to check if the email address ends with ".com" and return `True` or `False` accordingly. 


```python
"art.vandelay@vandelay.co" # False
```

As you can see below, the website "vandelay.com" is not preceded by `"www."`. We can perform what is called string concatenation to fix this! Use the plus sign, `'+'`, to change the website `'vandelay.com'` to the string `'www.vandelay.com'` by prepending `'www.'`.


```python
'vandelay.com' # 'www.vandelay.com'
```

### Working with numbers

Finally, Mr. Vandelay gave us his phone number, but he actually has two other phone numbers that are different from the one listed.  All three numbers are basically the same with the exception of the ending. Below, start by coercing the first phone number, which is currently a string, to an `int` and add one. Next do the same to the second phone number but increase it by two.


```python
"7285553334" # 7285553335
```


```python
"7285553334" # 7285553336
```

### Summary

Our first lab is done! Sweet. In this lab, we practiced working with string methods to operate on and answer questions about strings. We wrote methods that return Booleans and changed strings to integers in order to perform addition. So much of working with data is ensuring that it is properly formatted so we can then operate on it, and in this lab, we saw how to use code to do just that.
