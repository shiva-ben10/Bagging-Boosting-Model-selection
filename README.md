**Ensemble Machine Learning Algorithms in Python with scikit-learn**
![image](https://github.com/user-attachments/assets/5b72f495-e3a1-47a0-ba2d-158d4957a57b)

The three most popular methods for combining the predictions from different models are:

**Bagging.** Building multiple models (typically of the same type) from different subsamples of the training dataset.
**Boosting.** Building multiple models (typically of the same type) each of which learns to fix the prediction errors of a prior model in the chain.
**Voting.** Building multiple models (typically of differing types) and simple statistics (like calculating the mean) are used to combine predictions.

**1. Bagging Algorithms**
Bootstrap Aggregation or bagging involves taking multiple samples from your training dataset (with replacement) and training a model for each sample.

The final output prediction is averaged across the predictions of all of the sub-models.
The three bagging models covered in this section are as follows:

1.1. Bagged Decision Trees 

1.2. Random Forest 

1.3. Extra Trees 

**2.Boosting Algorithms**
Boosting ensemble algorithms creates a sequence of models that attempt to correct the mistakes of the models before them in the sequence.
Once created, the models make predictions that may be weighted by their demonstrated accuracy and the results are combined to create a final output prediction.

The two most common boosting ensemble machine learning algorithms are:

2.1. AdaBoost
2.2. Stochastic Gradient Boosting


