Name: Pavana Pranoy Pondurthi 
Student ID: 700749767
Naive Bayes and SVM Methods  

Based upon the Data SVM method provided an accuracy of 74.42% and GaussianNB Accuracy is 55.81% . With same test size and random state, Thus this states that SVM Algorithm performs well in this case.

Supporting Factors for these are as follows:

GNB is a simple probabilistic classifier based on Bayes' theorem that is fast to train and easy to interpret. It makes strong independence assumptions between the features, meaning that it assumes that the features are conditionally independent given the class. It is most commonly used for text classification problems where the features are words or n-grams. GNB is a good choice when you have a large number of features, as it scales well to high-dimensional data.

SVM, on the other hand, is a more sophisticated method that uses the concept of margins to find the best decision boundary between classes. SVM can handle complex non-linear relationships between features and is often used for image classification or classification problems with a small number of samples. SVM is also more robust to overfitting than GNB when the number of features is large, so it might be a better choice when dealing with high-dimensional data.

In general, GNB is a good first choice for classification problems, especially when the data is large, the problem is well understood, and computational resources are limited. SVM is a more powerful method that is useful for more complex classification problems, especially when the data is small, the problem is not well understood, or there is a need for more robustness to overfitting.

Conclusion: So here the data we have is only 215 rows which are very limited to train the model and there are multiple parameters which makes the prediction complex. So, SVM Algorithm is best suited for this data since the data is very small and also based upon the reasons mentioned above.








The Linear regression program imports scikit learn, pandas matplotlib and numpy libraries, will read the data from the csv file and calculate the mean squared error for the data, will perform train and testing the model later visulizing the train and test data using the scatter plot.
