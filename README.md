# XeTexText
XeTexText extension to Inkscape is a simple fork of TexText from here: http://pav.iki.fi/software/textext/
See the installation instructions from the web site shown above. XeTex (XeLaTex) should be installed.

XeTexText allows one to do the same things as TexText does, but uses XeTex core instead of pdflatex one. Thus you can choose the system fonts. An example of preamble:

\usepackage{fontspec,kantlipsum}

\fontsize{9.5pt}{9.5pt}

\setmainfont{DroidSerif}

\usepackage{mathtext}

\usepackage{amsmath,amsfonts,amssymb}
