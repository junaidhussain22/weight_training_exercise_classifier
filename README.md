# 🏋️ Weight Training Exercise Classifier

A machine learning pipeline that classifies weight training exercises using wearable sensor data from accelerometers and gyroscopes. The project performs data preprocessing, feature engineering, model training, and evaluation to accurately recognize different exercises and repetition patterns.

---

## 📌 Project Overview

This project demonstrates an end-to-end machine learning workflow for Human Activity Recognition (HAR) using motion sensor data.

The pipeline includes:

* Data cleaning and preprocessing
* Feature engineering
* Frequency-domain feature extraction
* Temporal feature extraction
* Outlier detection and removal
* Model training and comparison
* Performance evaluation
* Visualization of results

The goal is to classify various strength-training exercises from motion sensor readings collected during workouts.

---

## 📂 Project Structure

```text
exercise_ml/
│
├── data/
│   ├── raw/
│   ├── interim/
│   └── processed/
│
├── reports/
│   └── figures/
│
├── src/
│   ├── data/
│   ├── features/
│   ├── models/
│   └── visualization/
│
├── notebooks/
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🛠 Technologies Used

* Python 3
* Pandas
* NumPy
* Scikit-learn
* SciPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📊 Machine Learning Workflow

### 1. Data Collection

Wearable IMU sensor data containing:

* Accelerometer readings
* Gyroscope readings

representing multiple weight-training exercises.

---

### 2. Data Preprocessing

* Missing value handling
* Data cleaning
* Outlier removal
* Feature normalization

---

### 3. Feature Engineering

The project generates both time-domain and frequency-domain features, including:

* Mean
* Standard deviation
* Rolling statistics
* FFT-based frequency features
* Temporal abstractions
* Repetition counting

---

### 4. Model Training

Multiple supervised learning algorithms are trained and evaluated to identify the best-performing classifier.

Example algorithms include:

* Random Forest
* Decision Tree
* Support Vector Machine
* K-Nearest Neighbors
* Neural Networks (if applicable)

---

### 5. Evaluation

Models are compared using metrics such as:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## 📈 Results

The project compares multiple machine learning models to determine the most accurate classifier for recognizing different weight-training exercises based on wearable sensor signals.

Visualizations and performance plots are available in the `reports/figures` directory.

---

## 🚀 Running the Project

Clone the repository:

```bash
git clone https://github.com/junaidhussain22/weight-training-exercise-classifier.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebooks or execute the training scripts from the `src` directory.

---

## 📷 Example Output

The project produces:

* Confusion matrices
* Feature importance plots
* Accuracy comparisons
* Signal visualizations
* Exercise classification results

---

## 📚 Learning Resources

This project was developed as part of my learning journey in machine learning and human activity recognition.

---

## 👨‍💻 Author

**Junaid Hussain**

Mechanical Engineer | Data Analyst | Machine Learning Enthusiast

GitHub: https://github.com/junaidhussain22

---

## 📄 License

This project is intended for educational and portfolio purposes.
