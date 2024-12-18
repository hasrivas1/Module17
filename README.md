README 

About the data:

The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. 

The classification goal is to predict if the client will subscribe a term deposit (variable y).

Additional Information:

The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. 

There are four datasets: 
1) bank-additional-full.csv with all examples (41188) and 20 inputs, ordered by date (from May 2008 to November 2010), very close to the data analyzed in [Moro et al., 2014]
2) bank-additional.csv with 10% of the examples (4119), randomly selected from 1), and 20 inputs.
3) bank-full.csv with all examples and 17 inputs, ordered by date (older version of this dataset with less inputs). 
4) bank.csv with 10% of the examples and 17 inputs, randomly selected from 3 (older version of this dataset with less inputs). 
The smallest datasets are provided to test more computationally demanding machine learning algorithms (e.g., SVM). 

Observations:
The accuracy of the different classification models have gone by 2-3 percent as compared to the results in the previous section. From the confusion matrices, we can also observe that the classifiers are now predicting label 1 a lot more often than in the previous case, when we were working with a limited set of features.

Even after hyperpaprameter tuning, it is difficult to major improvements in the accuracy of the different classification models. From the baseline model, we see that 88% of the samples belong to the same class. Hence the dataset is highly skewed towards samples from one class. This makes it challenging for AI models to learn how to accurately predict.
