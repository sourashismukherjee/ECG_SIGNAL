 🫀 Intelligent ECG Abnormality Detection

👤 Author: Sourashis Mukherjee

 📖 Project Overview

This project is a **Machine Learning-based ECG Abnormality Detection System** that classifies ECG heartbeats into different categories using the **MIT-BIH Arrhythmia Database**.

🎯 Objectives

1. Classify ECG heartbeats using Machine Learning
2. Process ECG signals and annotations
3. Handle imbalanced ECG classes
4. Evaluate model performance using multiple metrics

 ⚙️ Features

1. ECG signal processing
2. Heartbeat extraction
3. ECG annotation mapping
4. Multiclass classification
5. Model evaluation and performance analysis

 🧠 Machine Learning

**Random Forest Classifier**

* Multiclass ECG classification
* `class_weight="balanced"` for imbalanced classes
* Group-based train/test splitting using `GroupShuffleSplit`

 🏷️ ECG Classes

* **N** – Normal Beat
* **S** – Supraventricular Beat
* **V** – Ventricular Beat
* **F** – Fusion Beat
* **Q** – Unknown/Other Beat

 🔍 Data Processing

1. Load ECG records from MIT-BIH
2. Read ECG annotations
3. Extract heartbeat segments
4. Map annotation symbols to classes
5. Prepare features for Machine Learning
6. Split data into training and testing sets

 📊 Model Evaluation

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* WFDB
* Scikit-learn
* Matplotlib

 🚀 Future Improvements

* Use more ECG records
* Improve minority-class performance
* Compare additional ML models
* Explore real-time ECG classification

