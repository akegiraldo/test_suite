<h1 align ="center"> Simple Shell, Checks </h1><br>

## Table of Contents 
---
- [Authors](#authors)
- [Introduction](#introduction)
- [Shell style guide](#description)
- [Installation](#installation)
- [Test](#Test)
- [Files](#files)
- [Features](#features)
- [Built With](#built-with)
- [Acknowledgments](#acknowledgments)
---
## Authors 
---
* [See AUTHORS file](https://github.com/Doouh/test_suite/blob/cohort10/AUTHORS)
---
## Introduction
> Repository created to add test cases that can be used by students in cohort 10 of Medellin, to test their Shell project.
---
## Shell style guide
---
* [See webpage](https://google.github.io/styleguide/shell.xml)
---
## Installation 
---
In order to run the shell command interpreter, you must install it in your repository by cloning the following (shown below) in your machine running:
```
git clone https://github.com/shincap8/simple_shell.git
```
---
## Test
---
- In order to compile the function you must run the following line in your shell:
```
gcc -Wall -Werror -Wextra -pedantic *.c *.h -o hsh
```
_Note_: there are two ways of using the command interpreter:

#### Interactive mode:
```
 $ ./hsh
($) /bin/ls
hsh main.c shell.c
($)
($) exit
$
```
---
## Features 

A simple shell must work with the path and without the path
* /bin/ls
* ls
* env "this must print the environment"
* help "this must print the help"
* exit "let you exit the shell"
* unsetenv "remove an environment variable"
---
### Examples of use

Below you can find use of some commands.

```
$ ls -a
$ echo Hola
$ pwd
```
Here are the result of this actions:

```
> ls -a
.   additionalFunctions_0.c  AUTHORS              .git             hsh        main.c              README.md  _stdlib.c   _string_1.c
..  additionalFunctions_1.c  builtinsFunctions.c  helpFunctions.c  library.h  man_1_simple_shell  _stdio.c   _string_0.c
> echo hola
hola
> pwd
/home/vagrant/hbn/simple_shell
> exit
```


## Built With

* [C](https://en.wikipedia.org/wiki/C_(programming_language))
* [Vim](https://https://en.wikipedia.org/wiki/Vim_(text_editor)/)
* [Vagrant](https://www.vagrantup.com/)
* [Peppermint](https://www.osboxes.org/peppermint/) Need to change to what Kevin is using
* [Ubuntu](https://www.ubuntu.com/)
* [GCC 4.8.4 Compiler](https://gcc.gnu.org/)
