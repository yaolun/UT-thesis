UTThesis
--------


This class was designed to match the University of Texas at Austin Guidelines, 2013.
Perfect correspondence is not guaranteed, but should be close. It is forked from Henry Schreiner's
[repository](https://bitbucket.org/henryiii/texutthesis) on bitbucket.

This is a class for building a UT thesis. It uses standard latex unpacking procedures
for a single dtx file. Running latex on the dtx file will produce all needed files.
Running tex on the dtx file will only produce necessary files (not documentation).
Place at least the .cls in your thesis folder, or in the standard location for
installed tex files.

Included files
==============

`readme.rst`:  The file you are reading.

`samplethesis.tex`:   A sample thesis file, to demonstrate usage.

`utthesis.dtx`:  The file that generates the other files. Run this through pdflatex.

Generated files
===============

`utthesis.cls`:  The class file that you'll use to set the class for your thesis.

`utthesis.pdf`:  A detailed help manual for the class.
  

`utthesis.cwl`:  A file for TexStudio to provide highlighting for the new commands.
  
To setup:
=========

- Fork this repository
- run `pdflatex utthesis.dtx` (this makes the .cls files and such)
- Follow ``samplethesis.tex`` to begin writing your thesis!
