Mobile Price Classification
a.Problem Statement : The objective of this project is to develop a machine learning–based classification system that predicts the price range of a mobile phone based on its technical specifications. Given various features such as battery power, RAM, internal memory, screen size, camera resolution, and connectivity options, the task is to classify each mobile phone into one of four price categories:
Low, Medium, High, or Very High. This is a multi-class classification problem, where the goal is to build, evaluate, and compare multiple machine learning models to identify the most effective approach for accurate price range prediction.
b.Data-set Description : The dataset used in this project is the Mobile Price Classification Dataset, commonly used for supervised learning tasks.

Source: Kaggle (Mobile Price Classification dataset)
Number of Records: ~2000 records
Number of features: 20 input features
Target variable: price_range
Problem type: Multi-class classification
Features :
Hardware specifications: battery power, RAM, internal memory, mobile weight
Display properties: screen height, screen width, pixel resolution
Camera features: front and primary camera megapixels
Connectivity options: WiFi, Bluetooth, 3G, 4G
Other attributes: number of cores, clock speed, talk time
c.Models Used
The following models are used for training and are available in dropdown to select :
1.Logistic Regression 
2. Decision Tree Classier
3. K-Nearest Neighbor Classier 
4. Naive Bayes Classier - Gaussian or Multinomial
5. Ensemble Model - Random Forest
6. Ensemble Model - XGBoost 

For each of the models above, calculated the following evaluation  metrics: 

1.Accuracy
2.AUC Score
3.Precision
4.Recall
5.F1 Score
6.MCC Score	

Metrics comparison is depicted below

d.Model Comparison

Model Name	Observation about model performance
Logistic Regression	Achieved the best overall performance with the highest accuracy, F1-score, MCC, and near-perfect AUC, indicating excellent class separation and strong generalization.
Decision Tree	Provided moderate performance but showed signs of overfitting, resulting in lower accuracy and MCC compared to ensemble and linear models.
KNN	Performed poorly overall, with the lowest accuracy, F1-score, and MCC, indicating sensitivity to feature scaling and high dimensionality.
Naive Bayes	Delivered stable and consistent performance, but lower accuracy than ensemble models due to the strong feature independence assumption.
Random Forest (Ensemble)	Achieved strong and balanced performance, outperforming single decision trees by reducing overfitting through ensemble learning.
XGBoost (Ensemble)	Demonstrated excellent performance, second only to Logistic Regression, with high accuracy, AUC, and MCC, showing effective boosting and feature interaction learning.

Conclusion : RandomForest & XGBoost performed best 
