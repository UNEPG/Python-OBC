## For loops

For loops tell the computer to do something for a bunch of values. They're particularly useful when we want the same "thing" done several times in succession.
### Many print statements, no for loop

Let's say, for example, we wanted to print out the numbers 0-5 in sequence. We could write print statements:
But that seems tedious!  
<iframe src="https://trinket.io/embed/python/ea63176ce3" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe> 


### For loop and a list

We could also put the numbers we want in a list and then print each thing in the list:

<iframe src="https://trinket.io/embed/python/2655224261" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

That seems a little better.

On the first line, we make a list, called `numbers`, and fill it with the numbers we wish to print: [0, 1, 2, 3, 4, 5].

On the second line, we write `for n in numbers`: This is the for loop part, and converted into English, it says "Look at the list called numbers. For each element in it, grab the element and temporarily call it `n`. Then .. "

On the third line, we write print just once, and ask Python to print n. That's the same as asking Python to print out the value in the variable container n – which we know is one of the elements in the list from the second line!

### For loop and `range( .. )` function
There's a special `range( .. )` function built into Python that gives back a range of numbers. Try running the code below: 

<iframe src="https://trinket.io/embed/python/a15cfb8a0a" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
Here we get the same result, though we didn't have to make a list ourselves. The range(0, 6) function gave us one that went from 0 (inclusive) to 6 (exclusive.)

### General form of a for loop

The general form of a for loop looks like this:

```
for temp_variable in some_sort_of_list:
    do_something
```
### Doing things with for loops

For loops end up being pretty useful. Take a look at the code below; when you think you know what it does, click 'Run', and take a look:

<iframe src="https://trinket.io/embed/python/be9135a40b" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

That for loop sums the numbers between 0 and 100.

What about this one?

<iframe src="https://trinket.io/embed/python/398fd547ea" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>


That code calculates the factorial of 10, 10! or 10 9 8 .. 1
### Challenge

In the Trinket below, can you write some code to print the odd numbers between 0 and 20?

<iframe src="https://trinket.io/embed/python/9dffbf50e2" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

What about a "movie countdown timer" that prints:

```
10
9
8
7
6
5
4
3
2
1
```

Finally, how about some code that averages a student's test scores. There's some starter code – a list called `scores` with the student's grades – in the Trinket below.

It's up to you to average those scores and assign that value to the variable container named `average`.

<iframe src="https://trinket.io/embed/python/3a5051d859" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

