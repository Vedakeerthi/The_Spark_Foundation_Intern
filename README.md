# The_Spark_Foundation_Intern

At the spark foundation, I have been selected as Data science and Business analytics intern, where I have been given with some tasks, so that this repository consists of the task that I have gone through this intern.

* Task 1 : Prediction using supervised machine learning algorithm


## Task 1 : Prediction using supervised machine learning algorithm

Predict the percentage of an student based on the number of study hours, this is a simple linear regression task as it involves just 2 variables. This task is implemented by using both sklearn and from scratch, in the program from scratch, the 
model is implemented and the cost function of the model is calculated and it is further optimized using gradient descent algorithm, and the model is evaluated using the following metrics : 
1. Mean squared error
2. Root mean squared error
3. R2 error.

According to the task query, it is said to predict the student score when he studies at a rate of 9.25 hours per day.

So, the results are :

1. Based on the implementation from sklearn if a student studies 9.25 hrs a day he will score : 89.99093062789352
2. Based on the implementation from scratch if a student studies 9.25 hrs a day he will score : 92.97420126293007

## Task 6 : Prediction using decision tree algorithm

The query about this task is to create a decision tree and to visualize it graphically and to make the decision tree predict the output class based on the new data. The decision tree is implemented from sklearn, the decision tree is visualized using two methods

1. Text representation : 
The whole decision tree model which is trained using the train dataset, is represented and visualized using text, using this representation we can know which feature has the highest information gain based on the model, eventhough you can't able to clearly in case of text representation, we can visualize it graphically.

2. Graphical representation : 
Here the model is represented graphically, this graphical representation is imported from the tree class of the sklearn library, it requires other two parameters such as the feature name of the dataset and the class name of the dependent variable, and further you can also export the graph as a png file for further reference.

Once the decision tree is visualized, then the model can be used to predict the test data, so the model has predicted the test data, and the accuracy of the model is evaluated using the score function of the model, so the accuracy of the model is 0.91111 which is quiet good for the decision tree model.
