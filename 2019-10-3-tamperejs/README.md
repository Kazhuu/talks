# Why You Should Give Vim a Try

Talk hosted on TampereJS on 3.10.2019 and is done with LaTex Beamer
presentation. Slides are available as main.pdf file.

## Prerequisites

Python package `pygments` is needed for compiling code snippets which can be
installed with pip or pipenv. Also LaTeX packages are also needed compiling. To
install LaTex on Ubuntu run

```
sudo apt install texlive-full
```

## Compiling presentation

### Using Pipenv

To install needed packages and activate virtual environment run

```
pipenv install
pipenv shell
```

### Using Pip

If you don't want to use virtual environments or pipenv then just install
`pygments` with

```
pip install pygments
```

### Compiling

After this compile `main.tex` file to pdf presentation with

```
pdflatex -shell-escape main.tex
```
