# Jupyter Notebooks
We will run tutorials as Jupyter notebooks. There are two ways to do that: locally on your laptop or on Google Colab. You can choose either. To run the notebooks locally, it is strongly recommended to set up a Python virtual environment (see instructions below). To use the tutorials on Google Colab (https://colab.research.google.com/), you will need to have a Google account, but there is no need in any additional installations (when there is, it can be done on the fly).

# Python Virtual Environment

 
Virtual environments (venvs) in Python serve as sandboxes for individual projects. Python libraries/packages from separate venvs do not interact with each other. In other words, what happens in a venv stays in the venv. It is almost always a good idea to create a venv for a new project. 

We will work with Python 3. It is assumed to have been installed on your computer. Installation intructions for a virtual environment follow.

## Linux/Mac

1. To create a venv:
```
python3 -m venv /path/to/new/virtual/environment
```
For example, if we want to create a venv called *mcmc* in the current location,
```
python3 -m venv mcmc
```
2. To activate the venv:
```
source /path/to/new/virtual/environment/bin/activate
```
To activate the venv from our previous example,
```
source mcmc/bin/activate
```
When the venv is activated, its name appears in the beginning of the command line:
```
(mcmc) student@class:
```
3. To install packages,
```
pip install --upgrade pip
pip install --upgrade setuptools
pip install numpy scipy matplotlib jupyter
```
   - Any additional packages can be installed by using `pip install` followed by the name of a package.
4. To launch a jupyter notebook,
```
jupyter-notebook
```
5. To deactivate the venv,
```
deactivate
```

## Windows

1. To create a venv:
```
python -m venv C:\path\to\new\virtual\environment
```
For example, if we want to create a venv called *mcmc* in the current location,
```
python -m venv mcmc
```
2. To activate the venv:
```
C:\path\to\new\virtual\environment\Scripts\activate
```
To activate the venv from our previous example,
```
mcmc\Scripts\activate
```
When the venv is activated, its name appears in the beginning of the command line:
```
(mcmc) C:\>
```
3. To install packages,
```
python -m pip install --upgrade pip
python -m pip install numpy scipy matplotlib jupyter
```
   - Any additional packages can be installed by using `python -m pip install` followed by the name of a package.
4. To launch a jupyter notebook,
```
jupyter notebook
```
If that doesn't work, try
```
python -m notebook
```
5. To deactivate the venv,
```
deactivate
```

  
