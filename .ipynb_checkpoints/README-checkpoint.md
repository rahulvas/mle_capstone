# Google Analytics Capstone

Scikit-Learn (both base Scikit-Learn and sklearn via Sagemaker) was used extensively in this project, and in order to recreate the results, please load in the "feature models" to recreate the intermediate clusters that were used for the final model. 

How to reproduce model:

Load in data (can download from Kaggle and run through `code/trim_data`). Once data is trimmed, go through `code/capstone_project`. Once at the RFM-cluster stage, be sure to load in the models in the `feature_models` directory. The actual models used for Sagemaker and deployment are in the `source` directory.

Imported packages:
```python
pandas
matplotlib
numpy
seaborn
datetime
pickle
sklearn
os
scipy
boto3
sagemaker
```