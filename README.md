# 📌 Project - Recommendation System

## 🔍 Introduction
This project focuses on implementing and evaluating different recommendation system techniques.
- **Dataset:** MovieLens 1M
- **Techniques:**
    + Matrix Factorization (latent features)
    + Singular Value Decomposition (SVD)
- **Optimizers (manual implementation):**
    + Stochastic Gradient Descent (SGD)
    + Mini-batch Gradient Descent

## 📊 Performance Comparison

| Method                      | Train Loss | Test Loss | Train MAE | Test MAE | Train RMSE | Test RMSE |
|-----------------------------|------------|-----------|-----------|----------|------------|-----------|
| Matrix Factorization        | 0.0513     | 0.0518    | 0.1784    | 0.1795   | 0.2266     | 0.2275    |
| SVD                         | 0.0488     | 0.0510    | 0.1743    | 0.1786   | 0.2209     | 0.2258    |

## 📌 Observations
- **SVD outperforms Matrix Factorization** across all evaluation metrics, particularly in terms of lower loss and error values.
- Both methods exhibit minimal variance between training and test sets, indicating a well-generalized model with no significant overfitting.
- While Matrix Factorization remains a solid approach, **SVD provides notable improvements in accuracy**.