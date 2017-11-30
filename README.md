# Tensorflow

This repository has some of the code I tried after installing Tensorflow in Anaconda. 

Python version 3.6.2
Tensorflow version 1.4.0

<b>Installation of Tensorflow within Anaconda</b>

First, I tried my installation as follows and it failed while invoking <i>"import tensorflow as tf"</i> with the error message No module found.

<b>Create tensorflow environment in Conda for python 3.5</b>
conda create -n tensorflow python=3.5

<b>Activate the environment tensorflow</b>
activate tensorflow

<b>After activating Tensorflow environment</b>
pip install --ignore-installed --upgrade tensorflow 

<b>To check all the enviroments:</b>
conda info --envs

<b>Invoke Python</b>
$ python

import tensorflow as tf

The above resulted in error. Hence, I removed the tensorflow environment by the command
conda remove --name tensorflow --all

I tried the install using python 3.6 whl by executing: pip install c:\directoryname\tensorflow-1.4.0-cp36-cp36m-win_amd64.whl
It still failed with the same error.

Went to Anaconda Navigator, "Open with Python" for tensorflow environment and the "import tensorflow" worked fine. Seems like the python version that tensorflow environment refers to is the anaconda python that was 3.6.2. 
So, I proceeded with removing the tensorflow environment in Anaconda, Installed the tensorflow package in the root. I could successfully execute tensorflow code via jupyter notebook as well python.
