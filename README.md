# ML Practice Workbooks

**What is this repository about?**
There are several python notebooks and codes which are part of this folder. These are just some simple practice problems attempted by me including **linear regression, logistic regression, and EDA on some datasets.** The codes dont follow best practices (are not commented properly, have hard coded variables everywhere etc.). Apologies, it is messy.

For running the code, you may follow the below steps:
1. Run VSCode (or any other code editor) from Anaconda Command Prompt
2. Make sure you are using a dedicated virtual environment and activate it,
sample - 
 '''code
conda create -n myenv python=3.7.3
'''
3. Install or upgrade all packages from requirements.txt
conda install --file requirements.txt
or pip install -r requirements.txt
You may need to add the full path of requirements.txt file depending on your pwd

4. You would have to change all data paths accordingly.

**Important links:**
1. Conda environment - https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html
2. https://wiki.epfl.ch/help-git-en/how-can-i-import-an-existing-folder-into-my-repository

### Folders & Code Description -
#### data - This folder contains all data files for the different workbooks & codes
#### Notebooks

1. Bank Defaulter Prediction contains Bank_Term.ipynb which implements logistic regression
2. Hospital Profiling contains two notebooks which does EDA of hospital data (Data unavailable)
3. Spam Identification contains Email_Spam.ipynb which focuses on EDA of email data
5. House Prices module contains Predicting_house_prices.ipynb which implents linear regression