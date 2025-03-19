# ml-concepts

Jupyter Notebooks demonstrating fundamental machine learning concepts.

## Getting Started

### Prerequisites

- Python 3.11 is recommended. Tensorflow supports Python 3.9-3.12, so virtual environments using Python 3.13+ will need to be downgrade.

### Setup

1. It's recommended to use a virtual enviornment to manage dependencies.
   <br/>`python3.11 -m ml-concepts-venv`
2. If using a virtual environment, activate virtual environment.
   - macOS/Linux:
     <br/>`source ml-concepts-venv/bin/activate`
   - Windows:
     <br/>`ml-concepts-venv\Scripts\activate`
3. Install Jupyter Notebook.
   <br/>`pip install notebook`
4. Start Jupyter Notebook.
   <br/>`jupyter notebook`

Alternatively, the notebooks can be viewed online using [nbviewer](https://nbviewer.org/github/kevinkli916/ml-concepts/tree/main/).

## Contents

The original Jupyter Notebooks are from [https://cse.msu.edu/~ptan/dmbook/software/](https://cse.msu.edu/~ptan/dmbook/software/). However, the original notebooks are no longer maintained and were updated to use supported versions of Python and packages.

These are the 7 Jupyter Notebooks used:

1. [Data Exploration](https://nbviewer.org/github/kevinkli916/ml-concepts/blob/main/Data_Exploration.ipynb)
2. [Data Preprocessing](https://nbviewer.org/github/kevinkli916/ml-concepts/blob/main/Data_Preprocessing.ipynb)
3. [Regression](https://nbviewer.org/github/kevinkli916/ml-concepts/blob/main/Regression.ipynb)
4. [Classification](https://nbviewer.org/github/kevinkli916/ml-concepts/blob/main/Classification.ipynb)
5. [Text Processing](https://nbviewer.org/github/kevinkli916/ml-concepts/blob/main/Text_Processing.ipynb)
6. [Cluster Analysis](https://nbviewer.org/github/kevinkli916/ml-concepts/blob/main/Clustering.ipynb)
7. [Anomaly Detection](https://nbviewer.org/github/kevinkli916/ml-concepts/blob/main/Anomaly_Detection.ipynb)

The first code block of each notebook installs the required packages for that notebook. Restart the kernel after installing the packages for the new packages to be recognized.

Otherwise, packages required for all packages can be installed all at once using requirements.txt.
<br/>`pip install -r requirements.txt`
