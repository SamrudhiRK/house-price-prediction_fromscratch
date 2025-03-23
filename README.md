# House-price-prediction_fromscratch

This project implements Linear Regression from scratch to predict house prices based on various features. It includes regularization to improve model performance and prevent overfitting. The model is optimized using Gradient Descent, and results are compared for regularized and non-regularized approaches.
---
# Linear Regression from Scratch for House Price Prediction 
## Project Overview  
This project implements **Linear Regression from scratch** to predict house prices. It also includes **L1 (Lasso) and L2 (Ridge) regularization** to improve model performance and prevent overfitting.  
## Dataset  
The data can be found at: https://www.kaggle.com/datasets/yasserh/housing-prices-dataset
The dataset contains features such as:  
- **Main Road Access** (`yes/no` converted to binary)  
- **Various House Attributes**  
- **Target Variable:** `price` (House price)  
## Implementation Steps  
1. **Data Preprocessing**  
   - Handling categorical variables using **binary mapping**  
   - Splitting data into **features (`X`)** and **target (`y`)**  
2. **Linear Regression Without Regularization**  
   - Implementing **Gradient Descent** to optimize the cost function  
   - Computing **Mean Squared Error (MSE)**  

3. **Regularized Linear Regression**  
   - Applying **L1 (Lasso) and L2 (Ridge) regularization**  

4. **Comparison of Models**  
   - Evaluating model performance with and without regularization  

## Requirements  
Install the required dependencies before running the notebook:  

```bash
pip install numpy pandas matplotlib
```
## How to Run the Project  
1. Clone this repository:  
   ```bash
   git clone https://github.com/SamrudhiRK/house-price-prediction_fromscratch.git
   ```
2. Navigate to the project folder:  
   ```bash
   cd linear-regression-house-price
   ```
3. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook linear_reg_housep.ipynb
   ```

## Results & Insights  
- The model successfully predicts house prices using **gradient descent optimization**.  
- **Regularization helps improve model generalization** and prevents overfitting.  
- Model performance is evaluated with and without regularization.  

