For simplicity, the recommended environment is Google Colab. Nonetheless, the notebooks can also be run in other environments (e.g., Anaconda), or even as Python scripts.

## 1. Notebook(s) for case-study + algorithm

You will see a separate Jupyter notebook for each case-study (Train-ticket, or CoCoME) and algorithm (NSGAII, PESA2, or SPEA2). For example, [archmodels\_trainticket\_spea2.ipynb](https://github.com/SEALABQualityGroup/replication-package_2023_search_budgets/blob/main/notebooks/archmodels_trainticket_spea2.ipynb) corresponds to an experiment with the algorithm SPEA2 on the Train-ticket case-study. 

There is a total of 6 notebooks for these combinations.

The execution of one of these notebooks performs a series of (similar) processing steps for the different time budgets and baseline solutions.

All the necessary datasets should be loaded automatically by the notebooks.


## 2. Notebook for visualizations

The [tree_scripts.ipynb](https://github.com/SEALABQualityGroup/replication-package_2023_search_budgets/blob/main/notebooks/tree_scripts.ipynb) notebook provides a set of utility functions to render some paper figures, namely:

* Trees for refactoring sequences (captured in DOT format)
* Differences between a pair or trees
* Pareto fronts for different combinations of objectives (e.g., #changes, pas) and datasets (i.e., time budgets or baseline)
* Tables with frequency distributions for refactoring actions

All the necessary datasets should be loaded automatically by the notebook.

<!---
## Contact

In case you might have questions, you might write to <andres.diazpace@isistan.unicen.edu.ar>.
-->
