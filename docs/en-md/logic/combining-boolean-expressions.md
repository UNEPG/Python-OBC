## Combining boolean expressions

Sometimes, you'll want to deal with more than one logical expression at a time.

You might like to see if one thing is true and another thing is true, one thing or another thing is true, or maybe see if both things are true.

Python has a few special words to help you do all that: `and`, `or`, and `not`.

### `and` 
`and` is a special keyword in Python that figures out whether, given two expressions, both are true. If so, Python will say True; if not, it'll say False. Here's a few examples:

<iframe src="https://trinket.io/embed/console/f31e9c968d" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

### `or`
`or` is another special keyword that figures out whether, given two expressions, one or the other or both are true. If so, Python will say True; if not, it'll say False. Here's a few examples:

<iframe src="https://trinket.io/embed/console/d109d9a41e" width="100%" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

### `not` 
`not` is Python's last keyword for combining booleans. When you put it in front of something, it negates, or reverses, that expression. So things that were true become false, and things that were false become true. For example:

<iframe src="https://trinket.io/embed/console/a6049d1448" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

### Challenge

Read through the boolean problems below and try to figure out what Python will return. Run each in the console below if you like.

- `True and False`
- `True or False`
- `(True or False) and True`
- `(True or False) and True`
- `not False or True`
- `not True and False`
- `not True or False`
- `not True or True`
- `3 + 3 == 6 and len("hi!") == 3`
- `3 + 3 == 6 or len("hi!") == 3`
- `3 + 3 != 6 or len("hi!") == 3`
- `4 + 4 > 2 and 4 != 5`


<iframe src="https://trinket.io/embed/console/aae5a0dc21" width="100%" height="200" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
