# ErinScript Documentation

## About

ErinScript is an interpreted language for ErinOS. It'll likely carry over to the **REAL** ErinOS once that gets made. To see it in action, look at `example.es`.

## Syntax *and whatnot*

`print "text";` prints text to the console. To read this text, use the console addon in PenguinMod. I'm sure you can find where it is. Also, the contents **must** be in quotes. Otherwise, it'll get interpreted as a variable.

`var myVar = "contents can either be strings or numbers!";` adds a variable. As you saw, it can either be a string, **or** a number. How fun! These can be printed to the console. They can be reassigned midoperation.

`// This is a comment!` Comments work like they do in C and JavaScript and many other programming languages. Two slashes.

`if myVar; print "true"; else print "false";` If statements exist. They're not typically written on one line, but I think they can? I've never tested it. Aanyways, they're simple. You saw how they work.

`myVar == 4` There are four conditionals in ErinScript. ==, >, and the variable itself. == is equals to. > is greater than. And the variable itself is the variable as either 1 or 0. I was planning on adding a not, but on paper it would've been too hard. If you want to add one, go ahead! == works with strings, though nothing in the condition can be in quotes. I'm not happy with this either.

`wait 2;` You can wait a number of seconds. This was really easy I didn't need to change anything wow,,,

`myVar + 4` ErinScript has four operators. + - * /. You've probably seen these in math class. They work as expected. You can also operate on two variables at once!

## ***DO NOT FORGET YOUR SEMICOLONS!!!***

## Headers

- Give yourself a unique ID! IDs usually follow the format of `author.program`
- The author part of your header should be your GitHub or similar.
- Give your program a unique icon! You can find the list of icons in the costumes.

## Good Practice

Generally, I would avoid using multiple lines in `print` commands, since it looks off in the console, but it's up to you! To add a line, use `\n`.