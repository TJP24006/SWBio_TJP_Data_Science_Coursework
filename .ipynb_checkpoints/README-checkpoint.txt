# On_Off-Tissue_model

On_Off-Tissue_model is a simple python code to generate a classification model of LESA-MSI data into On- or Off-Tissue with a KNN algorithm. 

# Requirements 

Python 3.7 or higher (to install required packages) 

# Provided data 

Dataset included under /data folder. Dataset should be named LESAPeakArea.csv and contain 766 samples, and 7 column headings. As part of the code a second cleaned dataset with be outputted named cleaned_LESAPeakdata.csv. Please ensure data folder containing LESAPeakArea.csv is in your working directory, or the code will not run.

# Usage 

1. Download entire github folder including data folder containing LESAPeakArea.csv into a single directory 

2. Run the 'Install Packages' code in On_Off-Tissue_model.ipynb first installing required packages from pandas and sklearn. 

3. Import the data from the dataset, and run data cleaning code. When cleaned_LESAPeakdata.csv is outputted, double check that no 'NaN' values are present. 

4. If using own data, make sure peak areas the following peak areas are recorded: Desmosterol, Desmosterol-D6, Cholesterol, Cholesterol-D7, 24S-hydroxycholesterol and 24R/S-hydroxycholesterol-D7. Also ensure own data is in the data folder is in the same directory as n_Off-Tissue_model.ipynb. 

5. Run the rest of the pipeline to construct model based off KNN algorithm, and evaluate model performance with final 'Model evaluation' secton.

# Contribution and Comments

Please feel free to send any comments or contributions to the publisher