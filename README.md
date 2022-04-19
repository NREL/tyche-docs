# Tyche Documentation

This repository will hold up-to-date compiled documentation for the *Tyche* (*T*echnolog*Y* *Ch*aracterization and *E*valuation) software. Open `Tyche.pdf` to begin.

## Updating

To re-generate this documentation:

* Clone this repository and [tyche](https://github.com/NREL/tyche) to your local machine.
* Install a LaTeX distribution if you don't already have one. [MiKTeX](https://miktex.org/) works and can be installed locally.
* Open an Anaconda prompt and change the directory to your local tyche repository directory.
* Use sphinx to generate a `.tex` file in this repository directory:
```
sphinx-build -b latex path\to\tyche\repo path\to\tyche-docs\repo
```
* Change the directory to your local tyche-docs repository directory.
* Use the LaTeX distribution to generate the documentation PDF:
```
xelatex Tyche.tex
```
* Use git to commit and push the updated documentation to this repository.
