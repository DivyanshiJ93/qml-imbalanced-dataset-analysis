# Impact of Dataset Imbalance on Quantum Machine Learning

##  Overview
This project analyzes how dataset imbalance affects classical and quantum machine learning models.

We compare:
- SVM (Classical)
- QSVM (Quantum Kernel-based)
- VQC (Variational Quantum Model)

##  Objective
To evaluate whether quantum machine learning models handle imbalanced datasets better than classical models.

##  Experimental Setup
- Dataset: Iris (binary classification)
- Imbalance ratios: 50:50 → 90:10
- Noise added for realistic conditions
- Metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score

## Results
- Accuracy increases with imbalance
- Recall and F1-score drop significantly
- Models fail to detect minority class at high imbalance

##  Key Insight
Quantum machine learning models do not inherently solve dataset imbalance.

## Conclusion
Data quality has a greater impact on performance than model complexity, even in quantum systems.

##  Tech Stack
- Python
- Scikit-learn
- Qiskit
- Matplotlib / Seaborn

## Future Work
- Apply SMOTE / resampling techniques
- Use class-weighted training
- Test on larger datasets
