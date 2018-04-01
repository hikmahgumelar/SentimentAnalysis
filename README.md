# Sentiment Analysis with LSTM networks


## Base info
This repo contains:
* iPython notebook
* raw dataset
* prepared dataset
* wordVector and WordList data

The NN's output is numeric vector. This vector contains of 5 values: []

## Requirements and Installation
In order to run [the iPython notebook](Diploma.ipynb), you'll need the following libraries. 

* [python](https://www.python.org/downloads/)
* [TensorFlow](https://www.tensorflow.org/install/)
* [NumPy](https://docs.scipy.org/doc/numpy/user/install.html)
* [Jupyter](https://jupyter.readthedocs.io/en/latest/install.html)
* [matplotlib](https://matplotlib.org/)
* [pandas](https://pandas.pydata.org/)
* [anaconda](https://anaconda.org/anaconda/python)

### Installation guide (Ubuntu 16.04)

```bash
conda create -n tensorflow-v1.6 python=3.6
conda list
source activate tensorflow-v1.6

pip install tensorflow
conda install ipython
conda install jupyter
conda install matplotlib
conda install ipykernel

jupyter notebook
```
