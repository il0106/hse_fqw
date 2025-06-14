![image](https://github.com/user-attachments/assets/a3ba287a-b92c-4c3e-8d7e-28cfca6fa15f)
# Master's Thesis: Session-Based Fraud Detection Using Machine Learning
#### Ilya Starkov | Final Qualification Work 
#### National Research University Higher School of Economics | MDS. Fall 2023 | 2025

## About
The repository was created for the Master's thesis. It includes the initial data, processed intermediate data, as well as scripts for reproducing the results of the work.

## Structure
* **data** - folder consists all available data for the thesis.
  * 'dataset.parquet' - initial raw data.
  * 'dataset_after_eda.parquet' - dataset after EDA with some added and deleted columns
* **eda.ipynb** - EDA, processing initial dataset and saving results.
* **feature_selection.ipynb** - feature filtration via correlation, back elimination, add-del, and permutation importance.
* **tuning.ipynb** - hyperparameter tuning.
* **testing** - script with final model test.
