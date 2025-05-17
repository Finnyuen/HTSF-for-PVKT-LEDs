# GreenPVKTLED
The open-source code modularizes the automated sample descriptor writing functionality,data sample statistics and sampling division,data preprocessing, model training, model cross-validation,
model performance evaluation, and high-throughput screening processes for predicting unknown samples.  It comprises five modules in total, as reflected in the program names. 
 The implementation achieves a high degree of automation and maintains broad compatibility with mainstream development environments.  
For code reproduction: Since the code automatically saves critical data from each module and output figures. users can sequentially execute the modules from 1 to 5. 
Collected samples data, intermediate processed data, and training results are stored under the **data** directory, while key output figures from each module are saved under the **output_figures** directory.

The required Python version and related dependencies are listed below:

Python                            3.11.4

Package                           Version
pandas                            2.2.2
numpy                             1.26.2
jupyter                           1.0.0
rdkit                             2023.9.4
scikit-learn                      1.5.1
xgboost                           2.1.1
catboost                          1.2.7
scipy                             1.14.0
shap                              0.43.0
seaborn                           0.13.0
wheel                             0.42.0
matplotlib                        3.9.2
# PVKT-LEDs-HTS-Screening
