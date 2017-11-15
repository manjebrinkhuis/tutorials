# Prepare your Windows machine for statistics

## Install Miniconda

Go to https://conda.io/miniconda.html

and download the installer for Miniconda for Python 3 point something (3.6 at time of writing).

Or follow this link: https://repo.continuum.io/miniconda/Miniconda3-latest-Windows-x86_64.exe

Install Miniconda with all the recommended defaults. That is:
- Install for just me (recommended)
- Install in C:/Users/"username"/Miniconda
- Don´t add Miniconda to your system path (i.e. don´t tick the mark that says to do that).

## Install R

From the windows start menu, open Anaconda prompt, type and press enter:

```
conda install -c r r r-essentials
```

Wait until conda has collected information and proceed by typing y (or press enter when you see "[y]/n", meaning that y is the default response), to confirm that you want to install.

Wait (quite) a bit until R is installed.

You can test by typing and press enter.

```
R
```

This should give you an R-console.

## Install R-studio

Just the R console is not a very user friendly interface, so we can also install R-studio using conda.

Type and press enter, and confirm installation:

```
conda install rstudio
```

You may get a pop-up that asks you if python may have access to your system. Press ok to confirm.

To run rstudio, find it in the windows start menu.

## Install jupyter

Two alternative graphical user interfaces are jupyter notebook and jupyterlab. These make use of your web browser. Jupyter notebook is included by default.

To run Jupyter notebook, type (in the Anaconda prompt):

```
jupyter notebook
```

You can install jupyter lab, a new and improved version of the jupyter notebook, but still in development phase. Type and enter:

```
conda install jupyterlab
```

To run Jupyter lab, type (in the Anaconda prompt):

```
jupyter lab
```

Now you have everything you need and more to run your analysis!
