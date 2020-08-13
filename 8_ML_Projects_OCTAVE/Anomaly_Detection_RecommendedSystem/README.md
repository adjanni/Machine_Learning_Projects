
### Anomaly Detection and Recommender System - Unøabel dataset

In this project has two parts:

  o) In the first part, I implement the anomaly detection algorithm and apply it to detect failing servers computers on a network. The features measure the throughput in mb/s and latency in ms of response of each server. The total dataset is m = 307 and there are unlabeled. I proceed as follow:
    1. Use a Gaussian model to detect anomalous examples in the dataset
    2. I implement an algorithm to select the thresold using the F1 score on a cross validation set (cv). For each cv, I compute the probability given the distribution. 
    3. I will also compute the F1 score which tell me how well I am doing on finding the ground thruth anomalies given a certain threshold.
  
  o) In the second part, I use collaborative filtering learning algorithm to build a recommender system for movie ratings. This dataset consists of rating on a scale of 1 to 5. The dataset has 943 users and 1682 movies. 
    1. Implement a collaborative filetering learning algorithm: 
      1.1. I start to implement the cost function without regularisation
      1.2 I implement the Collaborative filtering gradient without gradient
      1.3. I implement regulaised cost function follow with a regularised gradient
     
    2. I train my algorithm to make movie recommendation for myself.
      
