# FraudulentJobPostDetection
This project focuses on identifying **fraudulent job postings** using natural language processing (NLP) and machine learning.  
It applies a combination of text processing and classification models to distinguish real job ads from fake ones with high accuracy.

## Project Overview
The goal of this project was to detect fake job listings based on text descriptions and metadata.  
A **Random Forest classifier** was trained on cleaned and vectorized text data, achieving strong precision, recall, and overall accuracy.

Key steps included:
- Cleaning and preprocessing textual job posting data  
- Removing stop words and performing tokenization  
- Transforming text with **TF-IDF vectorization**  
- Training a **Random Forest** model for binary classification  
- Evaluating performance with accuracy, recall, precision, and ROC-AUC  

## Results & Insights
- Achieved an ROC-AUC score of **0.98**, with high precision and recall.  
- The model effectively identified language patterns typical of fraudulent postings (e.g., vague descriptions, missing company details).  
- Demonstrated how NLP techniques can add value in real-world data integrity and trust applications.

## Tools & Libraries
- Python  
- pandas, numpy  
- scikit-learn  
- nltk or spaCy  
- matplotlib, seaborn  

## Skills Demonstrated
- Natural language processing (NLP)  
- Feature engineering from text data  
- Model training and evaluation  
- Classification metrics interpretation  
- Visualization of model performance  

## Repository Structure
- `Fraudulent Job Post Detection.ipynb` – main analysis notebook  
- `fake_job_dataset` – link to dataset
- `README.md` – project overview and documentation
