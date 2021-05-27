# Week 1 

Remember to go into the root directory and git pull the changes made

## Python / Jupyter Notebook files 
Throughout these next couple of months we'll be using Python and Jupyter Notebook files 

Python files have the extension (.py) while Jupyter Notebook files have (.ipynb)

They are both still using the Python programming language just Notebook files have some cool features such as the ability to run code segmentally 

We will also be using Visual studio code as our IDE (Integrated development environment) (Pretty much where you can execute code)

In visual studio code if you press ctrl + shift + p you will open the command pallet 
(You can also go to the view option on the top of the ribbon and select command pallet from there)

If you type "Open new Jupyter notebook" it will create a blank notebook for you 
___
## Learning the standard 

When it comes to programming there is a lot of unwritten rules, rules which if followed make debugging and just generally improving the readability of your code. 

This week will go through some of these unwritten rules as well as some introduction into the key elements of programming. The following sections will just go through some structure and standards, there is no need to understand what is happening in the code snippets just the structure of it.

### Indentation
Indentation refers to the tab key being used to signify a function or block of code. 

In Python, a compiler will consider incorrect indentation as an error and will not execute the code. 

With function, if statements, for loops or any block or segment of code there needs to be an indent

As python does not use ; or {} it uses indentation, some find this easier to read and understand, I find it more complex as if you forget an indent it can be much harder to find. 

This is why understanding indentation at the start is key. 
```python
def function: 
    #This is a function, there is an indent placed after the : 

if(x == true):
    #This is an if statement, the indent again is placed after the :
    #This if statement is not contained within the function 
else:
    #Each if statement has an else statement. this again is not contained within the previous statement

for x in range(6):
    #This is a for loop, again it executes a block of code which is why an indent is necessary

    if(x == true):
        #This is an if statement this is inside the for loop as it is indented with the contents of the for loop

```
___
### Naming styles 
Naming styles or conventions are also another key thing with python, unlike indentation it does not cause an error but it is good to have standardized code 

#### FileNames 
In terms of file names, they should use upper camel case which pretty much means 

FirstLetterOfEachWordStartsWithACaptialLetterPlusThereAreNoSpaces

For instance Week1.ipynb

Another example would be Week1AdamsWork.ipynb 

Something to point out is not to name your file with any of the following ' " / I don't think windows will let you but just a reminder
___
#### Variable names 
Variables are simply placeholders which hold a value, this value can be a number, letter, word or even list
Variables in Python are dynamically allocated which pretty much means you do not need to define a type 
Which makes things super simple 

This is where it can get slightly confusing so I won't be too harsh as it took me a while to understand 

Most variable names will operating with a lower camel case which looks like this 

```python
variableHasLowerCaseFirstLetterButTheRestAreUpper = 1
```

There is another variable we have to worry about, these are constants so like values like Gravity for instance
As we are gonna be doing science-y programming we will probably have a lot of constants so it's important to reflect that in the code

For constants we will use a single capitalized letter it is also important to specify what the constant is above where it is first stated 

```python
#This is a comment btw denoted with a hashtag more on this later

#Gravity 
G = 9.8
```
___
### Function names 
Functions are blocks of code that have to be called to be executed (More on this later)
Functions are used to group code which carries out a function collectively such as added a series of numbers and then calculating the mean and returning that value back 

A function name should reflect what happens in the function lets take that mean calculation logic 
Function names are in lower_case_with_underscores 

```python
def calculate_average_of_n_numbers:
    n1 = 5
    n2 = 10
    n3 = 11
    sumOfNumbers = n1 + n2 + n3
    meanOfNumbers = sumOfNumbers / 3
    print(meanOfNumbers)

```
There are other specifications for some function names which require __double__underscores__ but we'll get to that later on 
___
## Comments 
As mentioned previously comments are defined in python with the use of the hashtag #
Hashtag's will be very important as to help make our code pretty well defined so we know what the f*ck is going on 
Hashtags are only needed when something isn't too clear 
The real emphasis should be on the names of functions and variable names as they will help print a clearer picture 
Such as before with the calculate_average_of_n_numbers we could tell just from the name this function calculated the mean of the numbers 
___

Now we can take a look at the Week1.ipynb file which is gonna lay out some exercises for us to take a look at 

