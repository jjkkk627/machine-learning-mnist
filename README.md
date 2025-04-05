# Machine Learning:

This project implements and compares multiple machine learning models to predict the **sum of two MNIST digits**, using images of size 56×28 formed by vertically stacking two handwritten digits.

## Models Implemented

- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Random Forest**
- **Fully Connected Neural Network (MLP)**

Each model was trained and evaluated on:
- A custom dataset built from MNIST pairs
- Balanced train/val/test splits

## Setup Instructions

### 1. Install Required Packages

To install the required packages listed in the requirements.txt file, run the following command in your terminal or command prompt, within your project’s environment:

```bash
pip install -r requirements.txt
```
### 2. Run the Jupyter Notebook

After installing the required packages, open the Jupyter Notebook `M1_Coursework.ipynb` and **execute the cells in order**.

## 3. Project structure:

Three neural network models are saved in a folder called `nn_models` which contains:

- A folder `best_model` which contains the saved best model, its weights, and its saved training history.

- A folder `model_1` which contains the saved **Model 1**, its weights, and its saved training history.

- A folder `model_2` which contains the saved **Model 2**, its weights, and its saved training history.

## Acknowledgments

- This project was originally developed as part of a graduate-level machine learning course.
