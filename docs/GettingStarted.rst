***************
Getting Started
***************

Source code
===========
Source (Quellcode) code is normally written by humans. Machine (or a computer program) can also generate source code during the translation process of the original quellcode, this would be "generated source code" and should normally not be read or modified by the humans. 

Language types
==============

At highest level there are two types of languages:
 * Programming languages
 * Description (markup) languages

Source code of programming languages is either directly executed or translated to object code or bytecode:
 * interpreted languages also scripts
 * compiled languages

Language structure
==================

Comments
--------

Most languages have a concept of adding comments to the source code. Comments are text blocks that are mostly meant to be read by humans. They are usually skipped if read by the machine.

Comments can be of two different styles, either
 * line end comment - comment ends at end of line
 * block comment - comment text can span multiple lines
 
Common line end comment delimiters are
 * ``#``
 * ``//``
 * ``--``
 * ``REM``
  
Common block comment delimiters are  
 * ``/*`` .. ``*/`` 
 * ``(*`` .. ``*)``
 
 
Statements
----------

End of simple statement (sentence) is usually
 * end of line
 * ``;``

Block statements are blocks of statements that are grouped together, usually marked by
 * ``begin`` .. ``end``
 * ``{`` .. ``}``
 * ``(`` .. ``)``
 
 
Strings
-------
 
Most languages support some sort of strings, common delimiters are:
 * ``"`` .. ``"``
 * ``'`` .. ``'``
  
Numbers
-------

todo
 
Operators
---------

todo

Keywords
--------
 
todo
 
 
Hello World!
============
 Hello World is possible the most famous program in any language. It is very simple program if executed on any modern host O/S. Writing a Hello World for embedded system may be more complicated.
 
C
-

.. code:: c
    
    #include <stdio.h>
    
    int main() {
        print("Hello World!");
    }

C#
--

.. code:: java

    using System;
    
    public class Hello
    {
        public static void Main()
        {
            System.Console.WriteLine("Hello World!");
        }
    }


JavaScript/WShell
-----------------

In Windows javascript can be executed directly from the command shell by starting a file with extension .js

.. code:: javascript
    
    WScript.echo("Hello World!")

This sample will print "Hello World!" in modal dialog box.




Pascal/Delphi
-------------

.. code:: pascal

    Program HelloWorld;
    begin
        Write('Hello World!');
    end.
 
Python
------

There are many incompatible differencies in Python2 vs Python3, as Python2 is officially deprecated we only look at Python3

.. code:: python

    print("Hello World")
    
    









 
 

