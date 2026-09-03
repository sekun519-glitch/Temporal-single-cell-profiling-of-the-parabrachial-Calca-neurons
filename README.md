# Temporal-single-cell-profiling-of-the-parabrachial-Calca-neurons
Python codes for sequencing data analysis
Python environments
  1) Preprocessing
channels:
  - conda-forge
  - nvidia
  - pytorch
  - defaults
dependencies:
  - scanpy=1.11.5
  - anndata
  - scipy
  - leidenalg
  - matplotlib
  - pytorch-cpu
  - tqdm
  - python=3.11
  - numpy
  - igraph
  - pandas
  - jupyterlab


  2) Analysis
channels:
  - conda-forge
  - nvidia
  - pytorch
  - defaults
dependencies:
  - python=3.10
  - scanpy
  - anndata
  - optuna
  - hyperopt
  - tensorboard
  - tqdm
  - python-igraph
  - leidenalg
  - jupyterlab
  - ipywidgets
  - widgetsnbextension
  - ipykernel
  - numpy[version='>=1.24,<2.0']
  - scipy
  - pandas
  - scikit-learn
  - scikit-image
  - matplotlib
  - seaborn
  - matplotlib-venn
  - intel-openmp
  - mkl
  - numba
  - joblib
