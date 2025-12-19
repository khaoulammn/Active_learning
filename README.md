## Arabic Handwritten Character Recognition using Active Learning

### Project Description
This project focuses on Arabic Handwritten Character Recognition (HCR) using Active Learning to reduce the amount of labeled data while preserving classification performance. The task is challenging due to the cursive nature of Arabic script, multiple letter forms, and writing variability.

### Objectives
* Build a complete handwritten Arabic character recognition pipeline
* Apply and compare multiple Active Learning strategies
* Reduce annotation cost
* Analyze performance improvement across iterations

### Dataset
* OIHACDB
* 5600 samples
* 28 Arabic character classes
* 31 statistical features
* Balanced dataset (200 samples per class)

### Methodology
* Label encoding and data shuffling
* Robust normalization using RobustScaler
* Dimensionality reduction with PCA
* Active Learning with iterative sample selection

### Active Learning Strategies
* Random Sampling
* Least Confidence
* Margin Sampling
* Entropy Sampling
* Query By Committee
* Expected Model Change
* Density-Weighted Uncertainty
* Hybrid (Uncertainty + Diversity)

### Classifier
* Random Forest
  * Robust to noise
  * Stable probability estimation
  * Fast retraining during Active Learning
 
### Results
* Active Learning reduces annotation effort compared to random sampling
* Confusion mainly occurs between visually similar Arabic characters

### Future Work
* Deep learning-based features
* Advanced Active Learning strategies
* Extension to word-level recognition
