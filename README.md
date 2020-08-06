# Implementation of Categorical Naive Bayes classifier from scratch but implement evaluation metrics and procedures and data processing usw following Python Libaray 

– pandas: https://pandas.pydata.org/
– scikit learn: https://scikit-learn.org/
– numpy: https://numpy.org/
– scipy: https://www.scipy.org/
– any of Python’s native libraries: https://docs.python.org/3/library/

Load_data(), which opens the data file,and converts it into a usable format
split_data(), where you split your data sets into a training set and a test set.
train(), where you build a Naive Bayes model from the training data
predict(), where you use a trained model from train() to predict a class (or class distri- bution) for the test data
evaluate(), where you will output the accuracy of your classifiers


# Data adapted in this project is Student data set available form The UCI machine learning repository (https://archive.ics.uci.edu/ml/index.html).
Some critical information of data set
 1. File containing the data set: student.csv
 2. 649 instances
 3. 30 nominal attributes. Note that although some attributes may equally be treated as ordinal, for the purpose of this assignment we assume all attributes are   nominal.
 4. 6 classes, corresponding to predicted final grade: {A+, A, B, C, D, F}
 5. student.txt explains the attributes and class-labels
