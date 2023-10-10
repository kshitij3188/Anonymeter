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

If you experience issues with the installation, we recommend to install
`anonymeter` in a new clean virtual environment.

## Getting started

Check out the example notebook in the `notebooks` folder to start playing around
with `anonymeter`. To run this notebook you would need `jupyter` and some plotting libraries.
This should be installed as part of the `notebooks` dependencies.

## Cite this work

"A Unified Framework for Quantifying Privacy Risk in Synthetic Data", M. Giomi *et al*, PoPETS 2023.
This `bibtex` entry can be used to refer to the paper:

```text
@misc{anonymeter,
  doi = {https://doi.org/10.56553/popets-2023-0055},
  url = {https://petsymposium.org/popets/2023/popets-2023-0055.php},
  journal = {Proceedings of Privacy Enhancing Technologies Symposium},
  year = {2023},
  author = {Giomi, Matteo and Boenisch, Franziska and Wehmeyer, Christoph and Tasnádi, Borbála},
  title = {A Unified Framework for Quantifying Privacy Risk in Synthetic Data},
}
```
