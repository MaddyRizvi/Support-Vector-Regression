# Support Vector Regression (SVR) - Salary Prediction

This project implements a **Support Vector Regression (SVR)** model to predict salaries based on position levels using the `Position_Salaries.csv` dataset. It demonstrates key machine learning steps including data preprocessing, feature scaling, model training, prediction, and visualization of results.

## 📊 Overview

The SVR model uses a radial basis function (RBF) kernel to capture non-linear relationships between a candidate’s job position level and the expected salary. The model is trained on a small dataset and uses scaling to improve performance and visualization clarity.

## 🔧 Features

- Data preprocessing using `pandas` and `numpy`
- Feature scaling using `StandardScaler`
- SVR training using an RBF kernel (`sklearn.svm.SVR`)
- Prediction of salary for a given position level (e.g., 6.5)
- Visualization of the model and its predictions

## 🗂 Dataset

The dataset used is `Position_Salaries.csv`, which includes:
- `Position`: Job title
- `Level`: Numerical level of the position
- `Salary`: Corresponding salary

## 📁 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MaddyRizvi/Support-Vector-Regression
   cd Support-Vector-Regression
   ```

2. Install the required libraries (preferably in a virtual environment):
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure the file `Position_Salaries.csv` is in the project directory.

## 📌 Usage

1. Run the script:
   ```bash
   python svr_salary_prediction.py
   ```

2. The script will:
   - Print transformed input and output data
   - Predict the salary for level 6.5
   - Display visualizations of the regression curve

## 📈 Output

- **Numeric prediction** for level 6.5 (inverse-transformed)
- **Graphs**:
  - Basic SVR fit
  - High-resolution SVR curve for better visual accuracy
 
## Screenshots

- # Visualising the SVR results
![Image](https://github.com/user-attachments/assets/cc88f492-14e0-4c26-bc39-165f30195a20)

- # Visualising the SVR results (for higher resolution and smoother curve)
![Image](https://github.com/user-attachments/assets/d80330c7-057c-44ac-88d1-aac66f0ac978)


## 📦 Dependencies

- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

You can install them manually or using:
```bash
pip install numpy pandas matplotlib scikit-learn
```

## 📃 License

This project is open-source and available under the [MIT License](LICENSE).

## 👤 Author

- **Your Name** – [@maddyRizvi]([https://github.com/maddyRizvi](https://github.com/MaddyRizvi/)

## 💬 Feedback

Feel free to open an issue or submit a pull request to improve the code or add more features!
