# Hotel Booking Cancellation Risk Prediction

## Overview

This project aims to predict hotel booking cancellations, used as a proxy for payment-related fraud. Drawing from real-world experience in the hotel industry, the project addresses operational inefficiencies caused by frequent cancellations due to invalid or declined credit cards. The objective is to identify high-risk bookings before arrival.

## Dataset

- Source: Kaggle – Hotel Booking Demand
- Size: 119,390 hotel reservations
- Target variable: `is_canceled` (binary)

## Methodology

- Data cleaning and missing value handling
- Removal of post-booking leakage features (reservation_status, reservation_status_date)
- Train / test split (80% / 20%)
- CatBoost classifier with native categorical feature handling
- Evaluation with ROC-AUC

## Results

- Strong predictive performance (ROC-AUC > 0.9)
- Model identifies high-risk bookings prior to arrival
- Feature importance analysis highlights key drivers
- Model saved as hotel_fraud_model.json for deployment
