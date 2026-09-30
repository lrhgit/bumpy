# Documentation source and build scripts

This directory contains the DocOnce source files and build scripts for the
project. For an introduction, project history, and links to the published
material, see the [main README](../../README.md).

## Source files

- `basics.do.txt` — basic scientific Python demonstrations
- `bumpy.do.txt` — a scientific application involving mechanical vibrations
- `lectures-basics.do.txt` and `lectures-bumpy.do.txt` — wrappers for lecture
  and slide material
- `lectures_tkt4140.do.txt` — course-specific lecture material

Supporting programs and media are located in:

- `src-bumpy/`
- `lec-bumpy/`
- `fig-bumpy/`
- `mov-bumpy/`

## Building

- `make.sh` builds the main material. It currently defaults to `basics` and
  generates HTML and Jupyter notebook output.
- `make_lec.sh` builds lecture and slide collections in several formats.
- `clean.sh` removes generated working files.

Files intended for publication are copied to [`../pub`](../pub/).

The DocOnce sources support output such as HTML, Jupyter notebooks (`ipynb`),
slides, PDF, and Sphinx.
