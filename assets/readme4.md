# Instructions

Create a program that does all of the following:

*Hint:* Flowchart 1 step at a time. Implement that step and when it works properly, flowchart the next.

* Prompt the user to input a command, then do the following:

1. If the command is `print` print all the employee names, office numbers, and telephone numbers

2. If the command is `verify`:
  * prompt the user for an employee name
  * print true if the employee exists otherwise print false

3. If the command is `lookup`:
  * prompt the user for an employee name
  * print the employee's name, office number, and telephone number

4. If the command is `contains`:
  * prompt the user for a string
  * print the information of *all* employees whose names contain the given string
  ex: `Dav` would print info for `David`, `Davus`, and `Dave`

5. If the command is `update`:
  * prompt the user for a name
  * prompt the user for a field they would like to update
  * prompt the user for a value
  * find the employee with that name and update the provided field with the provided value
  * print the new info for that employee

6. If the command is `add`:
  * prompt the user for a name
  * prompt the user for an office number
  * prompt the user for a telephone number
  * add this employee to the `employeeList`
  * print the updated `employeeList`

7. If the command is `delete`:
  * prompt the user for a name
  * delete the object with this name property from the array entirely.
  * print the updated `employeeList`
