# Artificial-Intelligence-Applications

Practicing Deep Learning in Python applied in the real world.

# Introduction

Deep learning is a subset of machine learning in artificial intelligence (AI) that has networks capable of learning unsupervised from data that is unstructured or unlabeled. Also known as deep neural learning or deep neural network

This website intends to present the work analysis for the *"Análise Econômica e Geração de Valor"* class assignment.

:octocat: Alternatively, run a binder container: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ldaniel/Artificial-Intelligence-Applications/master)

## Professor
- Bernardo Aflalo

## Authors / Students
|Profile|Name|E-mail|
|---|---|---|
|<a href="https://github.com/DanielFCampos"><img src="https://avatars2.githubusercontent.com/u/31582602?s=460&v=4" title="DanielFCampos" width="80" height="80"></a>|Daniel Campos|[(daniel.ferraz.campos@gmail.com)](daniel.ferraz.campos@gmail.com)|
|<a href="https://github.com/ldaniel"><img src="https://avatars2.githubusercontent.com/u/205534?s=460&v=4" title="ldaniel" width="80" height="80"></a>|Leandro Daniel|[(contato@leandrodaniel.com)](contato@leandrodaniel.com)|
|<a href="https://github.com/ricardobreis"><img src="https://avatars2.githubusercontent.com/u/4885152?s=64&v=4" title="ricardobreis" width="80" height="80"></a>|Ricardo Reis|[(ricardo.l.b.reis@gmail.com)](ricardo.l.b.reis@gmail.com)|
|<a href="https://github.com/RodriGonca"><img src="https://avatars2.githubusercontent.com/u/50252438?s=460&v=4" title="RodriGonca" width="80" height="80"></a>|Rodrigo Goncalves|[(rodrigo.goncalves@me.com)](rodrigo.goncalves@me.com)|
|<a href="https://github.com/ygorlima1"><img src="https://avatars2.githubusercontent.com/u/52429828?s=460&v=4" title="ygorlima1" width="80" height="80"></a>|Ygor Lima|[(ygor_redesocial@hotmail.com)](ygor_redesocial@hotmail.com)|

# Project Organization
------------

    ├── LICENSE
    ├── Makefile              <- Makefile with commands like `make data` or `make train`
    ├── README.md             <- The top-level README for developers using this project.
    ├── data
    │   ├── external          <- Data from third party sources.
    │   ├── interim           <- Intermediate data that has been transformed.
    │   ├── processed         <- The final, canonical data sets for modeling.
    │   └── raw               <- The original, immutable data dump.
    │
    ├── docs                  <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models                <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks             <- Jupyter notebooks. 
    │   └── external_examples <- Other interesting notebooks
    │   │
    │   └── fgv_assignment    <- The final class assignment given by Professor Mirapalheta
    │   │
    │   └── fgv_classes       <- All notebooks given by Professor Mirapalheta and Professor Hithoshi
    │                            in theirs respective classes
    │                            
    ├── references            <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports               <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures           <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt      <- The requirements file for reproducing the analysis environment, e.g.
    │                            generated with `pip freeze > requirements.txt`
    │
    ├── setup.py              <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                   <- Source code for use in this project.
    │   ├── __init__.py       <- Makes src a Python module
    │   │
    │   ├── data              <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── exercises         <- Scripts for FGV's class assignments
    │   │   └── __init__.py    
    │   │   └── playground.py
    │   │
    │   ├── features          <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models            <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization     <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini               <- tox file with settings for running tox; see tox.testrun.org


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
