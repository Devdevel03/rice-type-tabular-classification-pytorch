#Rice Type Classification (Tabular, PyTorch)
A compact tabular classification project predicting rice grain types from the Kaggle “Rice Type Classification” dataset, built with a clean PyTorch baseline and scikit-learn utilities. It includes data loading, basic preprocessing, a train/validation split, and accuracy evaluation with optional CUDA.

#Highlights
Multilayer perceptron (MLP) baseline for tabular classification with minimal, readable code.

GPU auto-detection (CUDA) for faster training when available.

Clear metric reporting (accuracy) suitable for quick experiments and benchmarking.

#Dataset
Kaggle “Rice Type Classification” with features including Area, MajorAxisLength, MinorAxisLength, Eccentricity, ConvexArea, EquivDiameter, Extent, Perimeter, Roundness, AspectRation, and the target Class. Data is accessed via opendatasets or a local CSV.

#File
TableDataTrain.ipynb — single notebook containing data prep, model, training, and evaluation.

#Tech
PyTorch, scikit-learn, pandas, matplotlib, opendatasets; CPU/GPU (CUDA) compatible.

#Notes
Designed as a straightforward baseline for tabular deep learning, easy to extend with normalization, confusion matrix, and hyperparameter tuning
