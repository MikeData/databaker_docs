
======
Further Usage
======

This isn't really learning materials but I'm going to touch on it briefly.

Databaker was designed with a firm eye on becoming part of an ETL (extraction transformation load) pipeline, and does so principally by being "just another python library" which can freely interact with anything else in the python echosphere.

Ad-hoc examples:
======

This is pretty limitless, so I've just included a few non-standard things we've done as well as things we probably will at some point.


Automated Monitoring and Processing
======

You can use something like beautifulSoup to monitor content on a web page (i.e wait for the next release of spreadsheet x?). When its released you can get it with requests and databake it. No manual interaction required.



Responsive Transformations
======

Python supports most message queue systems. Its relatively straight forward to turn a databaker script you run yourself into something that sits on a server as an on-demand service.


Dimensioned Dataset Viewer
======
If you combine databaker with a little pandas and flask you could load a disorganised dataset straight into a user-friendly html embedded pivot table.


Analysis From Uncleaned Data Sources
=====

This one is straight from the sensible code examples:
https://github.com/sensiblecodeio/databaker/blob/master/databaker/tutorial/Real_world_example.ipynb
