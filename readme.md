Jason Kuruzovich [6:03 PM]
@channel There is an issue I didn’t realize for Homework 8 that wasn’t meant to trip you up.

Currently the project is adopted for Python 2. To work on Python 3 (as in lab.analyticsdojo.com) you will need to make the following adaptations:


1. Printing in Python is different.

Python 2.X
`print x`

Python 3.X
`print (x)`


2. Lambda functions now only accept one value in Python 3.

Python 2.X
`(lambda a, b : a + b)`

Python 3.X
`(lambda ab : ab[0]+ab[1])`
