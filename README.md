# Outbrain Click Prediction

This repository contains the source code for my approach to solving the [Kaggle Outbrain Click Prediction](https://www.kaggle.com/c/outbrain-click-prediction/) competition. The challenge was to predict which pieces of content Outbrain's global user base is most likely to click on.

## Key Features:

* Technologies Used:
  
  * Apache Hadoop and PySpark for scalable and efficient processing of large datasets.
    
  * Parquet data format for optimised storage and fast querying.
    
  * SQL for extracting meaningful features for model training.
  
* Modeling:
  
  * Leveraged the FTRL-Proximal online learning algorithm for binomial logistic regression using the Vowpal Wabbit library, enabling effective learning on large-scale data.
  
## Results:

The best model achieved **a score of 0.679** on the test dataset, placing in the **top 50 out of 1,000** participants in the competition.
