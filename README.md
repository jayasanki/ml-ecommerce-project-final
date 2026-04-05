# 🛒 Production-Grade E-Commerce Analytics and MLOps System

## 👤 Student Information

* **Student Name:** M.A. Nethranjali Jayasanki
* **Student ID:** 2301691109
* **GCP Project ID:** *(Add your project ID here)*
* **Slack Handle:** *(Optional)*

---

## 📌 Project Description

This project is developed as part of the **ITS 2140: Machine Learning (Semester 4)** module.
The objective is to design and implement a **production-grade machine learning system** for an e-commerce platform (AuraCart).

The system performs three main tasks:

* 📈 **Regression** – Predict order price
* 🧠 **Classification** – Predict customer segments & delivery status
* 🔍 **Clustering** – Discover customer behavior patterns

Finally, the best-performing **customer segment classification model** is deployed as a **live prediction API using Google Vertex AI**.

---

## ⚙️ Technology Stack

* **Programming Language:** Python
* **Libraries:**

  * pandas
  * numpy
  * scikit-learn
  * joblib
  * matplotlib / seaborn
* **Tools:**

  * Jupyter Notebook
  * MLflow (Experiment Tracking)
* **Cloud Platform:**

  * Google Cloud Platform (GCP)
  * Google Cloud Storage
  * Vertex AI

---

## 📁 Project Structure

```
ml-ecommerce-project-final/
│
├── artifacts/
│   ├── model.joblib
│   └── requirements.txt
│
├── data/
│   ├── cleaned_data.csv
│   └── ecommerce_data.csv
│
└── notebooks/
    ├── 1_eda_and_preprocessing.ipynb
    ├── 2_supervised_modeling.ipynb
    ├── 3_unsupervised_clustering.ipynb
    └── 4_mlops_deployment.ipynb
```

---

## 🚀 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
```

### 2. Install Dependencies

```bash
pip install -r artifacts/requirements.txt
```

### 3. Run Notebooks

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run notebooks in order:

1. `1_eda_and_preprocessing.ipynb`
2. `2_supervised_modeling.ipynb`
3. `3_unsupervised_clustering.ipynb`
4. `4_mlops_deployment.ipynb`

---

## 🤖 Model Deployment (Vertex AI)

The final model (`model.joblib`) is deployed using **Google Vertex AI**.

### Deployment Steps:

1. Upload artifacts to **Google Cloud Storage**
2. Import model into **Vertex AI Model Registry**
3. Deploy to an **Endpoint**
4. Test using JSON request

---

## 🔗 Live Application URL

*(Add your deployed frontend URL if available)*

---

## 📡 API Example Request

```json
{
  "instances": [
    {
      "category": "Electronics",
      "quantity": 2,
      "payment_method": "Credit Card",
      "device_type": "Mobile",
      "channel": "Email"
    }
  ]
}
```

---

## 📊 Key Features

* End-to-end ML pipeline
* MLflow experiment tracking
* Hyperparameter tuning
* Customer segmentation analysis
* Production-ready deployment
* Real-time prediction API

---

## 📸 Screenshots (Add these)

* GCS Bucket Upload
* Vertex AI Model
* Deployed Endpoint
* Prediction Result

---

## 📝 Conclusion

This project demonstrates the complete lifecycle of a machine learning system, from **data preprocessing and modeling to deployment and real-time inference** using cloud infrastructure.

---

## 🔮 Future Improvements

* Add real-time streaming data
* Improve model performance with advanced algorithms
* Implement CI/CD for ML pipelines
* Add monitoring and logging

---
