This repository contains an example for how to use nbparamaterise to run a jupyter notebook that trains a neural network in batch mode, changing the training parameters for each run.

The nbparameterise library: https://pypi.org/project/nbparameterise/
Github containing example code to use nbparameterise: https://github.com/takluyver/nbparameterise

The files
"environment_tensorflow_batch.yml" the environment file for this work. 
Create the environment using the command: "conda env create -f environment_tensorflow_batch.yml". 
Activate it using the command: "conda activate tensorflow_batch".

"tensorflow_iris.ipynb": python code to train a neural network (using tensorflow, keras) on the iris dataset.

"batch_run_iris.ipynb": python code to run ""tensorflow_iris.ipynb" multiple times, using the library nbparameterise to change the parameters for each run. Saves each ipynb.

\data\iris_binary.csv: the dataset iris (which has been reduced to just two categories for this example). Contains four independany variables, and one dependant variable).
