----------MY CONTRIBUTION TO THE PROJECT----------

--> I have done the Data Modelling part. I have used sklearn.tree for decision tree classifier and imported datasets,linear_model for logistic regression

--> After the data collection and data cleaning part I have split the 80percent of data as training data and 20 percent as testing data

--->Initially I have performed both Logistic Regression and Decsion Tree but due to the low accuracy of logistic regression I have used the Decision tree in the final output.


-----#Code-----

self.dt = DecisionTreeClassifier()
        self.dt.fit(mainarray, train_y)