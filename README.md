# task4
# 🧪 Logistic Regression – Breast Cancer Classification

Build a binary classifier using **Logistic Regression** to detect whether a tumor is **malignant (M)** or **benign (B)** from medical features.

---

## 📂 Dataset

- **Source**: Breast Cancer Wisconsin (Diagnostic)
- **File**: `data.csv`
- **Target**: `diagnosis` → `M` (1), `B` (0)
- **Dropped Columns**: `id`, `Unnamed: 32`

---

## ⚙️ Workflow

1. Load and clean data
2. Encode target (`M`=1, `B`=0)
3. Train-test split & standardize features
4. Train `LogisticRegression` model
5. Evaluate with:
   - Confusion Matrix
   - Precision & Recall
   - ROC Curve & AUC
6. Tune classification threshold
7. Plot sigmoid function

---

## 📊 Sample Metrics

| Metric     | Value |
|------------|-------|
| Precision  | 0.97  |
| Recall     | 0.93  |
| ROC-AUC    | 0.99  |

---

## 🧠 Learnings

- Binary classification fundamentals  
- Sigmoid function & logistic output  
- Evaluation metrics (Precision, Recall, AUC)  
- Threshold tuning impact

---

## ▶️ Run This Project

```bash
pip install pandas numpy matplotlib scikit-learn
