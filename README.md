# Healthcare NLP Analytics – Patient Feedback Insights

## Overview
This project applies Natural Language Processing (NLP) and machine learning techniques to analyze unstructured patient feedback data in a healthcare context. The goal is to extract actionable insights related to service quality, patient satisfaction, and operational inefficiencies.

The project is organized into three analytical phases that reflect a realistic healthcare analytics workflow.

## Project Phases

### Phase 1 – Text Exploratory Data Analysis
- Text cleaning and preprocessing
- Tokenization and stopword removal
- TF-IDF feature extraction
- Keyword frequency and pattern analysis

### Phase 2 – Sentiment Modeling
- Rule-based sentiment labeling to bootstrap training data
- TF-IDF feature engineering
- Supervised classification using Logistic Regression
- Model evaluation using confusion matrix and classification report

### Phase 3 – Topic Modeling
- Topic extraction from patient feedback
- Identification of recurring service themes
- Visualization of topic distributions
- Interpretation of operational pain points

## Objectives
- Analyze unstructured healthcare text data
- Identify common service issues and satisfaction drivers
- Apply NLP techniques for scalable feedback analysis
- Translate insights into operational recommendations

## Tools & Technologies
- Python (Pandas, NumPy)
- NLP: NLTK, scikit-learn
- TF-IDF Vectorization
- Machine Learning (Logistic Regression)
- Topic Modeling
- Data Visualization (Matplotlib, Seaborn)
- Jupyter Notebook / Google Colab

## Key Insights
- Long wait times and scheduling issues are frequent sources of negative sentiment
- Positive feedback is closely associated with staff communication and care quality
- Topic modeling reveals operational patterns not easily captured in structured data

## Data
- Publicly available, de-identified healthcare-related text data
- Simulated samples used for demonstration purposes

## Model Limitations
- Small, simulated dataset
- Rule-based sentiment labeling
- Results are illustrative rather than production-grade

## Project Status
Complete

## How to Run
- View notebooks directly on GitHub, or
- Use the "Open in Colab" option for interactive execution
