## What you will learn in this section
This section will give you an overview of Python programming language and basics.

## Introduction
Python is a widely used high-level, general-purpose, interpreted, dynamic programming language. Its design philosophy emphasizes code readability, and its syntax allows programmers to express concepts in fewer lines of code.

Python supports multiple programming paradigms, including object-oriented, imperative and functional programming or procedural styles.

- Conceived in 1980 by Guido van Rossum
- Implementation started in 1989

## Features
Python is clearly a powerful object-oriented programming language compare to java, ruby, php, asp.net and perl. Some of the notable features of Python are:

- Write once and run everywhere.
- Uses an elegant syntax, making the programs you write easier to read.
- Comes with a large standard library that supports many common programming tasks.
- You can easily extend python.
- Can also be embedded into an application to provide a programmable interface.
- A variety of basic data types are available.
- Python supports object-oriented programming with classes and multiple inheritance.
- Code can be grouped into modules and packages.
- The language supports raising and catching exceptions, resulting in cleaner error handling.
- Data types are strongly and dynamically typed.
- Python's automatic memory management frees you from having to manually allocate and free memory in your code.
- Large standard library.

## First program
There are an old saying that if you write Hello World! while learning any new language, programming God will be happy and make you a good developer. However, what I believe is more and more you do practice, better and better your knowledge will be. But here to make Python God happy, we will write Hello World program.

From here onwards, we will consider, you are using Linux(Specially Linux Mint or Ubuntu) based machine. However, as I mentioned earlier, you can workon on Windows, Mac OSX too, it depends upon your personal choice.

```
$ python
Python 2.7.6 (default, Jun 22 2015, 17:58:13)
[GCC 4.8.2] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>> print "Hello World!"t
Hello World!
>>>
```
To exit from python shell, you can type below command.
```
>>> exit()
```
Now, we will start using a code editor called Atom which you can download from (https://atom.io/), it's an amazing open source editor which you can use for almost all programming language and web framework. It offers all short of features which you get in any other paid IDE, you name it!

## Start coding in Atom
I would recommend making a "project" folder inside your home directory and make another folder in the name of "pythontutorial". Create a file through command line, open ex1.py in atom IDE. Write same hello world code and run it.

```
$ mkdir project
$ cd project
$ mkdir pythontutorial
$ cd pythontutorial
$ touch ex1.py
```
You can run your python program which is written in ex1.py like this:

```
$ python ex1.py
```

## Comments and pound characters in python
Make a habbit of writing comments for the block of code you written. This will help others and propbably for you also to understand what you wrote. Now, we will see a sample program and output with comments.

```
# My hello world program
print "Hello World!"
# print "This won't run."
print 'I "said" do not touch me.'
```
Output

```
$ python ex1.py
Hello World!
I "said" do not touch me.
```
