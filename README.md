# Credit-Card-Fraud-Detection
**For this dataset you can find on kaggle and other sources**
Check whether the Credit transaction is fake or not

STEP 1: First Import all required lib as:

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import matplotlib_inline
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.pipeline import Pipeline
from sklearn.linear_model import LogisticRegression
from sklearn.neighbors import KNeighborsClassifier
from sklearn.tree import DecisionTreeClassifier
from sklearn.ensemble import RandomForestClassifier
from sklearn.svm import SVC
from sklearn import metrics

STEP 2: Read the dataset using pandas and do Data_processing Task and also check is your dataset need any preprocessing such label_enconding,Scaling ,Normalization
Go through all columns and data if any data is missing first try to handel it and do
some basics task to get aquinted with the data set such which is independent data and which is dependent data

STEP 3: Go for data visulization using seaborn and matplot lib 
plot graph to understand the relation betn Independent field and Dependent field

STEP 4 :Split your data into traning set and testing set 

STEP 5 :Go for model creation

STEP 6 :Chcek the accuracy of model and comapare through diff algorithms and pick the best one.
