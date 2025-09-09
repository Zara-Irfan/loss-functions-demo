# Loss Functions in Machine Learning

This project demonstrates **key loss functions** used in machine learning and neural networks. Loss functions measure how far a model's predictions are from the true values and guide the model to improve during training.

---

## Overview

Loss functions covered in this project:

1. **Mean Absolute Error (MAE)**  
   - Measures the average of absolute differences between predicted and actual values.  
   - Less sensitive to outliers.  

2. **Mean Squared Error (MSE)**  
   - Measures the average of squared differences between predicted and actual values.  
   - Larger errors are penalized more due to squaring.  

3. **Log Loss / Binary Cross-Entropy**  
   - Used for binary classification tasks.  
   - Measures how close predicted probabilities are to the true labels.  
   - Values are clipped slightly to avoid log(0) errors.

---

## Key Concepts

- **Loss / Cost Function:** Measures the model's error; the smaller the loss, the better the model is performing.  
- **MAE:** Simple average error magnitude.  
- **MSE:** Squares errors, penalizing large deviations.  
- **Log Loss:** Uses probabilities; penalizes confident wrong predictions more.  

---

## Project Highlights

- Implemented MAE, MSE, and Log Loss from scratch in Python.  
- Demonstrated calculations with **sample data** for clear understanding.  
- Showed **how NumPy can simplify computations** for MAE and MSE.  
- Explained **epsilon clipping** in log loss to prevent computational errors.  

---

## Sample Output

=== MAE ===
Total error: 2.2
MAE: 0.44
MAE (NumPy): 0.44

=== MSE ===
Total squared error: 2.34
MSE: 0.468
MSE (NumPy): 0.468

=== Log Loss / Binary Cross-Entropy ===
Log Loss: 2.528


---

## Installation

Clone this repository and install NumPy:

```bash
git clone https://github.com/yourusername/loss-functions-demo.git
cd loss-functions-demo
pip install numpy

Usage

    Run the Python script in your terminal or Jupyter Notebook.

    The script will compute MAE, MSE, and Log Loss for example predictions.

    Outputs show both custom calculations and NumPy-based calculations.

Applications

    MAE & MSE: Regression tasks, evaluating model predictions.

    Log Loss: Binary classification problems like spam detection, disease diagnosis, or yes/no predictions.

Why This Project is Useful

    Provides a clear understanding of loss functions used in ML and AI.

    Hands-on implementation demonstrates the calculations behind the theory.

    Useful for interviews targeting data scientist or machine learning engineer roles.

License

This project is open-source under the MIT License.
