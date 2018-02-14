======
What is databaker?
======

Databaker is a python library for writing scripts than helps turn human readable spreadsheets into machine readable one-observation-per-row CSVs.

Simply put, it's a set of python commands that takes data that looks like this:

.. image:: /_static/one.png

And turns it into something that looks like this.

.. image:: /_static/two.png

It does so in a largely repeatable way (i.e as long as the structure remains reasonably consistent you can us successfully rerun the script if more time/dates/data is added to the source).

Please note the output structure us an example only. The exact columns and structure for output can be specified by the user.
