# Language_classifier

Here I performed language classification using `sklearn`, a powerful ML library. The languages are     
+ Slovak
+ Czech
+ English

The dataset has a class imbalence problem, Czech consists of only few words. Then I perform the `Naive Bayes` algorithm which is based on Bayes Theorm, which performs poorly on test data, more specificly on CS class. Then I adjusted 2 parameters and the performance has improved. F1 score got increased to .83 from .61.    
Finally I used Subwords to Shift Perspective (Check *[here](https://arxiv.org/abs/1508.07909)*). The performance has improved a little bit. F1 score become .84 this time    

I added all the important files related to the project. All source codes are available on notebook file. A little bit theory is also added in the notebook. The dataset is also available. The helper function what is imported in the notebook can also be find from here.
