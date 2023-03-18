#### Replication package for the paper:

*Best performance and reliability for your time: budget-aware search-based optimization of software model refactoring*\
by J. Andres Diaz-Pace, Daniele Di Pompeo, and Michele Tucci

#### How to generate the tables and figures in the paper
Initialize the python execution environment:
```bash
git clone https://github.com/SEALABQualityGroup/replication-package_2023_search_budgets
cd replication-package_2023_search_budgets
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Generate tables and figures:
```bash
python HV_table_and_timeline.py
python time_and_algo_comparison.py
python superpareto_scatter.py
```

#### Experiments

The experiments in the paper were performed using [EASIER](http://sealabtools.di.univaq.it/EASIER/), which is available in a different repository:

[https://github.com/SEALABQualityGroup/EASIER](https://github.com/SEALABQualityGroup/EASIER)

The data gathered during such experiments is provided here, in the [data](data) folder.
