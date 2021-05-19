# BSAN6070 Machine_learning
Name: Bryan Lihardinata

**PROJECT: DecisionTree Classifier**

## Instruction:
- colab.research.google.com/
- Under GitHub tab, please write the following: blihardinata/CA03_DecisionTree

### Import Packages:
*import Panda, Numpy, Matplotlib, DecisionTreeClassifier*

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

### Step 4: Evaluate the performance with sklearn 
- Use Sklearn to calculate accuracy, precision, recall and f1 score
- Sklearn has a function to build confusion matrix. However, the function returns an array instead of a dataframe. Hence, crosstab is used
- AUC curve = Area under the curve that is used to summarize the performance of a classifier over all possible thresholds

### **Step 5: Tune Decision perfomance**
- Check the accuracy, precision, recall, and F1 score with either entropy or gini criterion
- Minimum sample split, minimum sample leaf and max depth are the three hyperparameters that we need to analyze based on the given criteria
- Another decision tree is made based on the best tree among 8 different selections, excluding the original tree.

### **Step 6: Automate Decision Tree** 
- The excel file that is provided for the project is to be uploaded with no accuracy, recall, precision and f1 score 
- iterrow function is used to read the excel file row by row
- Since the determinant of the outcome is based on either gini or entropy, "if" function is utilized. 

### **Step 7: Automate Decision Tree** 
- As values in each column have been encoded, the new variables are matched with the label using our trained model. 
- Hence, the prediction model shows that the new person has an income level above $50k. 
- Based on the prediction probability, the chances that the new person will have income above 50k is 71.60%

