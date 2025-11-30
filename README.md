# AMS-595_Project6

Author: Prerna Sachdeva  
Course: AMS 595 — Fundamentals of Computing  

This repository contains the full implementation and results for **Project 6**, which includes four problems:

- **Q2:** Gradient Descent on a 1D Function  
- **Q3:** Linear Regression with Two Features  
- **Q4:** Logistic Regression Classification  
- **Q5:** Cat vs Non-Cat Image Classification (Original + Modified Dataset)

The project is organized into **three Jupyter notebooks**, each explained below.

---

## File Descriptions

### **1. Sachdeva_Prerna_Project6.ipynb**
This notebook contains the complete solutions for:

### **Q2 — Gradient Descent on \(f(x) = \sqrt{x^2 + 5}\)**
- Plot of the function  
- Analytical minimum  
- Gradient descent implementation  
- Convergence plots  
- Step-size comparison for \(\alpha = 5, 3, 1, 0.5\)

---

### **Q3 — Linear Regression With Two Features**
- Creation of synthetic dataset  
- Closed-form solution using Normal Equation  
- Learned intercept and weights  
- 3D regression plane plotted over the data  

---

### **Q4 — Logistic Regression (Binary Classification)**
- Dataset construction  
- Logistic regression trained from scratch  
- Gradient descent optimization  
- Training/Test accuracy reports  
- Decision boundary visualization for:
  - Training set  
  - Test set  

---

### **2. Sachdeva_Prerna_Q5Original.ipynb**
Contains **Q5 (Original Dataset)**:

### **Q5 — Image Binary Classification (Original Dataset)**
- Uses `train_catvnoncat.h5` and `test_catvnoncat.h5`  
- Logistic regression built from scratch  
- Flattening + normalization of images  
- Learned parameters (w, b)  
- Train & test accuracy  
- Display of misclassified images (up to 4)  

This notebook evaluates the classifier on the **unmodified dataset**.

---

### **3. Sachdeva_Prerna_Q5Modified.ipynb**
Contains **Q5 (Modified Dataset)**:

### **Q5 — Image Binary Classification (Modified Dataset Based on ID)**
- Training set reduced to **160 + last_digit** examples  
- Remaining images automatically become the new test set  
- Entire logistic regression pipeline re-run  
- Updated accuracies  
- Updated misclassified images  

This demonstrates how dataset size impacts model performance.

---

## How to Run the Code

### **Step 1: Install Dependencies**

pip install numpy matplotlib h5py

### **Step 2: Add Dataset Files**

Make sure these dataset files are in the same folder as your notebooks:

- train_catvnoncat.h5

- test_catvnoncat.h5

### **Step 3: Run the Notebooks**
Run Jupyter Notebook:  

- jupyter notebook  

- Then open these files:  

- Sachdeva_Prerna_Project6.ipynb  

- Sachdeva_Prerna_Q5Original.ipynb  

- Sachdeva_Prerna_Q5Modified.ipynb  
