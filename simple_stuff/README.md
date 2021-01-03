# Short python exercises

## Parsing arguments
Create simple python program, that writes it's own arguments on standard output. Each argument on separate line.

_Hint: library sys, member argv_ 

---

## Fibonacci number
Write python program that accept argument "*-fib n*"

With said argument program will print n-th number from Fibonacci Sequence.

If wrong or no arguments are given, print nice help message with argument description and example usage.

> ### Fibonacci Sequence
> Each number is sum of previous two members from sequence.
> First two members are 0 and 1.
>
>eg. 0, 1, 1, 2, 3, 5, 8, 13, 21, 34 ...

> ### Example of _nice_ help
>```
>  usage: app_name [options] required_input required_input2
>  options:
>    -a, --argument     Does something
>    -b required     Does something with "required"
>    -c, --command required     Something else
>    -d [optlistitem1 optlistitem 2 ... ]     Something with list
>```
---
