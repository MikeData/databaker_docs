
=====
The Four Stages
=====

You can roughly split every databaker extraction into three stages. Each stage serves a different purpose and uses different syntactic tools which will be covered in its own section later.


1. Loading spreadsheets and tabs
==============================

This is a straight forward and won't require its own section.

.. image:: /_static/loadExcel.png

We can ignore the lines regarding naming the output file. This is for later in the process.


2. Selection
=========

This is wholly concerned with the logic behind selecting cells of data based on their content of formatting, then assigning that selection to a variable.

Typical Examples:

* select all bold cells in column B and assign to a variable
* select all cells containing the text "female" from a tab and assign to a variable

The syntax for this will be covered in more detail later.


3. Extraction
==========

This process consists of creating instructions that specify the relationship between those cells you have selected as your observations (the 'values' you are trying to extract). And those cells that contain the dimension for those observations.

We'll cover this in more detail later and in the walkthrough (it's worth spending some time on understanding this part of the walkthrough).

It may also be worth looking in the term "OLAP cube" if its unfamiliar. As it's a help in understanding the goal of this stage.

The stage will be covered in more detail later.


4. Post Processing
===============

This is the clean-up stage of the extraction. In some cases nothing extra will need to be done. But if additional cleaning operations are required this stage allows us to leverage the python Pandas dataframe for ad-hoc data cleaning functionality.

If you're unfamiliar with pandas then some basic tutorials around data loading and manipulation (ignore anything to with graphs and plotting) could be a valuable complementary learning path.

The stage will be covered in more detail later.
