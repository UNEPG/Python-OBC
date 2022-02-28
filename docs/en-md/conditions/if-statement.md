## If statements
So far, we haven't been able to do anything conditionally; we cannot tell Python "do this in some cases and do this other thing" in others. But this is the sort of logic we use everyday when making simple decisions.

Programming languages like Python have tools to mimic those real-world choices.

Many of the decisions we make throughout the day – "it's cold, so put on a coat"; "you're running late, so text your friend"; "you're hungry, so eat something" – have an if-then structure. Just like you, Python can make if-then decisions. 

### If statements
If statements are how you direct Python to do something if something else is true. For example – run the code below. What do you think it'll do? 

<iframe src="https://trinket.io/embed/python/d8ff5d7104" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
Seems pretty reasonable, right?

What about this code? 

<iframe src="https://trinket.io/embed/python/8da0316e52" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

Nothing prints. That's because those two lines of code, converted to English, say "if False, print 'Goodbye'" – but since the statement is false, nothing happens.
### Parts of an if statement
An if statement has two parts: the condition and the action(s). Here's what if statements look like generally: 
```
if some_condition_thats_True_or_False:
    action
```
The condition – the part after the if and before the semicolon – should be a True or False statement. Python can cope with things that don't come in True/False format, though – perhaps somewhat confusingly – it'll only print when the condition's answer isn't 0:

<iframe src="https://trinket.io/embed/python/6e4406d7ce" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

If you try to use a string for a condition, Python'll assume it's True – unless the string is empty:

<iframe src="https://trinket.io/embed/python/acd5902a7a" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
For the sake of your sanity, as well as those who read your code: keep the things in your if statements to those that become either True or False.

### Else
If statements only allow you one course of action; what happens, you might wonder, if you've got more than one instruction to give? Something like:

```
if its_cold_outside:
    put_on_a_coat
else:
    put_on_sandles
```

Or in terms that we can run in a Trinket:

<iframe src="https://trinket.io/embed/python/8bde4461e9" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

### Elif

Sometimes you might want to put in a few conditions. Imagine the somewhat real world example of deciding how to dress for the weather. Let's say your thinking goes like this:

- if it's raining and less than 60 degrees Fahrenheit, you should wear a raincoat
- if it's raining and more than 60 degrees Fahrenheit, you should bring an umbrella
- if it's not raining and is less than 60 degrees Fahrenheit, you should wear sandles
- if it's not raining and more than 60 degrees Fahrenheit, you should wear shoes

We could convert those instructions to Python with some code that looks like this:

```
if temperature < 60 and is_raining:
    wear_a_raincoat
elif temperature > 60 and is_raining:
    bring_an_umbrella
elif temperature > 60:
    wear_shoes
else:
    wear_sandles
```
### Order with conditions
Notice that, in the pseudocode above, we didn't need write `is_raining` for the third and fourth conditions. That's because Python goes through each if lines in order, stopping as soon as it gets to something that's True and then skipping all the rest.

For a more concrete depiction, take a look at the below:

<iframe src="https://trinket.io/embed/python/9fafbf0c75" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

### Challenge
When we run the below code, what will happen?

<iframe src="https://trinket.io/embed/python/58e554ce6c" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
What happens when we run the below?

<iframe src="https://trinket.io/embed/python/5f866a2d88" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

How can we change the below code to get the phrase "Some number?" to print? How about "Biiiiiig number"?
