# Linear_Regrassion with Gradient Descent
this project implements a simple linear regression model using gradient descent to predict a target variable based on three features. The dataset is generated with random values =, and the true relationship between features and lables is set according to the equation: Y = 5*x1 + 3*x2 + 1.5*x3 +6
## Project structure:
1. **Data Generation:**
   - Random data points for features (x1, x2, x3) and labels (Y) are generated.
   - Organized into a Pandas DataFrame.
2. **Data Preprocessing:**
   - Features (`feature1`, `feature2`, `feature3`) and labels (`labels`) are separated.
   - Split into training and testing sets using `train_test_split`.
   - Feature scaling with `StandardScaler` to prevent overflow and bias.
3. **Linear Regression Implementation:**
   - Bias term added to training features.
   - Initial weights set.
   - Gradient descent function updates weights based on the cost function.

4. **Training:**
   - Gradient descent applied to the training data.
   - Cost and weight history recorded.

5. **Results:**
   - Final weights and training loss displayed.
## Parameters:
- Learning Rate(LR):0.01
- Iterations: 1000

## Running the Code

1. **Dependencies:**
   - Ensure `numpy`, `pandas`, and `scikit-learn` are installed.

