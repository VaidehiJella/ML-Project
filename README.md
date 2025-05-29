Authenticity Classification for Job Postings using ML Techniques








📑 Abstract

With the surge in online job postings, fake job listings have become a growing concern, misleading job seekers and damaging the reputation of legitimate employers. This project presents a system that uses machine learning and NLP techniques to classify job postings as real or fake. The system has shown high accuracy and efficiency in detecting fraudulent listings, making the job-hunting process safer.


Introduction

Authentic job postings are essential for a fair hiring process. However, distinguishing fake listings is challenging due to:

1)The sophistication of scam techniques

2)Manual verification being time-consuming

3)Inadequate keyword-based detection methods

This project leverages ML and NLP to create a scalable, efficient classification system.


📊 Dataset

Source: Kaggle - Fake Job Postings Dataset

Attributes: job_id, title, location, department, salary_range, description, requirements, benefits, etc.

Target: fraudulent (0 - Real, 1 - Fake)


🛠 Technologies Used

1)Programming Language: Python

2)IDE: Jupyter Notebook

Libraries:

1)Data Processing: pandas, numpy

2)Visualization: seaborn, matplotlib

3)ML Models: scikit-learn

4)NLP: nltk, re

5)Evaluation: confusion_matrix, classification_report


🔍 Methodology

1)Data Preprocessing

Removed null values and irrelevant entries

Applied lemmatization and tokenization

Standardized text fields for uniformity

2)Feature Engineering

Converted text to numerical features using TF-IDF vectorization

Encoded categorical data

3)Model Building

We experimented with the following classifiers:

-Naive Bayes

-Random Forest

-Decision Tree

-Support Vector Machine (SVM)

4)Evaluation Metrics

-Accuracy

-Precision

-Recall

-F1-Score


🧾 Conclusion

This project successfully demonstrates the application of machine learning and NLP in identifying fraudulent job postings. By automating the detection process, the system reduces human effort and improves accuracy.


🚀 Future Work

-Deploy model via a web application (e.g., Flask or Streamlit)

-Use Deep Learning models like BERT for better text understanding

-Integrate real-time job data from APIs

-Multilingual support for broader application






