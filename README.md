# ToPython

Mathematica package to convert [MATHEMATICA](https://www.wolfram.com/mathematica/) expressions to Python [Numpy](http://www.numpy.org/)

## Input arguments

`x`: your mathematica expression, it can be `numbers`, `literals`,
`complexes` or `lists`;
`numpy\[LetterSpace]prefix`: string defining your Numpy `import` prefix,
e.g.:
* if your used `import numpy as np`, your prefix should be the string
`np`
* if your used `from numpy import *`, your prefix should be the empty
string `''`

## Output

* The Numpy python-ready expression (to be copied as a string)
* The formatted expression will be copied to your clipboard, ready to paste to Python

## Installation

To install the package

1. Download it
2. Click on `Mathematica`' `File menu-> Install->From file...`
3. Select the file on your disk

You should be ready to go.

## Disclaimer

This has not been tested for every possible combinations of all the things, use at your own risks.

## License

[MIT](LICENSE.md) © [Gustavo Wiederhecker](https://github.com/gwiederhecker)
