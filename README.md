# Hotel_Price_Prediction

Introduction: The primary objective of the project is to predict a new hotel profit if it is open in a given loacation using Machine Learning models. The hotel manager needs to know the future profit prediction along with the amount of the profit which can be gained. Here, I have used the historical data given with specific featuresset and labelled values by implementing classification and regression techniques. 


Dataset Details : I have used the sweetviz module to analyze the datasets which helps in visulizing the data content and automating the EDA. In the comparative study, the second part contains the 1000 rows and 21 columns in total as the required features without target or class. In addition to it, the other comparative study consists of the data with 36 features and a target. The total count of the dataset is 1500 datapoints with 36 features

Feature Engineering : The dataset in the second task has some features which are asymmetric, and they need to be treated before fitting in a model. I used MinMaxScaler to convert the data into 0-1 format to normalised it. Also, A SimpleImputer is used for the imputation as there is one column which comprises 50 percent of Null values. The dataset in the third task has features which are asymmetric and they need to be treated before fitting in a model using the same method (StandardScaler) and later changed to 0-1 scale


Algorithms : For the second task classification algorithms are supposed to be used as it’s a binary classification task with True or False values. In order to solve it, I have used different models like Decision Tree, K Nearest Neighbor, SVM  and Gradient Boosting. Also, In order to compare their learning outcomes and evaluated them using metrics like accuracy, confusion matrix and classification report. 

#Classification Evaluation

 Algorithm          |Train Accuracy % |Test Accuracy %|F1_Score %|
| -------------     | -------------   |---------------|----------|
| Decision Tree     | 100             |86             |86        |
| K Nearest Neighbor| 74.37           |58             |58        |
| SVM               | 75              |70.5           |70        |
| Gradient Boosting | 97.37           |92             |92        |


The third task which is an additional comparative study and comprises of a regression problem and the Linear Regression, Decision Tree, SVR, K nearest Regressor and GBM Regressor have been used. To evaluate the task the Mean Absolute Percentage Error (MAPE) is used as the metrics for testing the performance on the test value predictions and the Linear Regression is used as the primary model. 

#Regression Evaluation

 Algorithm           |Test set MAPE  |
| -------------      | ------------- |
| Linear Regression  | 2.11          |
| Decision Tree      | 3.14          |
| SVR                | 3.21          |
| K Nearest Regressor|3.13           |
| GBM Regressor      |1.97           |

Conclusion : 

From the above observations, it can be concluded that the results of the project are enough to understand the ability of the machine learning algorithms is good enough to find out that the hotel at location is profitable or not and it will also help the managers to calculate the profit that could be obtained from the hotels.
