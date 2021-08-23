|discord|_
|test|_
|stars|_

About
=====

A `Brainfuck`_ interpreter in the `Mys programming language`_.

Project: https://github.com/mys-lang/package-brainfuck

Installation
============

.. code-block:: myscon

   ❯ mys install brainfuck

Running Brainfuck programs
==========================

There are Brainfuck programs in the `programs folder`_.

Hello World
-----------

.. code-block:: myscon

   ❯ wget https://raw.githubusercontent.com/mys-lang/package-brainfuck/main/programs/hello_world.bf
   ❯ brainfuck hello_world.bf
   Hello World!

A tiny OS
---------

.. code-block:: myscon

   ❯ wget https://raw.githubusercontent.com/mys-lang/package-brainfuck/main/programs/os.bf
   ❯ brainfuck os.bf
   STARTING
   BRAINOS VER 1
   A FOR HELP
   OS>A
   A > HELP
   B > CHARCODE
   Z > HALT
   OS>B
   ENTER CHAR
   >1
   31
   OS>Z
   HALTING

API
===

.. mysfile:: src/lib.mys

.. |discord| image:: https://img.shields.io/discord/777073391320170507?label=Discord&logo=discord&logoColor=white
.. _discord: https://discord.gg/GFDN7JvWKS

.. |test| image:: https://github.com/mys-lang/package-brainfuck/actions/workflows/pythonpackage.yml/badge.svg
.. _test: https://github.com/mys-lang/package-brainfuck/actions/workflows/pythonpackage.yml

.. |stars| image:: https://img.shields.io/github/stars/mys-lang/package-brainfuck?style=social
.. _stars: https://github.com/mys-lang/package-brainfuck

.. _Mys programming language: https://mys-lang.org
.. _Brainfuck: https://en.wikipedia.org/wiki/Brainfuck
.. _programs folder: https://github.com/mys-lang/package-brainfuck/tree/main/programs
