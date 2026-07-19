# Rising Waters: A Machine Learning Approach to Flood Prediction

**Rising Waters** is an intelligent flood risk prediction system.

---

## 👥 Team & Collaboration

* **Team Leader**: Doppalapudi Mohana Raghavendra
* **Team Members**:
  * Moparthi Poornima
  * Kobbari Venkata Pravalika
  * Kamatham Naga Malleswari

> 📝 **Collaboration Note**: This project represents a collective team effort with active contributions from all members. Due to technical integration and code generation challenges during development, the consolidated codebase was compiled and submitted from this single repository.

---

## 📹 Project Demo Video

* **Google Drive Link**: [Rising Waters - Project Demonstration Video](https://drive.google.com/file/d/1ujeX-6Zf3CdJc20LG7rHp_8FUAYc38Fm/view?usp=drive_link)

---

## 🌊 Project Workflow & Architecture

1. **Data Collection & Synthesis**
2. **Preprocessing & Model Pipeline**
3. **Flask Web Dashboard**

---

## 🛠️ Data Pre-Processing & Pipeline

* **Handling Missing Values**
* **Outlier Capping**
* **Categorical Encoding**
* **Feature Scaling**
* **Stratified Split**

---

## 📊 Model Evaluation & Metrics

| Model Architecture | Accuracy |
| :--- | :---: |
| **Decision Tree** | 95.86% |
| **Random Forest** | 96.90% |
| **K-Nearest Neighbors (KNN)** | 93.79% |
| **XGBoost** | **96.55%** |

---

## 💻 Flask Web Application Pages

* **Home Page**
* **Prediction Input Page**
* **Flood Chance Result Page**
* **No Flood Chance Result Page**

---

## 🚀 Installation & Local Execution

### 1. Prerequisites
Ensure you have Python 3.8+ installed.

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Generate Dataset & Train Models
```bash
python generate_dataset.py
python train_models.py
```

### 4. Launch the Web Application
```bash
python app.py
```
Open [http://127.0.0.1:5000](http://127.0.0.1:5000) in your web browser.

---

## 📁 Repository Structure
```
├── document/
│   └── Rising_Waters_Project_Report.pdf
├── video_demo/
├── project files/
│   ├── data/
│   │   └── flood_data.csv
│   ├── plots/
│   │   ├── box_plots.png
│   │   ├── correlation_heatmap.png
│   │   └── distribution_plots.png
│   ├── static/
│   │   ├── css/
│   │   │   └── style.css
│   │   └── js/
│   │       └── script.js
│   ├── templates/
│   │   ├── index.html
│   │   ├── predict_input.html
│   │   ├── result_flood.html
│   │   └── result_no_flood.html
│   ├── app.py
│   ├── generate_dataset.py
│   ├── train_models.py
│   ├── test_app.py
│   ├── requirements.txt
│   └── floods.save
```
