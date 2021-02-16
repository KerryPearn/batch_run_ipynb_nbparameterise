This repository contains an example for how to use nbparamaterise to run a jupyter notebook that trains a neural network in batch mode, changing the training parameters for each run.

## The original source for nbparameterise:
1. The nbparameterise library: https://pypi.org/project/nbparameterise/
1. Github containing example code to use nbparameterise: https://github.com/takluyver/nbparameterise

## The files
1. "environment_tensorflow_batch.yml" the environment file for this work. 
Create the environment using the command: "conda env create -f environment_tensorflow_batch.yml". 
Activate it using the command: "conda activate tensorflow_batch".

1. "tensorflow_api.ipynb": python code to train a neural network (using tensorflow, keras) on the titanic dataset.

1. "batch_running_ipynb.ipynb": python code to run ""tensorflow_api.ipynb" multiple times, using the library nbparameterise to change the parameters for each run. Saves each ipynb.

1. \data\processed_data.csv: the processed titanic dataset.
