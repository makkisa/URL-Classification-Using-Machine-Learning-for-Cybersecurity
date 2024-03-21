# URL-Classification-Using-Machine-Learning-for-Cybersecurity
## Overview
The Malicious URL Detection System is designed to combat cybersecurity threats by accurately identifying and categorizing URLs as benign, phishing, defacement, or malware. Leveraging a comprehensive dataset of 651,191 URLs, this project employs machine learning techniques to provide an effective tool for preemptive cyber defense strategies. The dataset, enriched with features crucial for analysis, undergoes meticulous preprocessing, feature engineering, and modeling to achieve high predictive accuracy.

## Dataset
Our dataset comprises a vast collection of 651,191 URLs, meticulously classified into the following categories for detailed analysis:
- **Benign**: Safe URLs not involved in any malicious activities.
- **Phishing**: URLs designed to deceive users into giving away personal information.
- **Defacement**: URLs indicating unauthorized modifications of web pages.
- **Malware**: URLs associated with harmful software or content.

This rich dataset serves as the foundation for training our machine learning models, enabling them to learn and generalize from a diverse set of examples.

## Features
The project focuses on several key features derived from the URLs, crucial for the classification process:
- URL Length
- Count of Alphabetical Characters
- Count of Digits
- Count of Special Characters
- Usage of HTTPS Protocol
- Presence of IP Address in the URL
- Geographic Region of URL's Top-Level Domain

These features are instrumental in distinguishing between different types of URLs, aiding in the accurate detection of malicious links.

## Machine Learning Models
We explored various machine learning algorithms, ultimately selecting the Extra Trees Classifier for its superior performance in terms of accuracy, precision, recall, and F1-score. Other models evaluated include:
- Decision Trees
- Random Forest
- AdaBoost
- K-Neighbors
- Gaussian Naive Bayes

Contributing
Contributions to improve the Malicious URL Detection System are welcome. Please read through our contributing guidelines for more information on how to submit pull requests, report issues, or suggest improvements.
