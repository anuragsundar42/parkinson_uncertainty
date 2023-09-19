# parkinson_uncertainty
## Title: Clinically useful eary detection of Parkinson's disease using uncertainty-aware techiniques with CNNs
This repository is dedicated to a Master Thesis project for developing an uncertainty-aware model for detection of Parkinson's disease.

## Data Source
The data is pulled from the following public github account of my thesis supervisor, Dr. Markus Wenzel: 'https://github.com/mtwenzel/parkinson-classification/raw/master/data/PPMI-classification.zip'. The data is 2D DatScan image of the brain. The image is of dimension (109, 91). There are total 1290 images. 645 images are the unique original images while the rest 645 are the smoothened version of the same.

## Structure of Project and Repository
There are total 6 different CNN methods with their uncertainty-aware technique used as follows:
1. Basic CNN (with no uncertainty aware techniques)(baseline model)(methods_models/Base_BAL_CNN.ipynb)
2. Temperature Scaling (methods_models/TEMP_Scale_BAL.ipynb)
3. Monte Carlo Dropout (methods_models/MC_BAL_Dropout_TEST.ipynb)
4. Spectral-normalised neural gaussian process (SNGP) (methods_models/SNGP_BALANCE_MODEL_TEST_PLOTS.ipynb)
5. Batch Normalisation model(3rd model in Deep Ensemble) (methods_models/DEEP_BAL_ENSEMBLE_UNCERTAINTY.ipynb)
6. Deep ensemble (consisting of an aggregate of 3 models) (methods_models/DEEP_BAL_ENSEMBLE_UNCERTAINTY.ipynb)

The "methods_models" folder contains the .ipynb files of the 6 different CNN methods with some results in their respective .ipynb files.

The "entropy_threshold_results" contains the .ipynb file with the final results on the entropy and threshold analysis. It also contains excel files with entropy values for each method.

The "thesis_and_slides" folder contains the final thesis and the presentation slides for the first and final colloquim for the project. For detailed information, go through the Thesis to have a better understanding of the problem as well as the proposed solutions.

NOTE: The code in the .ipynb files are just for displaying the outcome of this project. Although most of these .ipynb files may be executible, they have not been setup to run in a generalized platform and might have some missing data and references.

++++++++++++++++++++++++++++++++++++++++++++++++++++THANK YOU++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
