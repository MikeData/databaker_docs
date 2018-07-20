
=====
Setup
=====


A quick note on Python
======================

A quick note on Python

Databaker should work on python2 but its mainly aimed at (and tested) on python 3 and it's usually best to run it under that unless you've a powerful reason not to.


Windows Install
===============

Install Anaconda for windows (double check the download is for the python3.5+ version).

From there you need to create a new environment with conda and install databaker plus a few dependancies with it.

Option1: Automatically

There's a batch file here that'll do it: https://github.com/ONS-OpenData/dbinstall

Option2: Manually on your command line

execute the following on your command line

* conda create --name <name of environment> python=3.5
* activate <name of environment>
* pip install --upgrade pip
* pip install pandas
* pip install databaker
* pip install jupyter



MAC OS
=====

within a terminal execute the follow commands.

PLEASE NOTE - on a mac <name of environment> will create a directory of that name at your location.

 * brew install python3
 * python3 -m venv <name of environment>
 * source /<name of environment>/bin/activate
 * pip install --upgrade pip
 * pip install pandas
 * pip install databaker
 * pip install jupyter



Environment
===========

Both examples assume you'll be using python virtual environments for running databaker (it's best practice anyway).

Before running any local transformation scripts, make sure the environment is actiated (either "activate <name of environment>" or "source /<name of environment>/bin/activate" depending on operating system.)


Notes on IDE
============

Jupyer notebooks are typically used, as they have useful html table rendering and support a few nice databaker preview functions.

Though you'll need them installed to run databaker (they're automatically imported) they're not really required. if you'd prefer you can edit and use databaker as just python through whatever your IDE of choice is.


Open a Jupyter Notebook
=======================

For anyone unfamiliar with notebooks. If you enter "jupyter notebook" from the command line (with your python env turned on) it'll start a local notebook server for you.
