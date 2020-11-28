Violent
=======

Rewrite of Violet in ``lark-parser``.
To run the lexer:

.. code-block:: python

    from lark import Lark
    parser = Lark(open('violent/grammar.lark'), start='file_input', parser='lalr')
    parsed = parser.parse('...')
    print(parsed.pretty())

A statically typed, interpreted language in Python.

⚠️ This language is still a work in progress, and mostly just a learning experience. ⚠️

Sample "Hello World" example:

.. code-block:: none

   import { print } from std;

   fun main(argv: List[String]) {
       print("Hello, world!");
   }

Other examples can be found in the ``examples/`` directory.

Clone the repo, and use ``python -m violent <file>`` to invoke the interpreter.
