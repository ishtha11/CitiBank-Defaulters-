# CitiBank-Defaulters-
The objective of this Dataset is that We have to find whether the target variable is the defaulter or not.
The evaluation metric is the accuracy.

Step taken to acheive the objective on this dataset:
Step 1: Imported all important libraries pertaining to machine learning

Step 2: First we read the train1 csv file.

Step 3: We found the basic parameters like head, columns,etc, we found the shape of the train dataset. We dropped the unnecessary columns as it would have affected the accuracy. We also used the decribe function to check the mean, standard deviation, etc. We used heatmap to find out the correlation(map form). We used pairplot to find the correaltion between pairs(graph form). After that i applied dummification on the categorical values.(through dummication we convert categorical values into numerical values).

Step 4: I merged all the three train data set and formed & named it as newdata

Step 5: After data analysis, we moved to model building. Here first we applied train test split and then we used standard scaler function. We fit the model. 

Step 6: First we applied new train on Logistic Regression Model and got 77% accuracy. Then By using Decision Tree Model(without hyperparameters), we got 72% accuracy. After using hyperparameters, we got 81% accuracy. Then next model was Random Forest Model(without hyperparameters got 80%). After using Hyper Parameters in Random Forest Model we got 81.4% accuracy.

Step7: Then by using Bagging Model we got 80% accuracy. In, Gradient Boosting Model we got 81.6% accuracy. Lastly, we used the
Voting classifier and got 81.7% accuracy.


Final Accuracy turns out to be 81.3%













