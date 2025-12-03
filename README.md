# Phishing URL Detection using the PhiUSIIL Dataset

**Sai Charan Petchetti**

University of California, Los Angeles

AOS SCI C111: Introduction to Machine Learning for the Physical Sciences

Dr. Alexander Lozinski

December 5, 2025
<br>

Phishing attacks continue to constitute a major cybersecurity threat, with detection systems increasingly relying on machine learning techniques to identify malicious URLs. This study presents acomparative analysis of feature engineering strategies for phishing URL detection using the PhiUSIIL dataset, which contains 235,795 URLs with three distinct feature categories: URL-based, HTML-based,
and derived features.

We assess how effectively each feature category distinguishes between legitimate and phishing sites through classical machine learning algorithms such as Logistic Regression, Random Forest, and XGBoost. Our findings show that models trained on URL and HTML features achieve near-perfect classification performance (99.98% accuracy), significantly outperforming URL-only configurations (99.80% accuracy). Feature importance analysis indicates that HTML features such as *NoOfExternalRef* and *NoOfImage* provide the most discriminative power, while derived features based on third-party datasets of legitimate URLs add little to no additional value when HTML features are present.

Moreover, applying TF-IDF vectorization directly to raw URL text produces comparable results (99.70% accuracy) without manual feature engineering, although generalizability concerns remain. These findings offer actionable recommendations for balancing detection accuracy against computational cost while training phishing URL detection models.
<br>

## [Report](/AOS_SCI_C111_Final_Project.pdf)

## [Data](https://archive.ics.uci.edu/dataset/967/phiusiil+phishing+url+dataset)

## [Code](https://colab.research.google.com/drive/1dHjL9VodZVov5zbB7-QWdXVVWBn39YIJ?usp=sharing)
