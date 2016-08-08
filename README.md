# usableR
**A compilation of often used and re-usable R functions.**


###1. buildR###
A function to install R packages and optionally load them.
Function accepts a string vector (of names of functions).
The function will attempt to install from the CRAN repository and on fail, will attempt to install from github.
