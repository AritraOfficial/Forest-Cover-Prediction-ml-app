# 🌲 Forest Cover Type Prediction ML App

Predict forest cover types using a machine learning model trained on cartographic features. This application enables users to input geographical data and receive real-time forest type predictions through a modern, interactive Gradio web interface.

---

## 📌 Project Overview

This project utilizes supervised learning to predict the forest cover type of a 30m x 30m land patch using cartographic attributes. The dataset is derived from the Roosevelt National Forest in northern Colorado. It includes elevation, slope, aspect, soil type, wilderness area, and hillshade indices.

---

## 🎯 Goal

- Build a robust **Random Forest Classifier** to accurately predict one of **7 forest cover types**.
- Deploy a user-friendly web app using **Gradio** for interactive predictions.
- Ensure the application is modular, maintainable, and easy to use.

---

## 📊 Dataset Information

**Source**: UCI Machine Learning Repository – [Forest CoverType Dataset](https://archive.ics.uci.edu/ml/datasets/covertype)  | I used here the gives dataset by Company.
**Size**: ~581,000 records  
**Features**:
- Numerical: `Elevation`, `Aspect`, `Slope`, `Hydrology distances`, `Road/Fire distances`, `Hillshade (3 times)`
- Categorical (one-hot encoded):
  - 4 Wilderness Areas
  - 40 Soil Types  
**Target**: Forest Cover Type (7 classes)

| Cover Type | Class Name         |
|------------|--------------------|
| 1          | Spruce/Fir         |
| 2          | Lodgepole Pine     |
| 3          | Ponderosa Pine     |
| 4          | Cottonwood/Willow  |
| 5          | Aspen              |
| 6          | Douglas-fir        |
| 7          | Krummholz          |

---

## ⚙️ Tech Stack

| Tool/Library   | Purpose                                  |
|----------------|-------------------------------------------|
| Python         | Core programming language                 |
| scikit-learn   | Model training using Random Forest        |
| joblib         | Model serialization                       |
| numpy          | Data preprocessing                        |
| gradio         | Web application interface                 |
| Jupyter/VS Code| Development and model experimentation     |

---

## 🔁 Project Workflow
![Flowchart diagram](https://github.com/user-attachments/assets/0ab21eff-5959-4a9d-97ab-c8f50ea7189b)

---

## 🚀 How to Run the Project

1. **Clone the Repository**

   ```bash
   git clone https://github.com/AritraOfficial/Forest-Cover-Prediction-ml-app.git
   cd Forest-Cover-Prediction-ml-app
   ```

2. **Create and Activate Virtual Environment**

   ```bash
   python -m venv forestenv
   source forestenv/bin/activate  # or `forestenv\Scripts\activate` on Windows
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Launch the Gradio App**

   ```bash
   python app.py
   ```

---

## 📷 UI Preview

![APP](https://github.com/user-attachments/assets/44f0803a-a8de-402a-aa48-f5f88450e496)

*Enter elevation, slope, distances, select wilderness & soil type, and get the predicted forest cover type.*

---
## 📄 License

This project is licensed under the **MIT License**. See `LICENSE` for details.

---

## 🙌 Acknowledgements

* UCI ML Repository for the dataset
* Gradio for the rapid prototyping interface
* Scikit-learn for model building

---

## 📧 Contact 
For queries or collaborations, feel free to connect:  
<p align="center">
  <a href="https://www.linkedin.com/in/aritramukherjeeofficial/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://x.com/AritraMofficial" target="_blank">
    <img src="https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter">
  </a>
  <a href="https://www.instagram.com/aritramukherjee_official/?__pwa=1" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
  </a>
  <a href="https://leetcode.com/u/aritram_official/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-%23FFA116.svg?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode">
  </a>
  <a href="https://github.com/AritraOfficial" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-%23181717.svg?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://discord.com/channels/@me" target="_blank">
    <img src="https://img.shields.io/badge/Discord-%237289DA.svg?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
  </a>
  <a href="mailto:aritra.work.official@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-%23D14836.svg?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---
