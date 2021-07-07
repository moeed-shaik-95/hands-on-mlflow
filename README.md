# Managing the end-to-end machine learning lifecycle with MLFlow


# How to setup?

## Setup the environment
- clone this repository
- **with conda**
  - create a new environment: `conda env create -f conda.yml`
  - activate the environment: `conda activate mlflow_tutorial`

## The notebook
- Get the `hands_on_example.ipynb`
- run `jupyter notebook`


## The `train.py` file
- run `python train.py`

## To start the mlflow-ui
- run `mlflow server --backend-store-uri mlruns/ --default-artifact-root mlruns/ --host 0.0.0.0 --port 5000`