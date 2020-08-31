# learn-python
learn-python is a repository of Jupyter notebooks that aim to introduce programming in Python. The notebooks are designed to be used in instructor-led sessions but please feel free to explore the notebooks and kickstart learning python! 

## Juypter Notebook Setup

Running the learn-python notebooks is easy, you can get setup by following the simple steps below.

1. Open **Terminal** and navigate with `cd` to a directory where you keep your code/files. E.g (/Users/felixtillyard/Documents/MyCode/)
1. Type the below commands to complete the setup
1. `git clone git@bitbucket.org:snappli-ondemand/learn-python.git` - clone this **learn-python** repository
1. `cd learn-python` - change to the newly created folder
1. `python3 -m venv myenv` - create a new python environment
1. `source myenv/bin/activate` - activate python evironment 
1. `pip install -r requirements.txt` - install python dependencies
1. `jupyter notebook` - run Jupyter notebooks

Upon completing these steps, Jupyter should have loaded in your web browser.

If you are returning to the learn-python notebooks you don't need to clone `learn-python` instead do the following.

1. `cd learn-python` - change to the learn-python folder
1. `git checkout master` - switch the main branch
1. `git pull` - get the latest changes

Then follow steps 5-8 from above.

## Using Jupyter Notebooks

The notebooks are located in the `notebooks` directory. Notebooks are comprised of cells that you can run and edit individually.

## learn-python Notebooks

The following section describes the notebooks in this series so you can select the right notebook for you.

### Introduction to Python

An introduction to the Python language that covers the basics, including *Data Types* (`str`, `tuple`, `list` etc..), *Functions*, *Classes*, *Built-in Functions* and *Library Modules*.

### Introduction to Data Analysis with Python

An introduction to the libraries used for Data Analysis with Python (`numpy`, `pandas` etc..). Includes the basics of how to, load, manipulate, analyse and visualise data with Python.

### Introduction to Python for Automation and CLI

Outside of the Jupyter notebook this lessons is an introduction to how we can use the Python skills we have learnt to automate some basic tasks. Including a brief tour of the Python standard library with `logging` and `requests`. How to handle script arguments / log / report progress. CLI with `click`.

### Intermediate Python 1

This notebook provides a gentle introduction to some intermediate topics and concepts that are part of the core Python language (Decorators and Generators)
