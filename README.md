# Simulation Code and Exercises for Complex Fluids and Soft Matter

This repository contains Jupyter notebooks with lecture notes and homework exercises for the Complex Fluids and Soft Matter course CHE 629.

There are two ways you can run this code:

## In the cloud (no setup required)

You can run this code in the cloud, access it with a web browser from any platform, and save your modifications to Google Drive:
* To open a new notebook, choose a link below the notebook in [Google Colab](https://colab.research.google.com/).
  * [Lecture notes](https://colab.research.google.com/github/joaander/hoomd-che629/blob/master/00-Lecture-Notes.ipynb)
  * [Homework part A - Hard Spheres](https://colab.research.google.com/github/joaander/hoomd-che629/blob/master/01-Homework-Hard-Spheres.ipynb)
  * [Homework part B - Hard Sphereocylinders](https://colab.research.google.com/github/joaander/hoomd-che629/blob/master/02-Homework-Hard-Sphereocylinders.ipynb)
* Select the menu option _Runtime->Run All_ to execute the code.
* Add code cells to complete the homework, running the notebook cells as needed.
* When in Colab, choose _File -> Save a copy in Drive_ to save your own copy.
* To continue working where you left off, go to [Google Colab](https://colab.research.google.com/) and select _Google Drive_ to open your modified notebook.
* Submit the completed homework notebook files (with all outputs) in Drive to the grader.

## On your computer (significant setup required)

You can install the software needed to execute the homework on a macOS or Linux platform
(including Windows Subsystem for Linux). You will need some familiarity with the command
prompt to do this:
* Install [miniconda](https://docs.conda.io/en/latest/miniconda.html).
* Download this repository: `git clone https://github.com/joaander/hoomd-che629`
* Create a virtual environment with the needed software: `conda env create -f hoomd-che629/environment.yml`
* Activate the environment: `conda activate hoomd-che629`
* Add Jupyterlab: `conda install jupyterlab -c conda-forge -y`
* Launch Jupyterlab: `jupyter lab` and open the notebooks in `hoomd-che629`
* Delete the cell that installs software in Google Colab as noted in the cell's comment.
* Select the menu option _Run->Run All_ to execute the code.
* Any changes will be saved on your computer.
* Submit the completed homework notebook files (with all outputs) in Drive to the grader.
