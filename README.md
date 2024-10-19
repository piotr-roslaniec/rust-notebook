# rust-notebook

A template repository for Jupyter notebooks with a Rust kernel.

This repo uses [`evcr`](https://github.com/evcxr/evcxr) to evaluate Rust in Jupyter notebooks.

## Installation

For installing Python 3.10, we suggest using [pyenv](https://github.com/pyenv/pyenv#getting-pyenv).

We also use [pipenv](https://pipenv.pypa.io/en/latest/installation.html) to easily manage dependencies.

Then, follow installation instructions for [`evcxr_jupyter`](https://github.com/evcxr/evcxr/tree/main/evcxr_jupyter).

```bash
pipenv shell --python3.10
pipenv install --dev
```

## Usage

```bash
pipenv shell
pipenv run jupyter notebook
```
