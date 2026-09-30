This directory tree contains the source for two documents:

 * A very basic introduction to scientific programming in Python (basics)
 * A demonstration of Python for a real scientific application (bumpy)

The material was originally developed by Hans Petter Langtangen (HPL),
with contributions by Leif Rune Hellevik (LRH). Following HPL's passing,
LRH has maintained and updated the basics material; the source header records
this work as continuing since 2016.

Recent use has focused on basics as a collection of demonstrations. Other
applications of the material are covered elsewhere.

The source is written in DocOnce and can be published in more forms than text
and slides. In particular, Jupyter notebooks (ipynb) have become a more
appealing way to use the material with the advent of Google Colab and
JupyterHub at NTNU. The generated forms also include HTML, PDF, and Sphinx.

The main source files are basics.do.txt and bumpy.do.txt. Slide material is in
the lec-bumpy subdirectory, with wrapper files for title, author, and related
metadata in lectures-basics.do.txt and lectures-bumpy.do.txt.

The script make.sh compiles the two texts, while make_lec.sh builds the two
slide collections. Generated documents are copied to ../pub for publishing on
the web.
