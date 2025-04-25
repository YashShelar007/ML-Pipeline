# 🧠 ML Pipeline – End-to-End Machine Learning Deployment System

A complete machine learning operations (MLOps) workflow including training, versioning, packaging, and deploying ML models with Docker, DVC, and FastAPI.

### 🔗 GitHub Repo: https://github.com/YashShelar007/ML-Pipeline

---

## 📍 Problem It Solves

Most ML projects fail in deployment due to lack of structure and reproducibility. This project provides a template to automate and productionize ML workflows from start to finish.

---

## ✨ Key Features

- ✅ Modular training and prediction pipeline
- ✅ Data & model versioning using DVC
- ✅ Dockerized for seamless deployment
- ✅ CI-ready structure for GitHub Actions
- ✅ YAML-based configuration for reproducibility

---

## 🛠 Tech Stack

- **ML & Data**: Scikit-learn, Pandas, NumPy
- **Serving**: FastAPI
- **Versioning**: DVC, Git
- **Deployment**: Docker
- **Automation**: GitHub Actions, `params.yaml`, CLI scripts

---

## 🧠 Architecture

```
[CLI / Main.py]
       ↓
[Data Ingestion] → [Training] → [Model Evaluation]
       ↓                  ↓
    [Artifacts]       [scores.json, models/]
       ↓
 [DVC + Git Tracking]
```

---

## 🚀 Getting Started

```bash
# 1. Clone the repo
git clone https://github.com/YashShelar007/ML-Pipeline.git
cd ML-Pipeline-main

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run training pipeline
python main.py

# 4. Launch API (if applicable)
uvicorn app:app --reload
```

---

## 🧩 Future Enhancements

- 📦 Add MLflow for experiment tracking
- 🔍 Integrate S3/remote storage into DVC
- 📊 Build UI for model performance visualization
- 🤖 Add automated model retraining hooks

---

## 📸 Optional Screenshots

- Diagrams: DVC flow, artifact structure, training CLI demo
- Output logs, FastAPI Swagger UI

---

## 👨‍💻 Author

**Yash Shelar**  
Portfolio: [yashshelar.com](https://yashshelar.com)  
LinkedIn: [linkedin.com/in/shelar-yash](https://linkedin.com/in/shelar-yash)
