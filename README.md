# ToPython

Package to convert MATHEMATICA expressions to  Python (Numpy);

INPUT ARGUMENTS;
x: your mathematica expression, it can be numbers, literals, 
complexes or lists;
numpy\[LetterSpace]prefix: string defining your Numpy import prefix, 
e.g.:
if your used "import numpy as np", your prefix should be the string 
"np"
if your used "from numpy import *", your prefix should be the empty 
string ""
;
OUTPUT;
the Numpy python-ready expression (to be copied as a string);
The formatted expression will be copied ot your clipboard, ready to paste on Python;

Not tested for every possible combination; use at your risk

# Installation

To install the package, download it, click on Mathematica' File menu-> Install->From file...
Select the file on your disk and you should be ready to go.
