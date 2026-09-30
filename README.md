# bumpy: Scientific Python examples

A brief, application-driven introduction to scientific computing with Python,
using examples from basic physics.

## Try the basics tutorial

Run the tutorial directly in your browser:

[![Open basics in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lrhgit/bumpy/blob/master/doc/pub/basics.ipynb)

No local Python installation is required.

## Contents

The repository contains two documents:

- **basics** introduces fundamental Python concepts such as variables, loops,
  conditionals, functions, arrays, plotting, files, and classes through a
  simple mathematical example.
- **bumpy** presents a more complete scientific application involving the
  analysis of mechanical vibrations. It also introduces command-line input,
  storage of objects, downloading data, unit testing, symbolic mathematics,
  and modules.

## History and current focus

The material was originally developed by
[Hans Petter Langtangen](https://www.simula.no/hpl-memorial) (HPL), with
contributions by Leif Rune Hellevik (LRH). Following HPL's passing, LRH has
maintained and updated the `basics` material; this work has continued since
2016.

Recent development and use have focused mainly on `basics` as a collection of
demonstrations. Other applications of the material are covered elsewhere.

## Goal

The tutorials are intended to help readers move quickly from Matlab-style
programming to scientific programming in Python. This foundation makes it
easier to follow scientific courses and teaching material that use Python.

The examples are deliberately brief and application-driven.

## Available formats

The material is available in more forms than traditional text and slides.
Jupyter notebooks (`ipynb`) have become particularly useful with Google Colab
and JupyterHub at NTNU.

Available generated material includes:

- [the basics Jupyter notebook](doc/pub/basics.ipynb)
- [the basics HTML version](doc/pub/basics.html)
- slides and other generated documents in [`doc/pub`](doc/pub/)

The DocOnce sources can also be used to generate PDF and Sphinx output.

## Source and building

The DocOnce source files and build scripts are located in
[`doc/src`](doc/src/).

See the [documentation source README](doc/src/README.md) for details about the
source files, build scripts, and generated output.
