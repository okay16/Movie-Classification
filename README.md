# Movie-Classification


This Natural Language Processing project predicts the correct movie genre tags through the screenplays by upto 0.43 f1 score. 

I used scikit-learn's MultiLabelBinarizer to turn this into a Multilabel Classification Problem to better predict the relevant genres. Using TF-IDF features to get the 363 predictors. However, due to lack of computational power, it was best suited to use Logistical Regression and turn this problem into a One-Vs-Rest Classification Probelm.

The datasets are taken from CMU Movie Summary Corpus: http://www.cs.cmu.edu/~ark/personas/


