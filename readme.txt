# For executing the jupyter notebook click 'Run All Cells' and the entire notebook will be executed. All the cells have been already run and outputs are properly visible.

# The libraries required for 'Vehicle Coupon reco.ipynb' are:
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
!pip install plotly
import plotly.express as px
import warnings
warnings.filterwarnings('ignore')
from sklearn.preprocessing import OneHotEncoder
from sklearn.linear_model import LogisticRegression
from sklearn.ensemble import RandomForestClassifier
from sklearn.model_selection import train_test_split, GridSearchCV

