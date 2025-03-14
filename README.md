# intro_to_python
Introduction to Programming with Python


## Colab Notebooks

The material can be accessed via Google Colab Notebook:
- [Intro to Python](https://colab.research.google.com/github/SCIE2100-learning-hub/intro_to_python/blob/master/Intro_to_Python_InClass_2025.ipynb)

## Before you attend the practical session in Week 4:
You will need Anaconda for Python (for any OS) installed on your computer. We will use Anaconda's Jupyter Notebook to learn Python. From the main menu, see **Python Reference Guide > Python**: Installation Guide for more information about installing Anaconda on your computer.


## Local installation

Alternatively, if you want to run it locally, we suggest you use [Anaconda](https://docs.anaconda.com/free/anaconda/install/) (or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)) to manage a virtual environment and install dependencies.


### First, create an environment with the following command:

```bash
$ conda create -n workshop_ml
```

### Then, install dependencies via pip:


```bash
$ conda activate workshop_ml

$ conda install python=3.10

$ pip install -r requirements.txt
```

### If you need to run under this environment at any time, use the following command to activate it and open the notebook:

```bash
$ conda activate workshop_ml

$ jupyter notebook
```
