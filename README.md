# 🌱 Plant Disease Detection Using Machine Learning

## 📌 Project Overview

This project is a machine learning-based plant disease detection system that identifies diseases in potato leaves using image processing techniques and classification algorithms. The system uses images of healthy and diseased potato leaves to train machine learning models and predict the disease present in newly uploaded images.

The project compares the performance of **Logistic Regression** and **Support Vector Machine (SVM)** algorithms and selects the best-performing model based on accuracy.

---

## 🚀 Features

* Extracts dataset automatically from ZIP file.
* Visualizes sample training images.
* Performs image preprocessing and normalization.
* Encodes class labels using Label Encoding.
* Trains and evaluates:

  * Logistic Regression
  * Support Vector Machine (SVM)
* Displays confusion matrices for model evaluation.
* Predicts disease from a custom uploaded image.
* Provides treatment suggestions based on predicted disease.
* Compares model performance using accuracy scores.

---

## 📂 Dataset Structure

```
Plant_Disease_Workshop/
│
├── train/
│   ├── Potato___Early_blight/
│   ├── Potato___Late_blight/
│   └── Potato___healthy/
│
└── val/
    ├── Potato___Early_blight/
    ├── Potato___Late_blight/
    └── Potato___healthy/
```

---

## 🛠 Technologies Used

* Python
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Google Colab

---

## 📚 Machine Learning Models

### 1. Logistic Regression

* Used for multiclass classification.
* Evaluated using accuracy score and confusion matrix.

### 2. Support Vector Machine (SVM)

* Linear kernel SVM classifier.
* Compared with Logistic Regression to identify the best model.

---

## 🔄 Workflow

1. Extract dataset from ZIP file.
2. Load and visualize images.
3. Resize images to 64 × 64 pixels.
4. Convert images into numerical arrays.
5. Normalize pixel values.
6. Encode labels using LabelEncoder.
7. Train Logistic Regression model.
8. Train SVM model.
9. Evaluate both models using accuracy and confusion matrices.
10. Upload custom image for disease prediction.
11. Display disease name and treatment recommendation.

---

## 📊 Evaluation Metrics

The project uses the following evaluation metrics:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Model Comparison Chart

---

## 🌿 Disease Prediction and Recommendations

### Potato Early Blight

**Recommendation:**

* Remove infected leaves.
* Apply appropriate fungicide.
* Maintain proper field sanitation.

### Potato Late Blight

**Recommendation:**

* Remove infected leaves immediately.
* Apply fungicide treatment.
* Avoid excessive moisture around plants.

### Healthy Plant

**Recommendation:**

* No action required.
* Continue regular monitoring and maintenance.

---

## ▶️ How to Run the Project

### Step 1: Upload Dataset

Upload the dataset ZIP file:

```
Plant_Disease_Workshop.zip
```

### Step 2: Run the Notebook

Execute all cells in Google Colab or Jupyter Notebook.

### Step 3: Upload Test Image

After model training is completed, upload a potato leaf image for prediction.

### Step 4: View Prediction

The system will display:

* Predicted disease name
* Recommended treatment

---

## 📈 Model Comparison

The project compares:

* Logistic Regression Accuracy
* Support Vector Machine Accuracy

The model with the highest accuracy is selected as the best model.

---

## 🎯 Applications

* Smart Agriculture
* Precision Farming
* Crop Health Monitoring
* Early Disease Detection
* Agricultural Research

---

## 👩‍💻 Author

**Akshata Meleyyannavar**
Bachelor of Computer Applications (BCA) Student
KLE College

---

## 📜 License

This project is developed for educational and research purposes.

https://www.kaggle.com/datasets/mohitsingh1804/plantvillage?utm_source=chatgpt.com
