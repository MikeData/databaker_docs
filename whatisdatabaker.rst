======
What is databaker?
======

Databaker is a python library for writing scripts than helps turn human readable spreadsheets into machine readable CSVs.

Simply put, it's a set of python commands that takes data that looks like this:

.. image:: /_static/1.png

And turns it into something that looks like this.

.. image:: /_static/2.png

So data structured as one observation per line.

It does so in a largely repeatable way (i.e as long as the structure remains reasonably consistent it can us rerun if more time/dates/data is added to the source).
