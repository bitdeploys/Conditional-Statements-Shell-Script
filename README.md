# Conditional-Statements-Shell-Script
Conditional Statements | Shell Script

1. if statement
if [ expression ]
then
   statement
fi

Script Example:
#!/bin/bash
x=100
y=120
if [ $x -ne $y ]
then
echo "x is not equal to y"
fi
