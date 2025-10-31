# 🌾 Crop Recommendation System using K-Means Clustering

🚀 **Mini Project Showcase:** Crop Prediction Using Unsupervised Machine Learning  

---

## 📌 Project Overview

This project demonstrates the power of **Unsupervised Machine Learning** by using the **K-Means Clustering** algorithm to recommend the most suitable crop based on soil and environmental conditions.  
Unlike supervised models, this system works **without any predefined labels**, grouping similar data points intelligently using clustering.

---

## 🎯 Core Objective

To apply **K-Means Clustering** on agricultural data and build a recommendation system that:
- Groups crops based on environmental and soil characteristics.
- Suggests the most suitable crop for given input conditions.

---

## 🧠 Machine Learning Highlights

| Component | Description |
|------------|--------------|
| **Algorithm Used** | K-Means (from scikit-learn) |
| **Cluster Optimization** | Tuned using Silhouette Score & Elbow Method |
| **Dataset Features** | Nitrogen (N), Phosphorus (P), Potassium (K), Temperature, Humidity, pH, Rainfall |
| **Model Export** | Saved using `joblib` for integration with Flask app |

---

## 🧪 ML Pipeline

1. **Data Preprocessing** – Handling missing values, normalization, and feature scaling.  
2. **Exploratory Data Analysis (EDA)** – Visualization using pairplots and heatmaps.  
3. **Clustering Model** – Applied K-Means to identify optimal clusters.  
4. **Model Evaluation** – Used Silhouette Score and visual plots for validation.  
5. **Model Exporting** – Saved trained model using `joblib` for reuse.  

---

## 💻 Flask Web Application

To demonstrate the ML model, a **Flask-based web app** was developed that allows real-time predictions through a simple user interface.

### 🔧 Features:
- User inputs soil/environmental parameters via a web form.
- Predicts the most suitable crop cluster.
- Displays **recommended crop name**, **similarity score**, and **actual crop image**.
- Static image hosting via Flask’s `static` directory.

### 🧩 Tech Stack:
- **Backend:** Flask, Python  
- **Frontend:** HTML, CSS, Jinja2 Templates, JavaScript  
- **Machine Learning:** scikit-learn, pandas, numpy, seaborn, matplotlib  

---

## 📁 Project Structure

```
Crop_Recommendation_System/
│
├── model_training/
│   └── crop_kmeans.ipynb        # Model training & experimentation notebook
│
├── model/
│   └── crop_model.joblib        # Trained model file
│
├── app.py                       # Flask web app
│
├── templates/
│   └── index.html               # Frontend UI template
│
├── static/
│   └── images/                  # Crop images used in UI
│
├── requirements.txt             # Python dependencies
│
└── README.md                    # Project documentation
```

---

## ⚙️ Installation & Usage

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/Crop-Recommendation-KMeans.git
cd Crop-Recommendation-KMeans
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

If `requirements.txt` is not available, you can manually install all dependencies:
```bash
pip install flask scikit-learn pandas numpy seaborn matplotlib joblib
```

### 3️⃣ Run the Flask app
```bash
python app.py
```

### 4️⃣ Open in browser
Visit [http://127.0.0.1:5000/](http://127.0.0.1:5000/) and enter input values to get real-time crop recommendations.

---

## 📦 requirements.txt

In case you don’t already have this file, here’s the content you can directly copy:

```
flask
scikit-learn
pandas
numpy
seaborn
matplotlib
joblib
```

---

## 🌟 Skills Strengthened

- 🧩 Unsupervised Learning (K-Means Clustering)  
- 🧹 Data Cleaning & EDA  
- 🧠 Model Evaluation & Exporting  
- 🌐 Web Integration (Flask)  
- 🧰 Full-stack ML Deployment Workflow  

---

## 🔗 Source Code

Complete Source Code: [Click Here]([https://lnkd.in/eDadVVUF]))

---

## 📜 License

This project is open-source and available for educational use under the **MIT License**.

---

## ✨ Author

**Pushpendra Tiwari**  
🎓 B.Tech  
📧 your-pushpt109@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/ptCStiwari) | [GitHub](https://github.com/ptCStiwari)
