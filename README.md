
# LSTM for Cyber Attack Classification

This project implements an **LSTM-based neural network** to classify cyber attacks using labeled time-series/network data.  
The repository contains training code, requirements, and evaluation results.

---

## 📂 Project Structure
- `notebooks/` – Jupyter notebooks for data preprocessing, training, and evaluation  
- `requirements.txt` – Python dependencies  
- `README.md` – Project documentation  

---

## ⚙️ Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```
## 📊 Dataset

The dataset consists of network traffic samples labeled as normal or cyber attack classes. These Steps include:
- Feature scaling/normalization
- Train/validation/test split
- Encoding categorical labels <br>
<br>
Your Data's Dimension should be (sample number, time series data point, feature number)

## 🔍 Evaluation
Metrics used:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
## 📖 Reference

If you use this project or find it helpful, please cite our related research work:

Pongsakorn Anantarativakorn, Thongchart Kerdphol, *“Long Short-Term Memory-Based Approach for Ensuring Cyber-Security in Grid-Forming Inverters ,”*  
**IEEE Access**, Accepted (in press), 2025.
