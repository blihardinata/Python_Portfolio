# BSAN6070 Machine_learning
Name: Bryan Lihardinata

**PROJECT: kNN Recommender**

## Instruction:
- colab.research.google.com/
- Under GitHub tab, please write the following: blihardinata/CA06_kNN_Recommendation

### Import Initial Packages:
import Panda, Numpy, Matplotlib
from scipy.sparse import csr_matrix
from sklearn.neighbors import NearestNeighbors
from fuzzywuzzy import process


### Step 1: Check the overall dataset. 
- Check if there is any missing value with df.count and df.isnull
- Drop an unnecessary column
- Adding a new row of data

### Step 2: Separate data into two dataframe
- Split the dataset into movie name (index and movie name) and feature columns
- create sparse matrix

### Step 3: Set up the recommender system 
- Build the initial model.fit

### Step 4: Build and design the outcome of the recommender system

### Please read additional reading for all the reference materials

Please feel free to reach out if you have any questions or issues with accessing or understanding any documents

Contact me via email at blihardi@lion.lmu.edu

Additional Resources:
Additional Reading:

Sparse Matrix: https://machinelearningmastery.com/sparse-matrices-for-machine-learning/

YouTube explanation: https://www.youtube.com/watch?v=4Ws0oPH350U

SciKit Learn: https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html
