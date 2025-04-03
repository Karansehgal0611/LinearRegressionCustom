# Linear Regression from Scratch

## 📌 Overview
This project demonstrates how to implement **Linear Regression from scratch in Python**, progressing from a basic implementation to an advanced model with **L1 (Lasso) and L2 (Ridge) regularization**. The project is structured into three Jupyter Notebooks, each building upon the previous one.

## 🚀 Notebooks Breakdown
### **1️⃣ Basic Linear Regression** (`Linear_Regression.ipynb`)
- Implements the core logic of **Linear Regression** without using libraries like scikit-learn.
- Uses **Gradient Descent** for optimization.
- Ideal for understanding fundamental concepts.

### **2️⃣ Linear Regression with Dataset** (`Linear_regression1.ipynb`)
- Builds upon the first notebook by applying **Linear Regression on a real dataset**.
- Reads data, preprocesses it, and fits the custom-built model.
- Adds error evaluation using **Mean Squared Error (MSE)** and **R² Score**.

### **3️⃣ Advanced Linear Regression with Regularization** (`Linear_Reg_with_Focused.ipynb`)
- Introduces **L1 (Lasso) and L2 (Ridge) Regularization** to prevent overfitting.
- Optimizes the model using **regularized gradient descent**.
- Compares performance with and without regularization.

## 📂 Project Structure
```
Linear-Regression-Custom/
│-- Linear_Regression.ipynb   # Basic LR implementation
│-- Linear_regression1.ipynb# LR with dataset handling
│-- Linear_Reg_with_Focused.ipynb # LR with L1 & L2 Regularization
│-- README.md  # Project documentation
│-- .gitignore  # Ignoring unnecessary files
```

## 📥 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Karansehgal0611/LinearRegressionCustom.git
cd LinearRegressionCustom
```

### 2️⃣ Create a Virtual Environment (Optional) (or Use environment provided)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```


## 🛠️ Usage
1. Open **Jupyter Notebook**
```bash
jupyter notebook
```
2. Navigate to the notebook of interest and **run the cells step by step**.

## 📊 Results & Visualization
- The notebooks visualize predictions, cost function trends, and model improvements.
- Comparison plots show the effect of **L1 & L2 regularization** on the model.


## 🤝 Contributing
Feel free to contribute! Open an issue or submit a pull request.

## 📬 Contact
For queries, reach out at **karansehgal0310@gmail.com** or open an issue on GitHub.

---

⭐ **If you find this project useful, consider giving it a star on GitHub!** ⭐

