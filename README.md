UniFiTh class
=============

This is the README file of the UniFiTh LaTeX class.

Official web page:
http://biccari.altervista.org/c/informatica/latex/unifith.php


About UniFiTh
-------------

UniFiTh is a LaTeX class to typeset theses that adhere to "University of
Florence"'s guidelines for publishing.

It is compatible with two compilation methods: `pdflatex` and `xelatex`.

The version number of this class is reported at the top of the class file
`unifith.cls` and in the pdf manual `unifith-doc.pdf`.

This work has the LPPL maintenance status 'maintained'. The Current Maintainer
of this work is Francesco Biccari.


Documentation
-------------

The documentation is provided in the file [unifith-doc.pdf](unifith-doc.pdf).

Examples are provided in the [examples](examples) folder.


How to install
--------------

UniFiTh can be installed in 3 different ways:

1. The simplest way to install UniFiTh is by the package manager of your TeX
   distribution (TeX Live, MiKTeX or MacTeX). Since the logo of the University
   cannot be uploaded on the TeX distribution repositories, you will get a
   Warning on the frontispiece of the thesis. You can click on this warning to
   obtain the original logo.

2. If you want to install UniFiTh manually, you have to download the unifith.zip
   archive from the official UniFiTh website
   http://biccari.altervista.org/c/informatica/latex/unifith.php or from CTAN.
   The unifith.zip archive contains:
      1. `unifith.cls` (main file)
      2. `unifith-doc.pdf` (manual of `unifith.cls`)
      3. `unifith-doc.tex` (source of the manual)
      4. `README.md` (this file)
      5. `unifilogo.pdf` (university logo, not in CTAN repository)
      6. examples folder with several examples of usage
      7. `unifith.bst` (an english BibTeX style) You can simply copy
         `unifith.cls` and `unifith.bst` together with `unifilogo.pdf` into your
         local work directory where your thesis files will live. Since the logo
         of the University cannot be uploaded on the TeX distribution
         repositories, if you have used the package from CTAN, you will get a
         Warning on the frontispiece of the thesis. You can click on this
         warning to obtain the original logo.

3. The last possibility is copying the files of UniFiTh (discussed in the
   previous point) into your texmf tree (or your localtexmf tree) at these
   locations:
   ```
   <texmf>/tex/latex/unifith/unifith.cls
   <texmf>/tex/latex/unifith/unifilogo.pdf
   <texmf>/doc/latex/unifith/unifith-doc.pdf
   <texmf>/doc/latex/unifith/unifith-doc.tex
   <texmf>/doc/latex/unifith/examples/*.tex
   <texmf>/doc/latex/unifith/README.md
   <texmf>/doc/latex/unifith/LICENSE
   <texmf>/bibtex/bst/unifith/unifith.bst
   ```
   Then, you need to update the file database. Since the logo of the University
   cannot be uploaded on the TeX distribution repositories, you will get a
   Warning on the frontispiece of the thesis. You can click on this warning to
   obtain the original logo.


License
-------

This work may be distributed and/or modified under the conditions of the LaTeX
Project Public License, either version 1.3c of this license or any later
version.

See [LICENSE.txt](LICENSE.txt) for more information.
