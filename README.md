# Handwritten_digit_recog
MNIST is a (”Modified National Institute of Standards and Technology”) classic dataset of handwritten images
has served as the basis for benchmarking classification algorithms.
Preprocessing the dataset and separating the features and outcome.
We split the data as training and testing data and scale the data before applying any algorithm so that all the
features contribute equally to the result.
We apply ML models like Logistic Regression and KNN on the data to classify digits and compare their accuracy.
The accuracy score of the Logistic regression in training dataset comes out to be 95% and that for the testing
dataset comes out to be 90%.
The accuracy score of the KNN with K=3 in training dataset comes out to be 96% and that for the testing
dataset comes out to be 94%.
We can conclude, K=3 has the highest accuracy among all other values of K for training as well as test dataset.
Therefore, we can say that best value for number of neighbors is 3.
