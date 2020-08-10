blocks inside if, else and while statements should be one line long (a function). This way the function name can be more descriptive.

functions should not be large enough to contain nested structures. The indent level should not be greater than 1 or 2.

functions should do one thing, do it well and do only that.

if you find yourself dividing code into sections, break them into functions instead

for practice, read the program as though it were a ste of 'TO' paragraphs, each of which is describing the current level of abstraction and referencing subsequeny 'TO' paragraphs at the next level down.

for switch statements, build an abstract factory and for the implementation.

only add function params if you cannot avoid them.

don't use more than 2 arguments for function params.

if you need more than 2 arguments, best to wrap them in a class.

avoid passing booleans into functions as params, break them into separate functions.


