# Sprint17_Proyect-Automatied_learning_for_texts
# Film Junky Union — Sentiment Analysis for Movie Reviews

## Project Overview

Film Junky Union, a modern community for classic movie enthusiasts, is developing a system to automatically filter and categorize movie reviews.

The objective of this project is to build and evaluate machine learning models capable of detecting negative movie reviews automatically using IMDB review data.

The final model must achieve an F1 score of at least **0.85**.

This project focuses on:
- Natural Language Processing (NLP)
- Sentiment Analysis
- Text Classification
- Machine Learning for textual data

---

# Dataset

The dataset contains movie reviews from IMDB labeled as:

- Positive Review → `1`
- Negative Review → `0`

The data includes:
- Review text
- Sentiment label
- Additional metadata

---

# Project Workflow

## Data Loading
- Import the IMDB reviews dataset
- Inspect structure and missing values

## Data Preprocessing
- Text cleaning
- Lowercasing
- Removing punctuation
- Tokenization
- Stopword removal
- Lemmatization

## Exploratory Data Analysis (EDA)
- Review distribution analysis
- Class imbalance evaluation
- Text length analysis
- Word frequency visualization

## Feature Engineering
- TF-IDF Vectorization
- Text embeddings
- NLP preprocessing pipelines

## Model Training
At least three different machine learning models were trained and evaluated, including:

- Logistic Regression
- Gradient Boosting
- Random Forest
- (Optional) BERT embeddings

## Model Evaluation
Models were evaluated using:
- F1 Score
- Accuracy
- Precision
- Recall
- Confusion Matrix

---

# Models Used

| Model | Description |
|---|---|
| Logistic Regression | Baseline NLP classifier |
| Gradient Boosting | Ensemble boosting model |
| Random Forest | Tree-based ensemble classifier |
| BERT (Optional) | Transformer-based embeddings |

---

# Goal

The target metric for this project is:

```python
F1 Score >= 0.85
```

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- spaCy
- Jupyter Notebook

---

# Natural Language Processing Techniques

The project includes:
- Tokenization
- Lemmatization
- Stopword Removal
- TF-IDF Vectorization
- Text Embeddings
- Sentiment Classification

---

# Results

The best-performing model achieved strong performance in detecting negative reviews while maintaining balanced precision and recall.

Key findings:
- TF-IDF + Logistic Regression performed surprisingly well.
- Ensemble methods improved generalization.
- Text preprocessing significantly impacted model quality.
- BERT embeddings improved semantic understanding but required higher computational resources.

---

# Example Predictions

Example review:

```text
"The movie had an excellent atmosphere, but the story was incredibly boring."
```

Predicted sentiment:
```text
Negative Review
```

---

# Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/film-junky-union.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

# Future Improvements

- Fine-tuning transformer models
- Deploying the model as a web application
- Real-time sentiment prediction API
- GPU-based BERT training
- Hyperparameter optimization

---

# Author

## Bryan Brandon Patiño Guerrero

Junior Data Scientist  
Machine Learning • NLP • Predictive Analytics

📧 bryanbrandon.patino@gmail.com

---

# Acknowledgments

This project was developed as part of the Data Science program at TripleTen and focuses on practical applications of NLP and Machine Learning for sentiment analysis.
