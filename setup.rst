
=====
Setup
=====


A quick note on Python
======================

A quick note on Python

Databaker should work on python2 but its mainly aimed at (and tested) on python 3 and it's usually best to run it under that unless you've a powerful reason not to.

Under windows it's easiest to install Anaconda python3 64bit (make sure it's the python3.5+ version, as a py2 version does exist).

On a mac you can just:

`brew install python3`.


Environment
===========

You need to make sure you're in the correct python environment before doing the installations.

WINDOWS USERS - You need to be on the command line, if using Anaconda (you should be) look for the anaconda command prompt in your installed programs, it should be there. That should open a version of your command prompt with the prefix (Anaconda).

MAC USERS - You'll need to create a new python3 environment for databaker work using virtual env. Navigate to a suitable directory then `python3 -m venv <env name>` followed by `source <env name>/bin/activate`.



Install
=========

Use the following commands on the command line.

`pip install pandas`

`pip install databaker`

`pip install jupyter`

Some of these may say "already installed" but that's fine. Better safe than sorry.


Open a Jupyter Notebook
=======================

Still on the command line. If you enter 'jupyer notebook' it should spawn a new notebook for you to use.
