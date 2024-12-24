# Anamoly-detection-in-network-traffic-by-cybersecurity

This project develops a hybrid anomaly detection model by combining Autoencoder and Random Forest, evaluated on the UNSW-NB15 dataset. The approach integrates unsupervised and supervised techniques to improve anomaly detection accuracy.

## Dataset
- *Source*: UNSW-NB15  
  - Training set: [UNSW_NB15_training-set.csv](https://github.com/Nithin7569/Anamoly-detection-in-network-traffic-by-cybersecurity/blob/main/UNSW_NB15_training-set.csv)
  - Testing set: [UNSW_NB15_testing-set.csv](https://github.com/Nithin7569/Anamoly-detection-in-network-traffic-by-cybersecurity/blob/main/UNSW_NB15_testing-set.csv)  

## Features and Objectives
1. *Data Processing*:
   - Handled imbalanced data using SMOTE.
   - Preprocessed mixed feature types (numeric and categorical).
   - Standardized numeric data and one-hot encoded categorical data.
2. *Models*:
   - *Autoencoder*: Unsupervised feature extraction.
   - *Random Forest*: Supervised classification.
   - *Hybrid Model*: Combined predictions from both models.
3. *Performance Metrics*:
   - Precision, Recall, F1-Score, Accuracy.
   - AUC-ROC and Precision-Recall Curve.

## Results
- *Precision*: 0.92  
- *Recall*: 0.90  
- *F1-Score*: 0.91  
- *Accuracy*: 0.93  

## Steps to Reproduce
1. Clone this repository:  
   ```bash
   git clone https://github.com/Nithin7569/Anamoly-detection-in-network-traffic-by-cybersecurity.git
