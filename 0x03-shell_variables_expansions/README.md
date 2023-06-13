## The content of this file are arrange in a file name and what they do format
11;rgb:0000/0000/0000
### [0-alias](0-alias)
This file execute a script that creates an alias
* Name: `ls`
* Value: `rm *`

### [1-hello_you](1-hello_you)
This file execute a script that prints `hello user`, where user is the current Linux user

### [2-path](2-path)
This file execute a script that add `/action` to the `PATH`. `/action` should be the last directory the shell looks into when looking for a program

### [3-paths](3-paths)
This file execute a script that counts the number of directories in the `PATH`

### [4-global_variables](4-global_variables)
This file execute a script that lists environment variables

### [5-local_variables](5-local_variables)
This file execute a script that lists all local variables and environment variables, and functions

### [6-create_local_variable](6-create_local_variable)
This file execute a script that creates a new local variable
* Name: `BEST`
* Value: `School`

### [7-create_global_variable](7-create_global_variable)
This file execute a script that creates a new global variable
* Name: `BEST`
* Value: `School`

### [8-true_knowledge](8-true_knowledge)
This file execute a script that prints the result of the addition of 128 with the value stored in the environment variable `TRUEKNOWLEDGE`, followed by a new line

### [9-divide_and_rule](9-divide_and_rule)
This file execute a script that prints the result of `POWER` divided by `DIVIDE`, followed by a new line

### [10-love_exponent_breath](10-love_exponent_breath)
This file execute a script that displays the result of `BREATH` to the power `LOVE`

### [11-binary_to_decimal](11-binary_to_decimal)
This file execute a script that converts a number from base 2 to base 10
* The number in base 2 is stored in the environment variable `BINARY`
* The script should display the number in base 10, followed by a new line

### [12-combinations](12-combinations)
This file execute a script that prints all possible combinations of two letters, except `oo`
* Letters are lower cases, from `a` to `z`
* One combination per line
* The output should be alpha ordered, starting with `aa`
* Do not print `oo`
* Your script file should contain maximum 64 characters

### [13-print_float](13-print_float)
This file execute a script that prints a number with two decimal places, followed by a new line
* The number will be stored in the environment variable `NUM`