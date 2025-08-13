# kmeans-customer-segmentation-mlops

Customer segmentation using K-means clustering with a production-ready MLOps pipeline powered by Airflow, DVC, Vertex AI, MLflow, Docker, and Flask.

## 📌 Overview
This project implements customer segmentation using K-means clustering, orchestrated through an end-to-end MLOps pipeline. It enables:
- **Scalable data processing** with Google Cloud Platform (GCP)
- **Automated model deployment** using Vertex AI
- **Data versioning** via DVC
- **Model tracking and hyperparameter tuning** with MLflow
- **Workflow orchestration** using Apache Airflow
- **Monitoring and analytics** with Looker
- **CI/CD integration** through GitHub Actions
- **Containerized development** with Docker
- **API serving** via Flask

## 🛠 Tech Stack
- **Machine Learning**: Python, scikit-learn (K-means)
- **Orchestration**: Apache Airflow
- **Version Control for Data & Models**: DVC
- **Cloud**: Google Cloud Platform, Vertex AI, Looker
- **Tracking & Experimentation**: MLflow
- **Deployment**: Docker, Flask
- **CI/CD**: GitHub Actions

## 🚀 Pipeline Workflow
1. **Data Ingestion & Preprocessing** – Pull raw customer data, clean, and prepare for modeling.
2. **Feature Engineering** – Create customer attributes for clustering.
3. **Model Training (K-means)** – Train and evaluate segmentation model.
4. **Model Tracking** – Log metrics and parameters with MLflow.
5. **Model Deployment** – Push trained model to Vertex AI for serving.
6. **Monitoring** – Track model performance with Looker dashboards.
7. **Automation** – Airflow schedules the entire workflow.
8. **CI/CD** – GitHub Actions triggers retraining/deployment on updates.

## 📂 Project Structure
