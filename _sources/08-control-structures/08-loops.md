# Loops

Testing for membership or returning index values are a couple examples of tasks we can accomplish in Python using iteration.

But let's review the definition of iteration as a control structure. From Busbee and Braunschweig's "[Iteration Control Structures](https://press.rebus.community/programmingfundamentals/chapter/iteration-control-structures/)," in *Programming Fundamentals*:

"In iteration control structures, a statement or block is executed until the program reaches a certain state, or operations have been applied to every element of a collection. This is usually expressed with keywords such as `while`, `repeat`, `for`, or `do..until`. The basic attribute of an iteration control structure is to be able to repeat some lines of code. The visual display of iteration creates a circular loop pattern when flowcharted, thus the word 'loop' is associated with iteration control structures."

Breaking down that definition:
- Iteration (repetition of a process) is a type of control structure
- In programming languages, iteration involves lines of code repeating until a condition is met of the end of a group of values has been reached.
- Because iteration in this context involves a circular pattern, many object-oriented programming languages refer to these structures as `loops`

The power of iteration as a control structure comes from a programming concept called `loops`.

## Types of Loops

<p align="center"><img src="https://github.com/kwaldenphd/python-loops-iteration/blob/main/images/loop-comparison-diagram.png?raw=true" width="1000"></p>

Most high-level programming languages support two main types of loops: event-controlled and count-controlled
- **Event-controlled loops** test for an initial condition, and execution continues as long as the initial condition is `True`. How many times the loop will execute *is not known*.
- **Count-controlled loops** (sometimes called counter-controlled loops) continue executing for a pre-determined number of times. The number of times the loop will execute is known because the loop is iterating through a collection of objects/values (i.e. a string or list), or the iteration when the initial condition will no longer be `True` is known.
