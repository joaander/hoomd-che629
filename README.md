# Simulation Code and Exercises for Complex Fluids and Soft Matter

This repository contains Jupyter notebooks with tutorials, code examples, and homework exercises for the Complex Fluids and Soft Matter course CHE 696.

There are two ways you can run this code.

## On your computer (macOS / Linux) - preferred

If you your computer runs the macOS or Linux platform (or you have access to system that does),
you can install the needed software and run this code locally.

You will need some familiarity with the command prompt to do this.
* Install [miniconda](https://docs.conda.io/en/latest/miniconda.html).
* Download this repository: `git clone https://github.com/joaander/hoomd-soft-matter-2021`
* Create a virtual environment with the needed software: `conda env create -f hoomd-soft-matter-2021/environment.yml`
* Activate the environment: `conda activate hoomd-soft-matter-2021`
* Add Jupyterlab: `conda install jupyterlab -c conda-forge -y`
* Launch Jupyterlab: `jupyter lab hoomd-soft-matter-2021/00-index.ipynb` and open `00-index.ipynb`

Follow the links in Jupyter to the tutorial and homework sections and select the menu option _Run->Run All_ to execute the code.
You can modify the code and run again and your changes will be saved on your computer.

## In the cloud

You can run this code in the cloud and access it with a web browser from any platform.
Click the link below and wait a few minutes for binder to start a Jupyterlab instance.
Follow the links in Jupyter to the tutorial and homework sections and select the menu option _Run->Run All_ to execute the code.
You can modify the code and run again, **but your changes will not be saved**.

[Launch on mybinder](https://mybinder.org/v2/gh/joaander/hoomd-soft-matter-2021/HEAD?urlpath=lab%2Ftree%2F00-index.ipynb)

**WARNING** changes will not automatically be saved to your computer. Your changes will be lost when you close the page or your instance times out.
Completing the homework will most likely require several sessions. You can save the modified notebook to your computer at the end of one session
and upload it at the beginning of the next session [as described in the JupyterLab documentation](https://jupyterlab.readthedocs.io/en/stable/user/files.html#uploading-and-downloading)