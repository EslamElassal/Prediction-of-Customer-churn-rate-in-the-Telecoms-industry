# A Prediction of Customer churn rate in the Telecoms industry.

This assigmnent is Home-Work of Fundamentals-Applied Data Sci to create many models to predict Customer churn rate in the Telecoms industry and determine the associations between items purchased from the departments of a store.
## Dataset
### Part A: Classification
Customer churn rate is an important performance metric in the Telecoms industry due to the highly competitive markets. The churn rate enables companies to understand why their customers are leaving. You are hereby provided with the churn dataset containing randomly collected data from a telecom company’s database.
#### Part B: association rules
A store is interested in determining the associations between items purchased from its Departments. The store chose to conduct a market basket analysis of specific items purchased to analyze customer’s buying behavior.

##  Questions that are helped to achieve This goal:
### Part A: Classification
1. Generate a scatterplot matrix to show the relationships between the variables and a heatmap to determine correlated attributes 
2. Ensure data is in the correct format for downstream processes (e.g., remove redundant information, convert categorical to numerical values, address missing values, etc.) 
3. Split the dataset into 80 training/20 test set and fit a decision tree to the training data. Plot the tree, and interpret the results. 4. Try different ways to improve the decision tree algorithm (e.g., use different splitting strategies, prune tree after splitting). Does pruning the tree improves the accuracy? 
5. Classify the data using the XGBoost model with nrounds = 70 and max depth = 3. Evaluate the performance. Is there any sign of overfitting?
6. Train a deep neural network using Keras with 3 dense layers. Try changing the activation function or dropout rate. What effects does any of these have on the result?
7. Compare the performance of the models in terms of the following criteria: precision, recall, accuracy, F-measure. Identify the model that performed best and worst according to each criterion.
8. Use a ROC graph to compare the performance of the DT, XGboost & DNN techniques.
#### Part B: association rules
a) Generate a plot of the top 10 transactions\
b) Generate association rules using minimum support of 0.002, minimum confidence of 0.20, and maximum length of 3. Display the rules, sorted by descending lift value.\
c) Select the rule from QII-b with the greatest lift. Compare this rule with the highest lift rule for maximum length of 2.\
i) Which rule has the better lift? Which rule has the greater support?\
ii) If you were a marketing manager, and could fund only one of these rules, which would it be, and why?
## Solutions
### Part A: Classification
1.\
![alt text](Images_Solutiuon(FADS)/assP1_1_1.jpg)\
![alt text](Images_Solutiuon(FADS)/assP1_1_2.jpg)\
![alt text](Images_Solutiuon(FADS)/assP1_1_3.jpg)\
2.\
![alt text](Images_Solutiuon(FADS)/assP1_2_1.jpg)\
![alt text](Images_Solutiuon(FADS)/assP1_2_2.jpg)\
![alt text](Images_Solutiuon(FADS)/assP1_2_3.jpg)\
![alt text](Images_Solutiuon(FADS)/assP1_2_4.jpg)\
3.\
![alt text](Images_Solutiuon(FADS)/assP1_3_1.jpg)\
![alt text](Images_Solutiuon(FADS)/assP1_3_2.jpg)\
4.\
![alt text](Images_Solutiuon(FADS)/assP1_4_1.jpg)\
![alt text](Images_Solutiuon(FADS)/assP1_4_2.jpg)\
![alt text](Images_Solutiuon(FADS)/assP1_4_3.jpg)\
5.\
![alt text](Images_Solutiuon(FADS)/assP1_5_1.jpg)\
6.\
![alt text](Images_Solutiuon(FADS)/assP1_6.jpg)\
7.\
![alt text](Images_Solutiuon(FADS)/assP1_7.jpg)\
8.\
![alt text](Images_Solutiuon(FADS)/assP1_8.jpg)

#### Part B: association rules
A)\
![alt text](Images_Solutiuon(FADS)/assP2_1.jpg)\
B)\
![alt text](Images_Solutiuon(FADS)/assP2_2.jpg)\
C)\
i)\
![alt text](Images_Solutiuon(FADS)/assP2_3_1.jpg)\
ii)\
![alt text](Images_Solutiuon(FADS)/assP2_3_2.jpg)