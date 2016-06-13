# NYC-Taxi-Tips-Predictor


We consider the problem of determining some areas in NYC, from which people pay more tips to NYC cabs. We are interested in defining the meaning of "pay more tips" as well as "how much more is". To devise this solution we use open sourced data from the NYC Taxi and Limousine Commission, which includes information about all trips completed by cabs in NYC during June 2015. This solution focuses on building a 6-class classifier based on random forests with 25 trees. These classes correspond to the proportional percentage of the fare amount that will be paid as a tip in a taxi ride from NYC based on 12 attributes that we have selected and derived. The performance obtained so far is over 85% with a standard deviation of 0.04%.

The files can be utilised following the numerical order:

1. Analysis & Planning Stage.ipynb - Where basically an analysis and clean-up of the raw dataset is performed.
2. Development .ipynb - In which we did the feature selection process.
3. Random Forests Classifier.ipynb - Here we show the training and testing process of a Random Forests Classifier using 25 trees and a 10-fold cross-validation.


The project hasn't entirely been concluded. Nevertheless, this is the release of the first part of the solution we're working on.
