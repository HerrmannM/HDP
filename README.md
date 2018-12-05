# MonashMLHDP
Accurate estimation of conditional categorical probability distributions using Hierarchical Dirichlet Processes 

This package offers an accurate parameter estimation technique for Bayesian Network classifiers. It uses a Hierarchical Dirichlet Process to estimate the parameters (using a collapsed Gibbs sampler). Note that the package is built in a generic way such that it can estimate any conditional probability distributions over categorical variables.

More information available at http://www.francois-petitjean.com/Research/

## Underlying research and scientific paper

This code is supporting [our paper in Machine Learning](https://doi.org/10.1007/s10994-018-5718-0) entitled "Accurate parameter estimation for Bayesian Network Classifiers using Hierarchical Dirichlet Processes". 

The paper is also available on [arXiv](https://arxiv.org/pdf/1708.07581).

When using this repository, please cite:

```
@ARTICLE{Petitjean2018-HDP,
  author = {Petitjean, Francois and Buntine, Wray and Webb, Geoffrey I. and Zaidi, Nayyar},
  title = {Accurate parameter estimation for Bayesian Network Classifiers using Hierarchical Dirichlet Processes},
  journal={Machine Learning},
  year={2018},
  volume={107},
  number={8},
  pages={1303--1331},
  year = 2018
  url = {https://doi.org/10.1007/s10994-018-5718-0}
}
```
