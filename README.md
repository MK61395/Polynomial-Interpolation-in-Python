# Polynomial-Interpolation-in-Python
Polynomial Interpolation, Evaluation and Testing using Direct and Newton Divided Methods

## Overview
This assignment demonstrates polynomial interpolation using two methods: the Direct (Matrix) method and the Newton Divided Difference method. The objective is to compute the polynomial coefficients, evaluate the polynomials at given points, and visualize the results. Additionally, the Root Mean Squared Error (RMSE) is calculated to assess the accuracy of the interpolated polynomials.

## Project Structure
The project consists of the following key components:

1. **Dataset Generation Function**: 
    - A function `f(x)` to generate a dataset based on a given mathematical expression.

2. **Root Mean Squared Error (RMSE)**: 
    - A function `RMSE(y_actual, y_predicted)` to compute the RMSE between actual and predicted values, providing a measure of the interpolation accuracy.

3. **Direct (Matrix) Method for Polynomial Interpolation**:
    - `poly_coeffs_direct(x, y)`: Computes the polynomial coefficients using the Direct (Matrix) method by solving a system of linear equations.
    - `poly_evaluation_direct(xx, coeffs)`: Evaluates the polynomial at given points using the computed coefficients from the Direct method.

4. **Newton Divided Difference Method for Polynomial Interpolation**:
    - `poly_coeffs_newton(x, y)`: Computes the polynomial coefficients using the Newton Divided Difference method.
    - `poly_evaluation_newton(a, x, z)`: Evaluates the polynomial at given points using the computed coefficients from the Newton method.

5. **Plot Generation**:
    - Generation of plots for polynomials of orders 5 and 25 using both interpolation methods. These plots compare the interpolated polynomial with the original function `f(x)` and the dataset points.

## Results
- **Polynomial of Order 5**:
    - Plots are generated using both Direct and Newton methods.
    - RMSE values are computed to compare the accuracy of the interpolated polynomials against the actual function values.

- **Polynomial of Order 25**:
    - Similar to the polynomial of order 5, but with a higher order polynomial, providing insights into the behavior and accuracy of higher-degree interpolations.

## Conclusion
The assignment successfully demonstrates polynomial interpolation using both the Direct (Matrix) method and the Newton Divided Difference method. The RMSE values indicate the accuracy of the interpolated polynomials, and the plots provide a visual comparison against the actual function. The project highlights the strengths and limitations of each interpolation method when applied to polynomials of different orders.


