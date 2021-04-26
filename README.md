# Starbucks-Capstone-Project

This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

Not all users receive the same offer, and that is the challenge to solve with this data set.
blog post: https://medium.com/@abelhad.soukaina/starbucks-capstone-challenge-f35a7faa358a?sk=6bdaa1d1aba9ac4c0e92612cf318f2c1

 # libraries used
 
import pandas as pd

import numpy as np

import json

from datetime import datetime

from time import time

import matplotlib.pyplot as plt

import seaborn as sns

import warnings

warnings.filterwarnings("ignore")

from sklearn.metrics import accuracy_score,f1_score

from sklearn.model_selection import train_test_split

from sklearn.svm import SVC

# Motivation

I've chosen Starbucks data that mimics customer behavior on the Starbucks rewards mobile app, 
and build a model to predict the preferred offer by the clients 

# Files
Starbucks_Capstone_notebook.ipynb: the code notebook 
Starbucks_Capstone_notebook.html : the HTML version of the notebook


https://medium.com/@abelhad.soukaina/starbucks-capstone-challenge-f35a7faa358a?sk=6bdaa1d1aba9ac4c0e92612cf318f2c1
