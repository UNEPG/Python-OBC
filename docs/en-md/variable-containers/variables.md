## Variable containers
Computer scientists often work with variables. Variables in computer science are pretty different than those in math, even though they're called the same thing. Because of this, some people call the computer sceince versions containers, since they don't actually vary like math variables do; they contain information. 

### Variable containers = name and value
There's two parts of every variable container: a name and a value. For example: 
```
age = 17
```
Here, the variable container's name is `age`, on the left, and its value is 17, on the right. This variable container is storing the number 17.

Here's another:
```
weather = "cloudy"
```
Here, the variable container's name is `weather` (left side), and its value is `"cloudy"` (right side.) This variable countainer is storing the string "cloudy".

In the console below, we (again) put the value `17` in the `age` container and the value `"cloudy"` in the `weather` container. Since we put values in the container, we can take them out later.

<iframe src="https://trinket.io/embed/console/358fb34f23" width="100%" height="200" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

This becomes really useful when we want to save values to use later; with variable containers, we don't have to remember the values, or even where they came from – we just have to remember where we put them.

### Naming variable containers
There's a few rules to keep in mind when you're naming variable containers: 

#### Begin with a letter
Variable container names must start with a letter.

If you try to start the name with a symbol or a number, Python will give you a ParseError, which is its way of saying it doesn't understand what you're trying to do.

<iframe src="https://trinket.io/embed/console/348b18cf7a" width="100%" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

#### Alphanumeric
Variable container names can only contain letters and numbers – no symbols, spaces, or other things that aren't (A-z, 0-9) allowed.

#### Case sensitive
Variable containers are case sensitive, which means that the name var is different from Var, vAr, and VAR.

You can see that in the console below, where we set `var`, `Var`, `vAr`, and `VAR` to different values and then print out the different values.

<iframe src="https://trinket.io/embed/console/3d5da4cb9b" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
#### Unique
Each variable container's name must be unique; that is, no other variable can have its name.

Python doesn't yell, or throw an error, if you re-use a variable name – it just re-writes the old value with a new one, which can be pretty confusing if you don't expect it.

Take a look at the code in the console below for an example. It creates two variable containers, `name` and `question`. The `name` variable container ends up holding the string `"Python"` – the string `"Trinket"`, which it originally held, got lost when we wrote name = "Python"

<iframe src="https://trinket.io/embed/console/ee474cb701" width="100%" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe> 
It might help to think of variable containers as named buckets that can only hold one thing; if you put something in one of them, it's in there until you replace it with something else.
#### Mutli-word names
It's common, but not required, to use snake case – all lower-case letters, with underscores `_` instead of spaces – if your variable container name is longer than one word:

<iframe src="https://trinket.io/embed/console/fb4f9d289b" width="100%" height="200" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
### Challenge
Set up your own variable containers:

- fill the `fav_programming_language` variable container with the string "Python"
- fill the `year` variable container with the number 2022
- fill the `cubesat` variable container with the string UniSat

Then, print out the values that the `fav_programming_language`, `year`, and `cubesat` variable containers contain.

<iframe src="https://trinket.io/embed/console/3814429e0f" width="100%" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

