

# 🧬 Breast Cancer Prediction using Machine Learning

## 📌 Overview

This project focuses on predicting whether a tumor is **malignant (cancerous)** or **benign (non-cancerous)** using Machine Learning techniques. The model is trained on a dataset containing various medical features related to breast cancer diagnosis.

The goal is to assist in early detection and improve decision-making in the healthcare domain.

---

## 🚀 Features

* 📊 Data preprocessing and cleaning
* 🔍 Exploratory Data Analysis (EDA)
* 🤖 Machine Learning model training
* 🏆 Best model selection and saving
* 📈 Visualization using Matplotlib & Seaborn
* 💾 Model deployment-ready (`.pkl` file included)

---

## 📂 Project Structure

```
Breast Cancer Prediction (ML)/
│
├── Dataset.csv                         # Dataset used for training
├── Breast_Cancer_Prediction.ipynb     # Jupyter Notebook (main code)
├── best_model_name.pkl                # Trained ML model
├── Breast_Cancer_Prediction.pdf       # Project documentation
├── app.pdf                            # Application overview
├── Outcome.mp4                        # Output/demo video
├── Capture.jpg                        # Screenshot of output
└── .ipynb_checkpoints/                # Notebook checkpoints
```

---

## 📊 Dataset

* The dataset contains features such as:

  * Radius, Texture, Perimeter, Area
  * Smoothness, Compactness, Concavity
  * Symmetry, Fractal Dimension, etc.

* Target Variable:

  * `M` → Malignant (0)
  * `B` → Benign (1)

---

## ⚙️ Technologies Used

* 🐍 Python
* 📦 NumPy, Pandas
* 📊 Matplotlib, Seaborn
* 🤖 Scikit-learn
* 📓 Jupyter Notebook

---

## 🔬 Workflow

1. **Data Loading**

   * Import dataset using Pandas

2. **Data Cleaning**

   * Removed unnecessary columns (e.g., `id`)
   * Handled missing values

3. **Data Transformation**

   * Converted categorical values into numerical

4. **Exploratory Data Analysis (EDA)**

   * Statistical summary
   * Visualization of features

5. **Model Building**

   * Trained multiple ML models
   * Evaluated performance

6. **Model Selection**

   * Selected best-performing model
   * Saved as `.pkl` file

---

## 📈 Results

* Successfully classified tumors as **Malignant or Benign**
* Achieved high accuracy using optimized ML model
* Ready for integration into real-world applications

---

## ▶️ How to Run

### 🔧 Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/breast-cancer-prediction.git
cd breast-cancer-prediction
```

### 📦 Step 2: Install Requirements

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### ▶️ Step 3: Run Notebook

```bash
jupyter notebook
```

---

## 📌 Future Improvements

* 🌐 Deploy as a web app using Flask/Streamlit
* 📱 Create a user-friendly UI
* 📊 Improve model accuracy with advanced algorithms
* 🔍 Add real-time prediction support

---

## 🎥 Demo

* Check `Outcome.mp4` for project output
* Refer to `Capture.jpg` for UI preview

---

## 📄 Documentation

* Detailed explanation available in:

  * `Breast_Cancer_Prediction.pdf`
  * `app.pdf`


✨ *This project demonstrates the power of Machine Learning in healthcare and early disease detection.*
