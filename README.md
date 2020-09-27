# Machine Learning Exercises
A number of python based machine learning exercises written in Jupyter notebooks.

## Overview

### Lab 1
A Collection of Python warm up exercises as well as problems to get aquainted with Numpy and MatPlotLib.

### Lab 2
A Problem set that explores how to approach Clustering.

## Installation
These labs have a number of dependencies, most of which are outlines in the instructions.
For brevity though, a brief set of instructions are laid out here.

Note: These were worked on using a Debian based Linux environment - if you are running windows,
simply use a [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install-win10) included in Windows 10.

You will need Python 3.8 or greater.
```
sudo apt install python3
sudo apt install pip3

pip install numpy matplotlib jupyter scikit-learn

# Then add pip's binary path to your shells global PATH. (~/.local/bin)
export PATH=/home/USERNAME/.local/bin:$PATH"


```

## Usage
All thats left to do is `cd` into the directory if you haven't already and run `jupyter notebook`.
At that point you can navigate to http://localhost:8888
