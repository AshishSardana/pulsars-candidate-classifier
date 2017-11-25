# pulsars-candidate-classifier

High Time Resolution Universe (HTRU) Survey was conducted to search for Pulsars and Fast Transients using the Parkes Telescope in Australia.
Majority of the Pulsars detections were actually false positives caused by radio frequency interference (RFI) and noise.
We have used state of the art Machine Learning techniques that have improved significantly in recent years to evaluate feature importance and compare the performances of different approaches to design a binary classifier that automatically labels real Pulsar candidates.
We have tried to address the problem of class imbalance by using Synthetic minority oversampling technique (SMOTE) and optimized our models by hyper parameter tuning to maximize accuracy and the geometric mean.

## Methodology

### Input Data
17,898 examples and 8 features

### Feature Pre-processing
1. Standard Scaler
2. Stratified train-test split
3. Oversampling using SMOTE

### Algorithm

#### Supervised Approach
1. Decision Tree
2. SVM
3. XgBoost
4. Neural Networks

#### Unsupervised Approach
1. Calculating feature importance
2. K-Means
3. Agglomerative Clustering

### Performance Metric
1. Confusion Matrix
2. F-Score
3. G-Mean


**Note:** Hyper-parameters are adjusted for best performance.
