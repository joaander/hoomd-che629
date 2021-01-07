# Simulation Code and Exercises for Complex Fluids and Soft Matter

This repository contains Jupyter notebooks with tutorials, code examples, and exercises for the Complex Fluids and Soft Matter course.

There are two ways you can run this code.

## In the cloud

You can run this code in the cloud and access it with a web browser from any platform.
Click the link below and wait a few moments for [mybinder](https://mybinder.org/) to start a [Jupyterlab](http://jupyterlab.io/) instance.
Follow the links in Jupyter to the tutorial sections and select the menu option _Run->Run All_ to execute the code.
You can modify the code and run again, **but your changes will not be saved**.

[Launch on mybinder](https://mybinder.org/v2/gh/joaander/hoomd-soft-matter-2021/HEAD?urlpath=lab%2F00-index.ipynb)

## On your computer (macOS / Linux)

If you your computer runs the macOS or Linux platform, you can install the needed software and run this code locally.
You will need some familiarity with the command prompt to do this.
* Install [miniconda](https://docs.conda.io/en/latest/miniconda.html).
* Download this repository: `git clone https://github.com/joaander/hoomd-soft-matter-2021`
* Create a virtual environment with the needed software: `conda env create -f hoomd-soft-matter-2021/environment.yml`
* Activate the environment: `conda activate hoomd-soft-matter-2021`
* Add Jupyterlab: `conda install jupyterlab -c conda-forge -y`
* Launch Jupyterlab: `jupyter lab hoomd-soft-matter-2021/00-index.ipynb` and open `00-index.ipynb`

Follow the links in Jupyter to the tutorial sections and select the menu option _Run->Run All_ to execute the code.
You can modify the code and run again and your changes will be saved on your computer.
