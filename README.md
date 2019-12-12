# DSSP 14

## Curriculum

This lecture is focused on the following concepts:

1. Introduction the Python programming language;
2. Data wrangling using Pandas;
3. Applied mathematics using NumPy;
4. Understand linear models;
5. Understand tree-based algorithms;
6. Manage mixed data types in machine-learning pipeline;
7. Fine tuning model by hyper-parameters search.

## Additional material:

Some intro slides: http://ogrisel.github.io/decks/2017_intro_sklearn

## Getting started

In case that you have any issues, you click on the binder link below
which will setup an online machine for you:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/glemaitre/dssp_12_2019/master)


Alternatively you can create a new conda environment which will be called
`dssp` by default and whill contain all the packages required to run the
notebooks:

``` bash
conda env create -f environment.yml
conda activate dssp
```

```bash
cd path/to/dssp_12_2019
jupyter notebook
```

You can also update an existing `conda` environment:


``` bash
conda env update -f environment.yml
```

## References

This material is inspired and reused part of the following materials:

* https://github.com/amueller/scipy-2018-sklearn
* https://github.com/lesteve/euroscipy-2019-scikit-learn-tutorial
