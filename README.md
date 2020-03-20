# About

This is a function depo. That is to say, I collect functions here that might
be useful way down the line. There is no restrictions on programming languages,
but I would generally avoid propriety languages, like Matlab, and would
definitely prefer scripting languages, like stuff that need no compiling.

# Rules

Because it is not only for programmers, but for anyone using these languages
for writing experiments, doing data analysis... I came up with some rules to
make everything tidy.

* **Filenames** should be straightforward, contain no spaces and have less then or
equal to 12 characters,
* **Line-length** is set to 80 characters.
* **Comment your code, you philistine!!!!**
* **Descriptions** of what each function does have to be inserted before the code. **Subfunctions** should be preceded with a description of why they are there.
* **Folder structure** us semi-random and is in development.
* **List** your function below and introduce it in a few words, so we know what it is. Try to do it in alphabetical order. We all know the ABC, so it should not be a problem...?
* **Authorship** must be provided for functions. If you found it on Stackoverflow or GitHub, then provide the name, username, maybe a link to the topic.


# Functions included

## data

* **cormatrixTEX.R** : Creates a correlation matrix and allows you to save it as a tex file.
* **mergesort.R** : A general-purpose comparison based sorting algorithm
* **normFESCA.R** : A feature-scaling algorithm to standardize the range of independent variables
* **sortQUICK.R** : A partition-exchange sort algorithm placing an element of an array in order
* **sortSELECT.R** : A selection-sort algorithm, which is an in-place comparison. Good for large lists.

## experiment

* **shuffle.js** : Javascript function to shuffle list. Essential for counterbalancing stimuli.
* **stimCHANGE.py** : A psychopy script that demonstrates how to use dynamic stimuli.

## utility

* **flatten.pl** : Batch flatten pdfs by converting it to ps and then back to pdf. Creates very large files.
* **flatten.py** : Same as flatten.pl, but in python.
* **printall** : bash script to print (and by proxy flatten) all files in the current directory to pdf. File sizes are comperable.

## art

* **frcKRONECKER.R** : Creates a fractal with [Kronecker product of two matrices](https://en.wikipedia.org/wiki/Kronecker_product).
* **frcMANDLBROT.R** : Creates a fractal with a Mandalbrot set](https://en.wikipedia.org/wiki/Mandelbrot_set).

