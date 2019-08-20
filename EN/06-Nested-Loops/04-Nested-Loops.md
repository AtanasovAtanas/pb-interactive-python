[slide]
# Nested Loops
Statements that consist of several **loops** located **inside each other**

**Nested loops** are used:

* To execute an **action**, which **executes** multiple **actions**
* To make more **complex** calculations and variations

A nested loop is a construction where in the body of one loop (**outer one**) stays another loop (**inner one**). 
In each iteration of the outer loop, the whole inner loop is executed. 

This happens in the following way:
* When nested loops start executing, the outer loop starts first: 
  * the controlling variable is initialized and after a check for ending the loop the code in its body is executed.
* After that, the inner loop is executed. 
  * The controlling variables start position is initialized, a check for ending the loop is made and the code in its body is executed.
* When reaching the specified value for ending the loop, the program goes back one step up and continues executing the previous (outer) loop.
* The controlling variable of the outer loop changes with one step, a check is made to see if the condition for ending the loop is met and a new execution of the nested (inner) loop is started.

This is repeated until the variable of the outer loop meets the condition to end the loop.
[/slide]