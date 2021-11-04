# TemplateProject
A template of the project with procedure to initialize a new data science project.

## Table of Contents
# Table of contents
1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Maintenance](#maintenance)
4. [Execution](#execution)


## Introduction <a name="introduction"></a>
The following procedure provides guidelines that I have chosen in order to realize my projects. The Jupyter’s next-generation notebook interface, [JupyterLab](https://jupyter.org/) is used. 


## Installation <a name="installation"></a>
To install a new clean environment, run the following commands. For specific package installations, [conda](https://docs.conda.io/en/latest/) is preferred to [pip](https://pypi.org/project/pip/) environment manager but pip is used in case the package is not available with conda.

To initialize a project environment using the ```requirements.txt``` file, run:
```
conda create -n test-env
conda activate test-env
conda install --force-reinstall -y -q -c conda-forge --file requirements.txt
```


## Maintenance <a name="maintenance"></a>

```
conda update -c conda-forge --all
conda list -e > requirements.txt
```


## Execution <a name="execution"></a>

```
jupyter-lab
```
