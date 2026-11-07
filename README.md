# Csc-122-Wk11
## Eggceptional
Create an abstract class called Egg. An egg should have a size and a flavor. These variables should be viewable, but not changeable. An egg should also have a purely virtual function called eat_egg, which is intended to print a textual description of what eating the egg is like.

Create at least three concrete classes inheriting egg. One of these should be a rotten egg.

Create a custom exception class called bad_egg. Trying to eat a rotten egg should throw this exception instead of printing anything.

Create a class called Carton which can hold twelve eggs. This should have a function that removes an egg from the carton and eats it. However, if the egg is a rotten egg this function should catch the error thrown and print a warning that there was a bad egg.

TPQs:

How might this program structure be applied in a more realistic scenario?
How could you have implemented the rotten egg behavior without using try-catch blocks?
