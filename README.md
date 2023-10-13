# Investigating: Anonymeter

## Setup and installation

`Anonymeter` requires Python 3.8.x, 3.9.x or 3.10.x installed. The simplest way to install `Anonymeter` is from `PyPi`. Simply run

```
pip install anonymeter
```

### Local installation

To install `Anonymeter` locally, clone the repository:

```shell
git clone https://github.com/kshitij3188/Anonymeter.git anonymeter
```

and install the dependencies:

```shell
cd anonymeter  # if you are not there already
pip install . # Basic dependencies
pip install ".[notebooks]" # Dependencies to run example notebooks
pip install -e ".[notebooks,dev]" # Development setup
```

## Getting started

To initiate the execution of commands for two distinct datasets, namely [Bank Marketing](https://archive.ics.uci.edu/dataset/222/bank+marketing) and [Student Performance](https://archive.ics.uci.edu/dataset/320/student+performance), please refer to the example notebook located in the `notebooks` directory. To run this notebook you would need `jupyter` and some plotting libraries.
This should be installed as part of the `notebooks` dependencies.
