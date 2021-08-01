# The CoverPage Package

The package `CoverPage` was created to supplement
scientific papers with a cover page containing bibliographical
information, a copyright notice, and/or some logos of the author's
institution. The cover page is created (almost) automatically; this
is done by parsing BibTeX information corresponding to the
main document and reading a configuration file in which the author
can set information like the affiliation he or she is associated with.

## Required packages

This package needs four other packages (`keyval`, `url`,
`textcomp`, and `verbatim`), but all of them are standard
packages and should be part of every LaTeX installation.

## Installation

The package `CoverPage` is distributed as `dtx` archive.
If you do not know how to install such archives, see documentation
"CoverPage.pdf" (for a short description) or look at some FAQ list,
e.g., <https://texfaq.org/FAQ-installthings>.

## File list

The term "CoverPage package" refers to the following files:

* `CoverPage.dtx`           --  code/documenation archive
* `CoverPage.ins`           --  installer
* `CoverPage.pdf`           --  documentation
* `SimpleSample.tex`        --  sample document, source code
* `SimpleSample.pdf`        --  sample document, result
* `SimpleSample.BibTex.txt` --  required BibTeX data
* `ECCV06Sample.pdf`        --  more realistic example (only pdf)
* `README-md`               --  this file

## License

`SPDX-License-Identifier: LPPL-1.3c+`
