# Tensorflow

Some of the code I tried after installing Tensorflow in Anaconda

<b>Installation of Tensorflow within Anaconda</b>

First, I tried my installation as follows and it failed while invoking <i>"import tensorflow as tf"</i> with the error message No module found.

#Create tensorflow environment in Conda for python 3.5
conda create -n tensorflow python=3.5

#Activate the environment tensorflow
activate tensorflow

#After activating Tensorflow environment
pip install --ignore-installed --upgrade tensorflow 

#To check all the enviroments:
conda info --envs

#Invoke Python
$ python

import tensorflow as tf

The above resulted in error. Hence, I removed the tensorflow environment by the command
conda remove --name tensorflow --all

I tried the install using python 3.6 whl by executing: pip install c:\directoryname\tensorflow-1.4.0-cp36-cp36m-win_amd64.whl
It still failed with the same error.

Went to Anaconda Navigator, "Open with Python" for tensorflow environment and the "import tensorflow" worked fine. Seems like the python version that tensorflow environment refers to is the anaconda python that was 3.6.2. 
So, I proceeded with removing the tensorflow environment in Anaconda, Installed the tensorflow package in the root. I could successfully execute tensorflow code via jupyter notebook as well python.
