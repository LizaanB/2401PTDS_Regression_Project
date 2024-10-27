# 2401PTDS_Regression_Project

## Tabel of contents 

## 1.Project overview

The aim is to analyse and predict average temperature from the agri-food sector, using data from the FAO and IPCC, to understand climate impacts and develop sustainable strategies for stakeholders including policymakers and agricultural businesses.

## 2. Dataset 

By the end of this project, you will have a thorough understanding of the impact of agricultural activities on CO2 emissions and climate change. Your findings and recommendations will contribute to the ongoing efforts to promote sustainability within the agri-food sector, providing valuable insights for the stakeholders involved in this initiative.



## 3. Packages 

To carry out all the objectives for this repo, the following necessary dependencies were loaded:

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import itertools
import random
import seaborn as sns
import matplotlib.cm as cm
import json
import pingouin as pg
import missingno as msno
import statsmodels.api as sm
import pmdarima as pm

from statsmodels.graphics.tsaplots import plot_acf, plot_pacf
from statsmodels.graphics.tsaplots import plot_predict
from statsmodels.tsa.statespace.tools import diff
from statsmodels.tsa.arima.model import ARIMA
from statsmodels.tsa.stattools import adfuller
from sklearn.metrics import mean_squared_error
from math import sqrt

import warnings
warnings.filterwarnings("ignore")
plt.rcParams["figure.figsize"] = (15,10)
## 4. Environment
It's highly recommended to use a virtual environment or Jupytor for your projects, there are many ways to do this; we've outlined one such method below. Make sure to regularly update this section. This way, anyone who clones your repository will know exactly what steps to follow to prepare the necessary environment. The instructions provided here should enable a person to clone your repo and quickly get started.

## Create the new evironment - you only need to do this once

# create the conda environment
conda create

# Exporting your conda environment
conda activate <env>
conda install pip
pip freeze > requirements.txt
pip list --format=freeze > requirements.txt

## This is how you activate the virtual environment in a terminal and install the project dependencies

# activate the virtual environment
conda activate <env>
# install the pip package
conda install pip
# install the requirements for this project
pip install -r requirements.txt



## 5. Contributors 

Name	Email
