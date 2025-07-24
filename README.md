# 🧠 PredMath – Student Math Score Predictor

PredMath is a production-ready machine learning pipeline designed to predict students' math scores based on demographic and academic inputs.

This project demonstrates a complete industry-level ML lifecycle—from data ingestion to model deployment—implemented using best practices like modular programming, custom exception handling, logging, and CI/CD with Docker and AWS.

---

<img width="1918" height="929" alt="image" src="https://github.com/user-attachments/assets/77bed204-bf80-4dbf-a5eb-14341f75970f" />

## 🚀 Tech Stack

- **ML Models**: Linear Regression, Random Forest, XGBoost (GridSearchCV used for tuning)
- **Data Pipeline**: Custom modules for ingestion, transformation, training, and prediction
- **Web Framework**: Flask
- **Containerization**: Docker
- **CI/CD**: GitHub Actions
- **Cloud**: AWS EC2 & ECR
- **Logging**: Python logging module
- **Exception Handling**: Custom classes for clean error tracing

---

## 📁 Project Structure
PredMath/
│ ├── artifacts/
│ ├── catboost_info/
│ ├── notebook/data # Jupyter notebook for EDA and data visualizations 
├── src/
│ ├── components/ # Data ingestion, transformation, model trainer
│ ├── pipeline/ # Training and prediction pipelines
│ ├── exception.py # Custom exceptions
│ ├── logger.py # Custom logger
│ └── utils.py # Utility functions
├── templates
├── application.py # Flask app
├── Dockerfile # Container config
├── .dockerignore
├── .gitignore
├── .github/workflows/ # CI/CD GitHub Action YAML
├── docker-compose.yml
└── requirements.txt
├── setup.py

---

## 🧪 How to Run Locally

```bash
# Step 1: Clone the repo
git clone https://github.com/Prithvi371/PredMath.git
cd PredMath

# Step 2: Create a virtual environment and install dependencies
pip install -r requirements.txt

# Step 3: Run the Flask app
python application.py


<img width="1918" height="929" alt="image" src="https://github.com/user-attachments/assets/77bed204-bf80-4dbf-a5eb-14341f75970f" />
