# ConTech2025 - What shapes prices in Airbnb?

## Repository 

This repository contains the code that was used to prepare the presentation/session  
**"What shapes prices in Airbnb?"** during the ConTech2025 conference (3rd-4th November 2025)

*.py files are Python files to run in a standard way.  
*.ipynb files are Jupyter notebooks for running in Colab, OCI DataScience or on-premises Jupyter notebooks installation. 
The presentation is in PowerPoint format.

## Code

automl/requirements.txt - required libraries to run examples
        (install with your Python Environment tool, I've used virtualenv)
airbnb_ShallowTuner_BayesianOptimization_*.py - Select Shallow Model - Random Forest vs SVM, Use BayesianOptimization strategy <br>
    Berlin - automl/airbnb_ShallowTuner_BayesianOptimization_berlin.py <br>
    Munich - automl/airbnb_ShallowTuner_BayesianOptimization_munich.py <br>
    Prague - automl/airbnb_ShallowTuner_BayesianOptimization_prague.py <br>
airbnb_ShallowTuner_*.py -  Select Shallow Model - Random Forest vs SVM, Use RandomSearch strategy <br>
    Berlin - automl/airbnb_ShallowTuner_berlin.py <br>
    Munich - automl/airbnb_ShallowTuner_munich.py <br>
    Prague - automl/airbnb_ShallowTuner_prague.py <br>
MLP-Structured-Data-Regression.py - MLP and how we could treat exact architecture as hyperparameter <br>
airbnb_*_automl_taskapi.py- How to deal with AutoML Functional API <br>
    Berlin - automl/airbnb_berlin_automl_taskapi.py <br>
    Munich - automl/airbnb_munich_automl_taskapi.py <br>
    Prague - automl/airbnb_prague_automl_taskapi.py <br>
Interpretable ML <br>
    Berlin - notebooks/airbnb_explainable_AI_shap_berlin.ipynb <br>
Using LASSO regularization on Airbnb data <br>
    notebook/What_shapes_AirBnb_prices.ipynb
