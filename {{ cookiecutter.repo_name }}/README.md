{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── configs            <- Config files
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── users              <- Working directroty for each worker
    │                         Under this directory, you can work freely and no review is done.
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
    ├── {{ cookiecutter.project_name.lower().replace(' ', '_') }}                <- Source code for use in this project.
    │    ├── __init__.py    <- Makes src a Python module
    │    │
    │    ├── data           <- Scripts to download or generate data
    │    │   └── make_dataset.py
    │    │
    │    ├── features       <- Scripts to turn raw data into features for modeling
    │    │   └── build_features.py
    │    │
    │    ├── models         <- Scripts to train models and then use trained models to make
    │    │   │                 predictions
    │    │   ├── predict_model.py
    │    │   └── train_model.py
    │    │
    │    └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │        └── visualize.py
    └── tox.ini             <- tox file with settings for running tox; see tox.readthedocs.io

--------

How to Build
------------

    pip install -r requirements.txt


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
