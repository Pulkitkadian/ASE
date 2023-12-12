## Replication
- [models](/models) directory should contain all the trained ML models on five folds (both on data with and without pre-processing) of the [Dronology Dataset](http://sarec.nd.edu/dronology/datasets/01/). The instructions to download the models are in the following section.
- [dronology.csv](/dronology.csv) contains the original Dronology dataset in CSV format. IDs starting with `RE` are considered requirements and all other entries are considered as non-requirements.
- [data](/data) contains the generated stratified five folds from the original Dronology dataset, both with and without pre-processing. These folds are used for cross-validation of all the pipelines.

## How to run?
1. Clone the repository
2. Create a virtual environment with Python `3.8.10` and install the `requirements.txt` using `pip install -r requirements.txt`
3. Run the Jupyter Notebook `RorNot_Pipelines.ipynb`
