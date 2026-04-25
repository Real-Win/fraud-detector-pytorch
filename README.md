# fraud-detector-pytorch
Détecteurs de fraudes bancaires avec Pytorch
# 🔍 Détecteur de Fraudes Bancaires avec PyTorch

## 📋 Description
Système de détection de fraudes bancaires basé 
sur un réseau de neurones (MLP) entraîné sur 
284 807 transactions réelles.

## 🚀 Résultats
| Métrique | Sans SMOTE | Avec SMOTE |
|----------|-----------|------------|
| Accuracy | 99.94%    | 99.91%     |
| Recall   | ~0%       | **86%** ✅  |
| F1-Score | ~0%       | **0.79** ✅ |

## 🧠 Stack Technique
- Python 3.x
- PyTorch
- Scikit-learn
- imbalanced-learn (SMOTE)
- Pandas / NumPy

## 📦 Installation
```bash
pip install torch scikit-learn imbalanced-learn pandas numpy
```

## 📊 Dataset
[Credit Card Fraud Detection - Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284 807 transactions
- 492 fraudes (0.17%)

## 🏗️ Architecture
## 💡 Problème résolu
Dataset déséquilibré résolu avec **SMOTE** :
- Avant : 394 fraudes
- Après : 227 451 fraudes synthétiques

## 👨‍💻 Auteur
**God-win** — Étudiant en 1ère année IA/Informatique
