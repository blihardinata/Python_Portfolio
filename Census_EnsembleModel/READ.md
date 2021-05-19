# BSAN6070 Machine_learning
Name: Bryan Lihardinata

**PROJECT: Ensemble Model**

## Instruction:
- colab.research.google.com/
- Under GitHub tab, please write the following: blihardinata/CA04_Ensemble_model

### Import Packages:
*import Panda, Numpy, Matplotlib, DecisionTreeClassifier*
from sklearn.tree import DecisionTreeClassifier
from sklearn.ensemble import RandomForestClassifier, AdaBoostClassifier, GradientBoostingClassifier
from sklearn.metrics import accuracy_score, roc_auc_score, auc

### Step 1: Check the overall dataset. 
- Check if there is any missing value with df.count and df.isnull
- Rename all the columns as needed to improve readability

### Step 2: Display a stack bar representing the income level VS. one of each 7 variables. Hence, there are 7 stacked bars to be displayed. 
- Build a pivot table with 0 and 1 as columns and variables as rows
- fill the pivot table with ratio (over 100)

### Step 3: Build the decision tree classifier 
- Split the dataset into train and test as specified under "flag" column
- Use label encoder to label all the values and drop the columns with no encoded values. 
- Build the prediction with decision tree classifier and visualize that decision tree

### Step 4: Find the optimal value with key performance parameter
- Use Decision Tree Classifier. Set the max depth from 2 to 20 with an increment of 2 value per round
- Use Random Forest classfier. Set the range from 50 to 500 with an increment of 50 value per round
- Use Adaboost classfier. Set the range from 50 to 500 with an increment of 50 value per round
- Use Gradient Boost classfier. Set the range from 50 to 500 with an increment of 50 value per round
- Use XGB classfier. Set the range from 50 to 500 with an increment of 50 value per round

### **Step 5: Compare Performance for the above models, except Decision Tree Classfier** 
- Set up a new dataframe with accuracy and AUC columns to compare performance. 
- N_estimator is set 100 for all models
