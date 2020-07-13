# Applied-Machine-Learning
Applied Machine Learning in Python

One accurate measurement is worth more than a thousand expert opinions
— Admiral Grace Hopper 
## Some Great Informations;


Lasso Regression (Least Absolute Shrinkage and Selection Operator) 

http://approximatelycorrect.com/2016/11/07/the-foundations-of-algorithmic-bias/

"1"
After training a Radial Basis Function (RBF) kernel SVM, you decide to increase the influence of each training point and to simplify the decision surface. Which of the following would be the best choice for the next RBF SVM you train?

Decrease C, decrease gamma


"2"
Suppose you are interested in finding a parsimonious model (the model that accomplishes the desired level of prediction with as few predictor variables as possible) to predict housing prices. Which of the following would be the best choice?

Ridge Regression


"3"
Which of the following is an example of multiclass classification? (Select all that apply)

Classify a set of fruits as apples, oranges, bananas, or lemons
Predict whether an article is relevant to one or more topics (e.g. sports, politics, finance, science)


"4"
Which of the following is true of cross-validation? (Select all that apply)

Helps prevent knowledge about the test set from leaking into the model
Fits multiple models on different splits of the data
Increases generalization ability and computational complexity


"5"
Suppose you are interested in finding a parsimonious model (the model that accomplishes the desired level of prediction with as few predictor variables as possible) to predict housing prices. Which of the following would be the best choice?

Lasso Regression


"6"
After training a ridge regression model, you find that the training and test set accuracies are 0.98 and 0.54 respectively. Which of the following would be the best choice for the next ridge regression model you train?

You are overfitting, the next model trained should have a higher value for alpha



#When do we need high precision or high recall?
Models need high recall when you need output-sensitive predictions. For example, predicting cancer or predicting terrorists needs a high recall, in other words, you need to cover false negatives as well. It is ok if a non-cancer tumor is flagged as cancerous but a cancerous tumor should not be labeled non-cancerous.
Similarly, we need high precision in places such as recommendation engines, spam mail detection, etc. Where you don’t care about false negatives but focus more on true positives and false positives. It is ok if spam comes into the inbox folder but a really important mail shouldn’t go into the spam folder.




Data Leakage: 
https://medium.com/@colin.fraser/the-treachery-of-leakage-56a2d7c4e931
