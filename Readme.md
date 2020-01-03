To install Anaconda follow the instructions in the following webpage:
https://www.digitalocean.com/community/tutorials/how-to-install-anaconda-on-ubuntu-18-04-quickstart

Create a conda environment for the PyBullet tutorial:
$ conda create --name pyb_env

Switch to the newly create environment (you will notice the name of the environment on the command line in the extreme left):
$ conda activate pyb_env


Once in the desired environemtn install the following packages:
$ conda install nb_conda_kernels

Install PyBullet (while in the environment):
$ pip install pybullet


To check the installation launch:
$ python

Inside the python environment import the pybullet library:
>> import pybullet

If this command executes without any error then the pybullet installation is successful.


Check the Jupyter notebook by running the following command in the bash shell:
$ jupyter notebook

This command will provide a URL. Run the URL in a browser (Firefox). If a web page opens up, then the Jupyter software is successfully installed.
