=============================
Setup development environment
=============================

1. Install prerequisites
------------------------

* Debian 12
* CPython 3.11
* GNU `Make`


2. Clone the source repository
------------------------------

::

   $ git clone https://github.com/mete0r/pyhwp.git

3. Initialize the environment
------------------------------

Bootstrap development environment::

   $ make bootstrap
   $ . .venv/bin/activate

4. Check basic stuffs
---------------------

Run `hwp5proc`::

   $ bin/hwp5proc --help

To run tests::

   $ tox
