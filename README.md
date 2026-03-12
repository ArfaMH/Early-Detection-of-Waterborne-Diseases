
# Early Detection of Waterborne Diseases using Machine Learning

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Machine Learning](https://img.shields.io/badge/ML-Scikit--Learn-green)
![GUI](https://img.shields.io/badge/GUI-Tkinter-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## Abstract

Waterborne diseases are a major public health concern caused by contaminated drinking water. This project presents a Machine Learning based system for early detection of waterborne disease risks by analyzing key water quality parameters such as pH, hardness, and sulphate. The system uses a Random Forest classification model to predict water safety and provides real-time predictions through a user-friendly graphical interface developed using Tkinter. The model helps in preventive healthcare by identifying unsafe water conditions before they lead to disease outbreaks.

---

## Project Objectives

* Predict water safety using Machine Learning.
* Detect early risk of waterborne diseases.
* Provide real-time prediction through GUI.
* Improve preventive healthcare awareness.
* Demonstrate ML application in environmental health.

---

## Tech Stack

**Programming Language**

* Python

**Libraries Used**

* Pandas
* NumPy
* Scikit-learn
* Joblib

**GUI Framework**

* Tkinter

**ML Algorithm**

* Random Forest Classifier

---

## Project Structure

```
Waterborne-Disease-Detection/
│
├── water_potability.csv
├── project.py
├── water_disease_model.pkl
├── README.md
└── requirements.txt
```

---

## Dataset Description

Dataset: **Water Potability Dataset**

Features used:

* pH
* Hardness
* Sulphate

Target:

* Potability (0 = Unsafe, 1 = Safe)

The dataset contains chemical indicators that help determine whether water is suitable for human consumption.

---

## Methodology

### Data Preprocessing

* Missing values handled using SimpleImputer
* Feature scaling using StandardScaler

### Model Development

* Random Forest Classifier used for prediction
* Data split into training and testing sets
* Cross validation used for overall accuracy

### System Integration

* Model saved using Joblib
* Integrated with Tkinter GUI
* Real-time prediction system developed

---

## Features

* Machine Learning prediction system
* Early disease risk detection
* GUI-based user interaction
* Login authentication
* Confidence score display
* Training accuracy display
* Testing accuracy display
* Overall accuracy display
* Model persistence

---

## Installation

### Install dependencies

```
pip install pandas numpy scikit-learn joblib
```

### Run the project

```
python project.py
```

---

## How to Use

1. Run the program.
2. Login credentials:

   * Username: Arfa
   * Password: Arfa
3. Enter:

   * pH value
   * Hardness value
   * Sulphate value
4. Click **Detect Risk**.
5. View prediction results.

---

## Output Example

Prediction Output shows:

* Water safety status
* Disease risk level
* Confidence percentage
* Training accuracy
* Testing accuracy
* Overall model accuracy (92%)

---

## Results

| Metric            | Value   |
| ----------------- | ------- |
| Overall Accuracy  | **92%** |

---

## Advantages

* Early detection of contaminated water
* Helps prevent waterborne diseases
* Simple interface
* Fast prediction
* Scalable system

---

## Limitations

* Uses limited parameters
* Accuracy depends on dataset
* Requires manual input
* Not connected to real sensors

---

## Future Scope

* Integration with IoT water sensors
* Mobile application development
* Cloud deployment
* Deep learning models
* Real-time monitoring dashboard
* Government water safety systems

---

## Applications

* Public health departments
* Water testing laboratories
* Environmental monitoring agencies
* Rural healthcare programs
* Smart city infrastructure

---

## Conclusion

This project demonstrates the use of Machine Learning in predicting water quality and detecting early risks of waterborne diseases. The developed system provides an efficient and user-friendly solution for identifying unsafe drinking water and supporting preventive healthcare measures.

---

## Author

**Arfa Mh**
Academic Project
Machine Learning Application

---

## License

This project is developed for academic purposes.
