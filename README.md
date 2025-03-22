
## Author
- **Name**: Shahd Hatem Abd Elgalil
- **ID**: 4211235

# Human Activity Recognition (HAR) using Deep Learning

## Project Overview
This project focuses on Human Activity Recognition (HAR) using deep learning models. The goal is to classify human activities such as walking, sitting, standing, etc., based on sensor data from accelerometers and gyroscopes. The dataset used is the **UCI HAR Dataset**, which contains time-series data collected from smartphones.

Three deep learning models were implemented and evaluated:
1. **LSTM Model**
2. **CNN Model**
3. **CNN-LSTM Hybrid Model**

The best-performing model achieved an accuracy of **90.87%** on the test set.

---

## Project Structure
- **Data Loading and Preprocessing**: The dataset is loaded, preprocessed, and split into training and testing sets.
- **Model Training**: Three deep learning models are trained using Keras and TensorFlow.
- **Evaluation**: The models are evaluated using metrics such as accuracy, confusion matrix, and ROC curves.
- **Visualization**: Results are visualized using Matplotlib and Seaborn.

---

## Requirements
To run this project, you need the following Python libraries:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow/Keras

You can install the required libraries using:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
```

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/human-activity-recognition.git
   cd human-activity-recognition
   ```
2. Download the [UCI HAR Dataset](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones) and place it in the `data` directory.
3. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook HAR_Project.ipynb
   ```
   or
   ```bash
   python HAR_Project.py
   ```

---

## Results
- **Best Model**: CNN-LSTM Hybrid Model
- **Test Accuracy**: 90.87%
- **Confusion Matrix**
- **ROC Curve**

---
