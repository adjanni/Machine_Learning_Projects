
**Detecting Credit Card Fraud using supervised and unsupervised learning**

In this repo, in the first part, I analyse the datasets (data cleaning, correlation analysis, labelisation of datasets). In the second part, I discuss the use of various supervised classifiers to capture fraudulent credit card transactions. The last part, I discuss the use of Principal Component Analysis (PCA) and Gaussian
Anomaly Detection (GAD) as Andrew Ng explain in his coursera's lecture [1]. The PCA is an unsupervised machine learning technique that decreases the size of the data while still keeping the information it contains [2].

**Error Analysis**
The dataset at our disposal is extremely skewed, . Hence, I measure the success rate with a netric called the F1-score. To do so, I compute precision and recall. 

**True positive (TP):** a transaction is flagged as anomalous when it is actually fraudulent.

**True negative (TN):** a transaction is NOT flagged when it is actually NOT fraudulent.

**False Negative (FN):** a transaction is NOT flagged when it is actually fraudulent.

**False positive (FP):** a transaction is flagged as anomalous when it is actually NOT fraudulent.


Precision calculates the rate of success of the model out of all transactions flagged as anomalous. It is expressed as:

Precision (P) = TP/(TP + FP)

Recall on the other hand, calculates the rate of success of the model out of all fraudulent transactions. It is expressed as

Recall (R) = TP/(TP + FN)

The F1-score is expressed by combining P and R:

F1 = 2 PR/(P+R)







**Bibliography**

[1] Andrew Ng - https://www.youtube.com/watch?v=lCipWj-Cets

[2] Amin Selim: Capturing fraudulent credit card transactions using a Gaussian Anomaly Detection algorithm with PCA masked data - https://www.imo.universite-paris-saclay.fr/IMG/pdf/report-selim_cle0d276d.pdf
