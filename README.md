# CUPCAKE-vs-MUFFIN
In this datasheet we will look at classifying the recipe of muffin and cupcake with SVM

Let us look at the dataset where we have our recipe. But first, we need to load the tools we are going to need to work on that dataset.

 Let us load the packages we are going to need to start this project

# Packages
import numpy as np
import pandas as pd
import seaborn as sns
from sklearn import svm

Now we need to load our visualization tool for the data

# visual your data
import matplotlib.pyplot as plt
%matplotlib inline

As we continue with this project, we can now upload the data set and see what is in it. I will upload it from my computer, but you will need to remember where you put yours.

# Loading the data
cupmuf = pd.read_excel('C:/Users/Delmafia91/Downloads/RecipesMuffinsCupcakes.xlsx')

Let us have a look at the data now. We are going to load only the first five columns

# Peek at data
cupmuf.head(5)


