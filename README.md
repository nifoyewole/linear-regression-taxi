# Linear Regression Refresher

Predicting Chicago taxi fares from trip data, built as a hands-on lab to understand linear regression.

## Things covered (and studied)
1. Data exploration: descriptive stats, scale/outlier checks, and correlation
2. The model: fitting `FARE = w1·miles + w2·minutes + b`; what weights and bias mean geometrically (tilt and height of a line/plane).
3. Two solvers: `LinearRegression` (exact, algebraic) vs `SGDRegressor` (gradient descent), and confirming they reach the same answer.
4. Gradient descent: the loss landscape, local slope, learning rate, epochs, batch size, and convergence
5. Feature scaling: why standardization matters for iterative solvers
6. Evaluation: MSE / RMSE / MAE / R², what each means, and how to judge "good" relative to the target's scale and the train/test gap.
7. Generalization: train/test split, overfitting vs underfitting, and why lowest training loss is not the goal.

## Stack
Python, pandas, NumPy, matplotlib, seaborn, scikit-learn.

## Files
- `taxi_linear_regression_lab.ipynb`
- data: Chicago taxi trips

## Finding
Gradient descent worked out Chicago's actual fare formula (2.25·miles + 0.12·minutes + 3.25)
