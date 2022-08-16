# master-thesis-FS

This repository was made for my thesis about feature selection in network-based intrusion detection systems.

**feature_selection.ipynb** contains all the cells where we execute our re-implementation of GA-LR and our filter-based algorithms.

**train_stage.ipynb** contains the code of the classification stage using the feature sets obtained through the aforementionned stage.

**geneticAlg.py** is a module of genetic algorithms for feature selection by Manuel Calzolari. We have modified several parts of it to reproduce the same algorithm as GA-LR from the paper by Khamassi et al.

## Installation
Python 3.10 was used for this experiment. The requirements can be installed using the following command: 

`pip install -r requirements.txt`