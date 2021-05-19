# BSAN6070 Machine_learning
Name: Bryan Lihardinata

**PROJECT: Ensemble Model**

## Instruction:
- colab.research.google.com/
- Under GitHub tab, please write the following: blihardinata/CA05_Logistic_Regression

### Import Initial Packages:
import Panda, Numpy, Matplotlib, Seaborn

import statsmodels.api as sm

import statsmodels.formula.api as smf

from sklearn.model_selection import train_test_split

from sklearn.metrics import accuracy_score

from sklearn.metrics import recall_score

from sklearn.metrics import confusion_matrix

from sklearn.metrics import precision_score

from sklearn.metrics import f1_score

from sklearn.metrics import roc_auc_score

from sklearn.metrics import auc

from sklearn.metrics import roc_curve

from sklearn.metrics import classification_report

### Step 1: Check the overall dataset. 
- Check if there is any missing value with df.count and df.isnull
- Check multi collinearity with correlation matrix and remove one variable (keep the other half) with correlation above 70% or below -70%
- Rename all the columns as needed to improve readability

### Step 3: Build binary classifier 
- Split the dataset into x (independent variables) and y (dependent variable)
- Use glm function to find the significant level of each variable in corresponding to the independent variable and remove variables with P.value above 5%
- Split the dataset into train and test with model selection

### Step 4: Find the best performance
- Adjust C value and see which of the C values has the highest accuracy score. 
- Use solver 'newton-cg' because the penalty is set at default

### Step 5: Display the feature importance based on coefficients
- Calculate the coefficient and sort in descending order

### Step 6: Evalue the performance model
- Calculate the confusion matrix, accuracy score, AUC and other classifiers

Additional Resources:
Additional reading:

Logistic Regression
-	https://realpython.com/logistic-regression-python/
-	Training the model with a variety of C: https://www.quora.com/Can-someone-introduce-a-tutorial-or-a-paper-on-how-to-choose-the-value-of-C-in-the-scikit-learn-logistic-regression-function
-	https://www.youtube.com/watch?v=zM4VZR0px8E&t=904s

GLM in R For python
https://stackoverflow.com/questions/53198033/glm-r-vs-python
https://www.youtube.com/watch?v=__oC5IRCFKI
 
Different type of GLM:
https://www.statsmodels.org/stable/regression.html

Visualization
-	https://medium.com/@szabo.bibor/how-to-create-a-seaborn-correlation-heatmap-in-python-834c0686b88e
-	https://seaborn.pydata.org/tutorial/color_palettes.html

Please feel free to reach out if you have any questions or issues with accessing or understanding any documents

Contact me via email at blihardi@lion.lmu.edu
