# Module_17_Challenge

Precision and Recall Scores

Each of the four models had great precision scores while having mediocre recall scores:
  Naive Random Oversampling:
  
  - pre: 0.99 rec: 0.66
  
  Smote Oversampling:
  
  - pre: 0.99 rec: 0.66
  
  Undersampling
  
  - pre: 0.99 rec: 0.66
  
  Combination Sampling
  
  - pre: 0.99 rec: 0.58
  
  The worst model in terms of recalling is the Combination Sampling model and the others yield the same exact results.
  
  The balanced accuracy scores: 
    Naive Random Oversampling:
  - .65
  Smote Oversampling:
  - .63
  Undersampling
  - .63
  Combination Sampling
  - .64
  
  As you can see, the accuracy scores are not optimal using these models. The scores are well below par and we would recommend using these models with caution but if we had to choose one model over the rest, it would be the Naive Random Oversampling model because it yields the same precision and recall scores while having a higher accuracy score than the rest, even though it is still a bit low in general at 65%. 
