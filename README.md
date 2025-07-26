# 🧠 DermaDiagnosis AI

 *Explainable Machine Learning for Skin Disease Prediction*


## 📌 Overview

**DermaDiagnosis AI** is an interpretable machine learning system that predicts six common dermatological conditions based on patient symptoms — and *explains* how it reached the decision.

Built with a strong focus on **explainability**, this tool uses **SHAP** to highlight which symptoms influenced the model’s prediction most. It’s an early prototype of a larger vision: a scalable, AI-driven medical diagnostic platform.


Due to the lack of large, diverse medical datasets, this version is focused on **dermatology**, but the modular backend is designed to adapt to more complex multi-system medical data.

---

## 🔍 Features

* ✅ Disease classification using **XGBoost**
* 📊 Human-readable **SHAP explanations**
* 💬 Clean, formatted output for top predicted diseases
* 📦 Ready for scaling into a full diagnostic engine

---

## 📂 Dataset Details

| Field    | Description                    |
| -------- | ------------------------------ |
| Rows     | \~500                          |
| Features | 34 binary symptoms             |
| Labels   | 6 dermatological diseases      |
| Source   | Public dataset (symptom-based) |

### Target Classes:

* Psoriasis
* Seborrheic Dermatitis
* Lichen Planus
* Pityriasis Rosea
* Chronic Dermatitis
* PRP (Pityriasis Rubra Pilaris)

---

## 🛠 Tech Stack

| Category      | Tools / Libraries                       |
| ------------- | --------------------------------------- |
| ML Algorithms | `XGBoost`, `scikit-learn`               |
| Data Handling | `pandas`, `numpy`                       |
| XAI           | `SHAP`                                  |
| Visualization | `matplotlib`, `seaborn`                 |
| Evaluation    | `Accuracy`, `Confusion Matrix`, `Calibration` |
| Dev Platform  | `Jupyter`           |

---

## 🚀 Getting Started

### 1. Clone Repo

```bash
git clone https://github.com/yourusername/derma-diagnosis-ai.git
cd derma-diagnosis-ai
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

Open `DermaDiagnosis.ipynb` and follow along with the code.

---

## 🧪 Example Output

```
Prediction:
🧪 psoriasis: 71%
🧪 seborrheic dermatitis: 39%
🟢 prp: 12%

Explanation (Top SHAP factors):
✔️ scaling (+0.26)
❌ itching (+0.19)
✔️ follicular papules (+0.13)
❌ family history (–0.11)
```

---

## 📽️ Coming Soon

* 🎥 A **video walkthrough** (dataset + model + SHAP) will be posted on YouTube soon!
* 🌐 Plan to **expand to a multi-disease model** covering internal medicine, using a larger dataset
* 💡 Idea submitted to **Startup Nation Olympiad**

---

## ✨ Future Scope

* Expand dataset to **vitals**, **lab tests**, and **other systems**
* Integrate with **real-time IIoT sensors** for monitoring
* Wrap into a **mobile/web app for clinical deployment**
* Work on **multilingual symptom input** for accessibility

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss what you’d like to change.
If you have access to a **larger clinical dataset**, feel free to collaborate!

---

## 📜 License

MIT © Aryan – 2025
For educational and research use only. Not for clinical deployment.


