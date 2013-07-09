Common List Book in ePub Format
===============================

This is an unofficial ePub version of the Practical Common Lisp book
[available online](http://www.gigamonkeys.com/book/). 

Build
-----

The `Makefile` depends on [Pandoc](http://johnmacfarlane.net/pandoc/) to
create the eBooks. If you have
[Kindlegen](http://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000765211)
you can generate an eBook that is readable on the Kindle.

To build the ePub just run any of the following commands at the command line:

- `make` will generate the PDF, ePub and Kindle files.
- `make pdf`, `make epub` and `make kindle` will only generate the
  requested format.

The files will be available in the `_build` folder after the operation
completes.

Troubleshooting
---------------

If you reuse this Makefile to create your own eBooks, make sure that the
input files are saved with the UTF-8 encoding, which is the one that
Pandoc expects.

Download
--------

The source code of the book can be downloaded in
[tar.gz](http://www.gigamonkeys.com/book/practicals-1.0.3.tar.gz) and
[zip](http://www.gigamonkeys.com/book/practicals-1.0.3.zip) formats from
the original website.

Copyright
---------

Copyright © 2003-2009, Peter Seibel. 

