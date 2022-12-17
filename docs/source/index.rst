Welcome to openMTPK's documentation.
===================================
**openMTPK** is a open-source mathematics package written in C++ originally inspired from my 
undergraduate coursework at Northern Arizona University in mathematics, cybersecurity 
and computer science, Python based projects in CS 499 Contemporary Developments, Deep
Learning, developments on vpaSTRM as well as my increasing curiosity of the all things 
pure and applied in the realm of mathematics.
The goal is to make a reusable mathematics library similar to the use of math.h allowing
users to call within their own projects. Starting with some implementations of basics of 
different mathematical topics like arithmetic, calculus, statistics, linear algebra, etc. 
in conjunction with more advanced algorithms seen in the blend of such topics, branches 
of Machine Learning, image processing and much more. Some of the modules operate in a 
circular dependant way, for example arithmetic operations seen in linear algebra vector 
operations that can be seen in algorithms implemented into the deep learning module. Many of
these implementations were first prototypes in Wolfram Mathetmatica, then converted to C++ 
code for the package. Look in the drivers folder for examples on using these tools in your 
own project. This paper will highlight the modules in use, the mathematics/logic behind 
them, future developments, and more. \linebreak

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   Installation
   Modules
   Language Bindings
   usage
   api
