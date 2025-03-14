# **Project Chronic Heart Failure Detection**

## **Project Overview**
Chronic heart failure is a serious condition affecting many lives worldwide. The aim of this project is to assist in early detection of heart abnormalities using machine learning and deep learning techniques. The system analyzes heart sound datasets to predict whether a person's heart condition is **normal** or **abnormal**.

## **Purpose**
- Provide an automated system for detecting chronic heart failure.
- Analyze heart sound data to determine whether the heart condition is normal or abnormal.
- Improve diagnostic accuracy by combining machine learning (ML) and deep learning (DL) models.
- Assist healthcare professionals in early detection and decision-making.

## **Features**
- **Dataset Handling:** Uses heart sound datasets from **PhysioNet**.
- **Data Preprocessing:** Extracts **systolic and diastolic** features from heart sound recordings.
- **Machine Learning Model:** Uses **Random Forest** to analyze extracted features.
- **Deep Learning Model:** Trains on raw features using an **end-to-end deep learning** approach.
- **Hybrid Model:** Combines ML and DL features and retrains with an additional classifier for improved accuracy.
- **Prediction Module:** Upload heart sound files and classify them as **normal** or **abnormal**.
- **Performance Metrics:** Displays accuracy, sensitivity, and specificity of different models.

## **Technology Stack**
- **Programming Language:** Python
- **Libraries Used:**
  - NumPy
  - Pandas
  - Sci-kit Learn
  - TensorFlow/Keras
  - Matplotlib
- **Dataset Source:** PhysioNet (PCG signals and heart sound recordings)

## **How It Works**
1. **Upload Dataset:** Load the heart sound dataset from PhysioNet.
2. **Data Preprocessing:** Extract systolic and diastolic features from heart sound recordings.
3. **Train ML Model:** Train a **Random Forest** model on extracted features.
4. **Train DL Model:** Train a **deep learning model** on raw features.
5. **Hybrid Model Training:** Combine ML and DL features and retrain with a final classifier.
6. **Make Predictions:** Upload a heart sound file, and the system classifies it as **normal** or **abnormal**.

## **Screenshots / UI Preview**
![Screenshot 1](https://github.com/user-attachments/assets/15e15cd1-9b06-4246-a8c6-21005c5de42d)

## **Future Enhancements**
- Improve accuracy using additional feature extraction techniques.
- Implement real-time heart sound analysis.
- Develop a mobile or web-based interface for easy accessibility.
- Integrate with medical devices for real-time patient monitoring.

This project is a step toward automated medical diagnosis, assisting doctors in early detection and reducing fatalities due to chronic heart failure.

