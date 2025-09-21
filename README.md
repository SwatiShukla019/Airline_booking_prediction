# Airline_booking_prediction
Enhancing airline booking prediction through multilingual sentiment analysis and demographic personalization using deep learning. Implements traditional ML baselines, XLM-RoBERTa for multilingual sentiment, and hybrid deep learning models with demographic embeddings.

---

##  Project Overview
- **Goal**: Improve airline booking prediction by integrating **multilingual sentiment analysis** (XLM-RoBERTa) with **demographic personalization** (age, gender, travel class).
- **Models**: 
  - Traditional ML: Logistic Regression, Random Forest, SVM, KNN
  - Deep Learning: Text-only, Hybrid (Frozen), Hybrid + Fine-Tuning, Hybrid + FT + Class Weights
- **Evaluation**: ROC-AUC, F1@0.30, Confusion Matrices

---

## Repository Structure
- `notebooks/` → Jupyter notebooks for dataset preparation, augmentation, ML/DL training
- `data/` → placeholder for datasets (download separately from Kaggle)

---

##  How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/SwatiShukla019/airline-booking-prediction.git

---

## Download datasets:
-Skytrax Airline Reviews
-Twitter Airline Sentiment
-Expedia Booking Data
-Passenger Satisfaction Dataset

---

## Run notebooks in order:
-dataset_merge.ipynb
-creating_synthetic_data.ipynb
-airline_traditional.ipynb
-deep_learning_airline_model.ipynb

---

## Results
-Best Model: Hybrid + Fine-Tuning
-ROC-AUC: 0.6636
-F1@0.30: 0.559
