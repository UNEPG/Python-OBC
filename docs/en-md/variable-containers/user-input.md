## user Input
Before, we talked about how we could use variable containers even if we didn't know which values they held. When might that happen? You might wonder. Can't we always see what we're typing?

Sort of. We can always see what we're typing, but we might not be able to see what other people – say, a user of our program – type. Variable containers become especially helpful here because we've got to save the user's input somewhere.

Take a look at the code below. It might not all look familiar at first, but it should make more sense when you run it. (Click the Run button at the top of the trinket and wait for an instruction on the right side.)


<iframe src="https://trinket.io/embed/python/2261e5e753" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

### raw_input( .. ) function
raw_input("Question") is one way Python programmers can get input from their users.

The line name = `raw_input("What's your name?")` works like the other variable container statements we've seen before. It puts the value of the thing on the right, `raw_input("What's your name?")`, into the variable container on the left – in this case `name`.

### Functions 
`raw_input( .. )` is called a function, which we'll talk more about later. In short, for now, functions are ways to run separate sections of code.

The string in parentheses, in this case "Question", is the text the computer will use to prompt the user. Notice how, in the Trinket above, putting "What's your name?" inside the parentheses caused the Trinket to ask you for your name.

### Challenge
Write two lines of code below.

1. Ask the user for his or her favorite number, and save the answer in a variable container called `num`.
2. print out `num` doubled. 

Hint: you can convert num from text into a number using `int()`. That way, you can use multiplication on it.

So, for example, if I tell you my favorite number is 3, you'll want to print out 6, and if I tell you my favorite number is 42, you'll want to print out 84.

<iframe src="https://trinket.io/embed/python/3ac17e7dc3" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
