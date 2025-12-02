# Phishing URL Detection using the PhiUSIIL Dataset

**Sai Charan Petchetti**

University of California, Los Angeles

AOS SCI C111: Introduction to Machine Learning for the Physical Sciences

Dr. Alexander Lozinski

December 5, 2025
<br>

Phishing attacks continue to constitute a major cybersecurity threat, with detection systems increasingly relying on machine learning techniques to identify fraudulent URLs. This study presents a comparative analysis of feature engineering strategies for phishing URL detection using the PhiUSIIL dataset, which contains 235,795 URLs with three distinct feature categories: URL-based, HTML-based, and derived features. 

We evaluate the discriminative power of each feature category using classical machine learning models including Logistic Regression, Random Forest, and XGBoost. Our results demonstrate that models trained on URL and HTML features achieve near-perfect classification performance (99.98% accuracy), substantially outperforming URL-only configurations (99.80% accuracy). Feature importance analysis reveals that HTML features such as *NoOfExternalRef* and *NoOfImage* provide the strongest discriminative signal, while derived features based on third-party legitimate URL databases contribute minimal additional value when HTML features are present.

Additionally, TF-IDF vectorization of raw URL strings achieves competitive performance (99.70% accuracy) without manual feature engineering, though generalizability concerns remain. These results offer practical guidance for balancing detection accuracy against computational cost in phishing URL detection systems, while highlighting the critical limitation of potential model overfitting to specific datasets.
<br>

## [Report](/AOS_SCI_C111_Final_Project.pdf)

## [Data](https://archive.ics.uci.edu/dataset/967/phiusiil+phishing+url+dataset)

## [Code](https://colab.research.google.com/drive/1dHjL9VodZVov5zbB7-QWdXVVWBn39YIJ?usp=sharing)
