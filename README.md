# FedLung-Shield

Privacy-preserving pneumonia detection from chest X-rays using Federated Learning (FedAvg, FedProx, Differential Privacy).

## Problem
Hospitals cannot share patient data because of privacy laws (such as India's DPDP Act), but a single hospital's data is often too small to train a reliable AI model. This project trains one shared model across several simulated hospitals without moving any patient data.

## Research Questions
1. Does federated learning beat training at each hospital alone?
2. How close is it to centralized training (all data pooled)?
3. How does performance change when hospitals have different data (non-IID)? Does FedProx help?
4. What is the accuracy cost of adding differential privacy?
5. Can an attacker still learn about patients, and does differential privacy stop it?

## Tech Stack
Python, PyTorch, torchvision, scikit-learn, Opacus, Google Colab

## Dataset
Chest X-Ray Images (Pneumonia), Kaggle (Paul Mooney)

## Status
In progress. Results coming soon.
