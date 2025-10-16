# Conditional-Statements-Shell-Script
Conditional Statements | Shell Script


1. Implementing if statement
if [ expression ]
then
   statement
fi

Script Example:
#!/bin/bash
# two variables x & y
x=100
y=120
# check whether x is equal to y
if [ $x == $y ]
then
echo "x is equal to y"
fi

# check whether x is not equal to y
if [ $x != $y ]
then echo "x is not equal to y"
fi

