# ml-concepts

Jupyter Notebooks demonstrating fundamental machine learning concepts.

## Getting Started

### Prerequisites

- Python 3.11 is recommended. Tensorflow supports Python 3.9-3.12, so virtual environments using Python 3.13+ will need to downgrade.

### Setup

1. It's recommended to use a virtual enviornment to manage dependencies.
   <br/>`python3.11 -m ml-concepts-venv `
2. If using a virtual environment, activate virtual environment.

- macOS/Linux:
  <br/>`source ml-concepts-venv/bin/activate`
- Windows:
  <br/>`ml-concepts-venv\Scripts\activate`

3. Install Jupyter Notebook.
   <br/>`pip install notebook`
4. Start Jupyter Notebook.
   <br/>`jupyter notebook`

## Contents

The original Jupyter Notebooks are from [https://cse.msu.edu/~ptan/dmbook/software/](https://cse.msu.edu/~ptan/dmbook/software/). However, the original notebooks are no longer maintained and were updated to use supported versions of Python and packages.

These are 7 Jupyter Notebooks used:

1. Data Exploration
2. Data Preprocessing
3. Regression
4. Classification
5. Text Processing
6. Cluster Analysis
7. Anomaly Detection

The first code block of each notebook installs required packages for that notebook. Restart the kernel after installing the packages for the new packages to be recognized.

Otherwise, packages required for all packages can be installed all at once using requirements.txt.
<br/>`pip install -r requirements.txt`
