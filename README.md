Phishing Website Detection using Machine Learning
Overview
This project focuses on detecting phishing websites using machine learning models. We analyze a dataset that categorizes websites into legitimate, phishing, or suspicious based on various features. The dataset is sourced from the UCI Machine Learning Repository.

Dataset Details
Total Instances: 1353
Categories:
Legitimate websites (1) → 548 instances
Phishing websites (-1) → 702 instances
Suspicious websites (0) → 103 instances
The dataset contains no missing values, making it ideal for direct analysis and modeling.

Features
Key website attributes analyzed include:

SFH (Server Form Handler)
popUpWindow
SSLfinal_State (SSL certificate validation)
Request_URL
URL_of_Anchor
web_traffic
URL_Length
age_of_domain
having_IP_Address
These features help determine whether a website is safe or malicious.

Objective
The goal of this project is to:
✅ Preprocess and analyze the dataset
✅ Train machine learning models for phishing website detection
✅ Evaluate model performance using classification metrics

Machine Learning Models Used
Support Vector Machine (SVM)
Random Forest Classifier
Implementation
🔹 Preprocessing: Data normalization and feature engineering
🔹 Model Training: Applying SVM and Random Forest to classify websites
🔹 Evaluation: Measuring accuracy, precision, recall, and F1-score

Results & Findings
The trained models effectively classify websites as legitimate, phishing, or suspicious based on the extracted features. Further optimization can be done using hyperparameter tuning.

📌 Future Enhancements:

Add deep learning techniques for improved accuracy
Implement real-time phishing detection integration
Expand dataset for better generalization
