# Brandenburg Dataset: Model Zoo

This repository accompanies the [Brandenburg Dataset](https://github.com/obrookes/brandenburg-dataset) repository, it is a work-in-progress offshoot of [The Pan-African Models](https://github.com/obrookes/panaf-models) repository. 
This repository contains the codebase to train and evaluate several deep learning models on the Pan-African Dataset, which been adapted (in part) for use with the Brandenburg dataset. 

*NOTE* To date, the supervised triplet loss models are currently the only tested model-set on the Brandenburg data. 

## Data sorting

The [Brandenburg Tracking](https://github.com/rob64j/brandenburg-tracking) repository is intended for pre-processing the raw Brandenburg data in terms of generating tracklets, and sorting the data into train/validation/test groups based on user defined proportions.

## Setup

A conda environment file is provided which can be used to build the necessary environment. 
```bash
conda env create --name $NAME -f conda-environment.yaml
```
The Brandenburg Dataset package will also need to be installed into the new environment (-e if planning to use in development).
```bash
pip install -e $PATH_TO_BRANDENBURG_DATASET
```


