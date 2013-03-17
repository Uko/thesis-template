Tech info:
----------

  1. This template needs **XeLaTeX** to compile.
  2. We use **[Liberation(tm) Fonts](https://fedorahosted.org/liberation-fonts/)** font family. Version 2.00.1 of the typefaces is bundled in this package.

:exclamation: **Please Note:** font loading from external files requires pretty new version of TeX environment. MacTeX & Tex Live from 2012 year should work fine. Check out the [guide](http://askubuntu.com/a/163683/112623) on how to install on Ubuntu 12.04. No status on MikTeX compatibility is available yet.

Branch info:
------------
  * [![Build Status](https://travis-ci.org/Uko/thesis-template.png?branch=master)](https://travis-ci.org/Uko/thesis-template)
    **master** - contains basic template for thesis.
  * [![Build Status](https://travis-ci.org/Uko/thesis-template.png?branch=summery)](https://travis-ci.org/Uko/thesis-template)
    **summery** - reduced template suitable for summeries.
  * [![Build Status](https://travis-ci.org/Uko/thesis-template.png?branch=summery-light)](https://travis-ci.org/Uko/thesis-template)
    **summery-light** - a minimal template used for a kind of semi-summery papers that do not require table of contents and bibliography.

Installing TeX family:
----------------------
  * **OS X**: [MacTeX](http://tug.org/mactex/)
  * **Linux**: TeX should be available in your package manager, otherwise use [TeX Live](http://www.tug.org/texlive/)
  * **Windows**: [MikTeX](http://miktex.org)

:pencil: You can use whatever editor & compiler you want off course, but if you have just discovered TeX ecosystem and do not know where to start, I can recommend the [Texmaker](http://www.xm1math.net/texmaker/).

Note that you can build PDF just by running
    
    make
in a project directory.
