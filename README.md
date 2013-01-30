Changelist package --- Manage change lists
==========================================

License
-------
Copyright 2012 by Julien Tanguy (julien.tanguy@jhome.fr).
All rights reserved.

This work may be distributed and/or modified under the conditions of
the LaTeX Project Public License, either version 1.3 of this license
or (at your option) any later version. The latest version of the
license is in

    http://www.latex-project.org/lppl.txt

and version 1.3 or later is part of all distributions of LaTeX
version 2003/12/01 or later.

This work has the LPPL maintenance status "maintained".
The Current Maintainer of this work is Julien Tanguy (julien.tanguy@jhome.fr).

Installation
------------
To generate the package and the associated documentation, run

    pdflatex changelist.dtx
    makeindex -s gind.ist -o changelist.ind changelist.idx
    makeindex -s gglo.ist -o changelist.gls changelist.glo
    pdflatex changelist.dtx

Then you need to move all files to their appropriate location in your home TDS tree.[^1]

    changelist.dtx --> TEXMFHOME/source/latex/changelist/
    changelist.ins --> TEXMFHOME/source/latex/changelist/
    changelist.sty --> TEXMFHOME/tex/latex/changelist/
    frenchb.cfg    --> TEXMFHOME/tex/latex/changelist/
    changelist.pdf --> TEXMFHOME/doc/latex/changelist/

[^1]: If you don't know where is your home TDS tree or what is a TDS tree,
      please contact the author for more information

