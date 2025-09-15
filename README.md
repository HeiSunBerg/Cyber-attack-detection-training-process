
# LSTM for Cyber Attack Classification

This project implements an **LSTM-based neural network** to classify cyber attacks using labeled time-series/network data.  
The repository contains training code, requirements, and evaluation results.

---

## 🔎 Introduction

Cybersecurity threats are becoming more complex, and traditional rule-based detection systems often fail to recognize new attack patterns.  
This project applies **Long Short-Term Memory (LSTM) networks** to capture temporal dependencies in network traffic and classify whether a connection is **normal** or a type of **cyber attack**.

---

## 📂 Project Structure
- `notebooks/` – Jupyter notebooks for data preprocessing, training, and evaluation  
- `requirements.txt` – Python dependencies  
- `README.md` – Project documentation  

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/HeiSunBerg/Cyber-attack-detection-training-process.git
cd lstm-cyber-attack
```
Install dependencies with:

```bash
pip install -r requirements.txt
```
## 📊 Dataset

The dataset consists of network traffic samples labeled as normal or cyber attack classes. These Steps include:
- Feature scaling/normalization
- Train/validation/test split
- Encoding categorical labels
<br>
Your Data's Dimension should be (sample number, time series data point, feature number)

## 🔍 Evaluation
Metrics used:
- Accuracy > 90%
- Precision, Recall, F1-score
- Confusion Matrix (Normal vs. Attack classes)
## 📖 Reference

If you use this project or find it helpful, please cite our related research work:

Pongsakorn Anantarativakorn, Thongchart Kerdphol, *“Long Short-Term Memory-Based Approach for Ensuring Cyber-Security in Grid-Forming Inverters ,”*  
**IEEE Access**, Accepted (in press), 2025.
