# ML_classification
In this repository I work on different classifiers (fish classifier, number classifier etc.)

## Fish Classifier

**1. Introduction**

I used dataset from the kaggle (link below). 
There are 7 classes of fish in this dataset. There are 159 samples of all fish.
Each fish has 6 characteristics (3xlength, width, height and weight). Firstly I implemented my own encoder. Additionally dataset has been normalized. Then I tested 3 classification methods:
 * RandomClassifier - baseline/dummy
 * KNNClassifier - k-nearest neighbors
 * LNRClassifier - linear regression
 * 
In the structure of the code, such classes can be distinguished:
 *  Encoder 
 *  Dataset
 *  Classfier - kind of superclass for next classifier classes
 *  RandomClassifier, KNNClassifier and LNRClassifier
 
I wrote program in jupyter notebook.
https://www.kaggle.com/aungpyaeap/fish-market

**2. Technologies**

 * Python 3.9
 * Numpy 1.21.4
 * Pandas 1.3.5

**3. Results**

I measured the accuracy of the test data. I got the best results for KNNClassifier and LNRClassifier. Their accuracy is betwween 0.8 and 0.9
