# Implementing Linear Regression from Scratch using Python

## Overview
This project demonstrates how to implement simple linear regression from scratch using Python, without relying on libraries like Scikit-Learn. The implementation includes data preprocessing, model training, evaluation, and visualization of results.

## Features
- Implementation of simple linear regression using NumPy
- Gradient descent for parameter optimization
- Performance evaluation using Mean Squared Error (MSE)
- Data visualization using Matplotlib
- Comparison with Scikit-Learn's implementation
- Calculation of regression weights using Scikit-Learn

## Prerequisites
Before running the project, ensure you have the following dependencies installed:

```bash
pip install numpy matplotlib scikit-learn
```

## Project Structure
- `simpleLR.ipynb` - Jupyter Notebook containing the full implementation and explanation.

## Implementation Details
1. **Data Generation:** Synthetic dataset is created with a linear relationship.
2. **Model Training:** Gradient descent is used to find optimal parameters.
3. **Loss Function:** Mean Squared Error (MSE) is used to evaluate the model.
4. **Visualization:** Data points and regression line are plotted for better understanding.
5. **Comparison with Scikit-Learn:** The custom implementation is validated against Scikit-Learn's `LinearRegression`.
6. **Weight Calculation:** Regression weights are computed using Scikit-Learn for comparison.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/dheru94/Implementing-Linear-Regression-FROM-SCRATCH-using-PYTHON.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Implementing-Linear-Regression-FROM-SCRATCH-using-PYTHON
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook simpleLR.ipynb
   ```
4. Run the cells sequentially to see the implementation in action.

## Results
- The model successfully fits a linear dataset.
- The predicted regression line closely follows the ground truth.
- Performance is comparable to Scikit-Learn’s linear regression.
- Regression weights are computed using both custom implementation and Scikit-Learn for validation.

## Future Enhancements
- Extend to multiple linear regression
- Implement regularization techniques (Lasso, Ridge)
- Use stochastic gradient descent (SGD) for optimization
- Optimize code for better performance

## Contributing
Feel free to fork this repository, make improvements, and submit a pull request.

## License
This project is licensed under the MIT License.

