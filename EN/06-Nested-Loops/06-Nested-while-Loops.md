[slide]
# Nested while Loops

A nested while loop is a **while statement inside** another **while statement**. 

In a nested while loop, one iteration of the outer loop is first executed, after which the inner loop is executed. 

The execution of the inner loop continues till the condition described in the inner loop is satisfied. 

Once the condition of the inner loop is satisfied, the program moves to the next iteration of the outer loop.

```python
while condition:
  # Outer Loop 
  while condition: 
    # Inner Loop
      # Statement
```
[/slide]

[slide]
# Problem: Triangle of Stars 2
[code-task title="Triangle of Stars 2" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads the height of a triangle from the console
* Prints a triangle of stars
* Use a while loop
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|5|\*|
||\*\*|
||\*\*\*|
||\*\*\*\*|
||\*\*\*\*\*|
[/slide]

[slide]
# Problem: Triangle of Stars 2
[code-task title="Triangle of Stars 2" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
height = 5
i = 1
while i <= height:
    j = 0
    while j < i:
        print('*', end="")
        j += 1
    print()
    i += 1
```
[/code-editor]
[task-description]
Write a program, which:

* Reads the height of a triangle from the console
* Prints a triangle of stars
* Use a while loop
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|5|\*|
||\*\*|
||\*\*\*|
||\*\*\*\*|
||\*\*\*\*\*|
[/slide]