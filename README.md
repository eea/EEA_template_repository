
EEA template repository
==============================


Getting started
-------------------------------------------------------------------------------------------

### location on CWS
folder_for_EEA_template_repository = 'C:\Users\"user-name"\projects\'

### How to clone



Directory layout
-------------------------------------------------------------------------------------------

    ├── data               <- sample data. Note: all data is stored in an S3 bucket
    │
    ├── notebooks          <- Jupyter notebooks
    │   ├── demo           <- notebooks to show how to use the software developed in this repository
    │   └── dev            <- work-in-progress notebooks for testing and developing
    │
    ├── processing         <- tools for data processing. Mainly Python scripts
    │
    ├── post-processing    <-  tools for data post-processing. Can include Python scripts, CLI instructions etc.
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   ├── utils.py       <- Collection of common functions used in notebooks
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io

--------
