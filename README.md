# ToPython

FUNCTION TO CONVERT MATHEMATICA EXPRESSION TO NUMPY;
----------------------------------------------------
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
------------------------------------------------------
Not tested for every possible combination; use at your risk
