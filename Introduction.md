# Pseudocode

Most programs are developed using programming languages.
These languages have specific syntax that must be used so that the 
**Pseudocode** is not a programming language,
it is a simple way of describing a set of instructions
that does not have to use specific syntax.

## Common pseudocode notation
There is no strict set of standard notations 
for **pseudocode**, but some of the most widely recognised are:

INPUT – indicates a user will be inputting something
OUTPUT – indicates that an output will appear on the screen
WHILE – a loop (iteration that has a condition at the beginning)
FOR – a counting loop (iteration)
REPEAT – UNTIL – a loop (iteration) that has a condition at the end
IF – THEN – ELSE – a decision (selection) in which a choice is made
any instructions that occur inside a selection or iteration are usually indented

## Using pseudocode
Pseudocode can be used to plan out programs. 
Planning a program that asks people what the best subject they take is, 
would look like this in **pseudocode**:

REPEAT
	OUTPUT 'What is the best subject you take?'
	INPUT user inputs the best subject they take
	STORE the user's input in the answer variable
	IF answer = 'Computer Science' THEN
		OUTPUT 'Of course it is!'
	ELSE
		OUTPUT 'Try again!'
UNTIL answer = 'Computer Science'