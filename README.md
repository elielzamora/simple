# simple
The Syntactically Intuitive Multi-paradigm Programming Language for Education _is_ simple in every way.

## Intro
  simple is the idea that _anyone_ can code (just like Chef Gusteau's famous book). Anyone can read, understand and then pick up the textual instructions in seconds. It can be used as a tool to teach code, algorithms or just plain share a cool idea to others in an easy manner. Plain english, 'codeless' code.
  
## Vision
  Create a language that is consitent and intuative. Create and online interpreter JS and a virtual machine that can be implemented in C to be either interpreted or run just like you would a C++ project.
  
## Language Overview

### Features
- Python like code blocks using indentation as markings
- Natural english phrases make statments seem less cryptic and unambiguous

### Comments
- Starting a line with `this` comments the line
- Starting a line with `the following` comments the following indented words

### Values

### Assignment
####Example: Variable Assignment
```
x is now 42
```
creates the variable x and assigns it the value of 42
the variable `x` is a dynamic variable and can be reassigned by calling the assignment statment again
```
x is now a Dog
```
for now ignore the `a Dog` part of the statement.
####Example: Constants
```
pi is always 3.14159
```
This is as straight forward as can be. If you later try to say `pi is now 4` it won't complile because `pi is ALWAYS 3.14159` (case insensitivity has is upsides)

#### Selection Structures
Example: Classic 3 part if statement (if, else if, else)
```
if x is 3 then
    write "x is 3"
if x is 4 then
    write "x is 4"
otherwise
    write "x is neither 3 or 4"
```
otherwise flows much nicer than else when reading out the code.
also it can be written without the then keyword
```
if x is 3
    write "x is 3"
if x is 4
    write "x is 4"
otherwise
    write "x is neither 3 or 4"
```


  
