# Agentic AI for Real-Time Credit Risk Assessment & Dynamic Limit Allocation

## 📊 Project Overview
This project implements an **Agentic AI framework** for real-time credit risk assessment and dynamic credit limit allocation using an XGBoost ensemble model with SHAP explainability.

## 👩‍🎓 Author
**Anaya Noor Syed**
- FAST NUCES, Islamabad
- 23i5521@isb.nu.edu.pk

## 🎯 Problem Statement
Traditional credit scoring uses monthly reviews, creating a dangerous delay between financial trouble and credit adjustment, resulting in higher default rates.

## 🤖 Proposed Solution
A **4-Agent Framework**:
1. **Monitoring Agent** - Ingests transaction data
2. **Reasoning Agent** - XGBoost risk calculation
3. **Action Agent** - Dynamic limit allocation (<500ms)
4. **Explainability Agent** - SHAP value reporting

## 📊 Results
| Metric | Score |
|--------|-------|
| Accuracy | 79% |
| Recall (Safe Borrowers) | 84% |
| Response Time | <500ms |
| High-Risk Detection | 92% |

## 🔧 Tech Stack
- Python 3.12
- XGBoost 2.0
- Scikit-learn
- SHAP (Explainable AI)
- SMOTE (Imbalanced data)

## 📁 Dataset
- **Source:** UCI Machine Learning Repository
- **Dataset:** Default of Credit Card Clients
- **Samples:** 30,000
- **Features:** 25 (payment history, bill amounts, demographics)

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook AgenticAI_CreditRisk.ipynb