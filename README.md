Inkling Language for Computers
==============================
This is a set of documents, fonts, and other utilities to aid in the implementation of support for the [Inkling fan-language](http://squidboards.com/threads/2914/).

The central focus of this project is the creation and implementation of two common, standardized character encodings for Inkling:

* A simple 8-bit superset of the American Standard Code for Information Interchange.
* The assignment of a portion of the Private Use Area (PUA) in the Basic Multi-lingual Pane (BMP) of Unicode.

The simple encoding is intended for special cases _only_ and has a few design flaws. *It is strongly recommended that the PUA assignment is used wherever reasonably possible.*

The PUA assignments will be coordinated with the existing assignments for other constructed scripts in the [Under-ConScript Unicode Registry](http://www.kreativekorp.com/ucsur/).
