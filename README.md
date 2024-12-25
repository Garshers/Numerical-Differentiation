# Numerical Differentiation with Finite Difference Method

This program calculates the derivative of a given function `f(x)` at a specific point `x₀` using the finite difference method. It constructs a difference table to approximate the derivative and compares the result with the analytical derivative calculated symbolically. Additionally, it estimates the theoretical error and computes the actual error to validate the accuracy of the method.

## Features

- **Function Input and Parameters:**
  - Define a custom function `f(x)` (e.g., `ln(x)`).
  - Specify the point of interest (`x₀`), step size (`h`), and method order (`n`).

- **Finite Difference Table Construction:**
  - Computes function values at equidistant points around `x₀`.
  - Builds a difference table to calculate higher-order differences.

- **Approximation of the Derivative:**
  - Uses the difference table to approximate `f'(x₀)` as a weighted sum of finite differences.
  - Adjusts the result using the step size `h`.

- **Exact Derivative Calculation:**
  - Computes the exact derivative symbolically for comparison.
  - Provides a benchmark for validating the approximation.

- **Error Estimation:**
  - Calculates the theoretical error bound based on higher-order derivatives.
  - Computes the actual error as the difference between the approximate and exact values.

## Output

The program outputs the following:
- The approximate derivative value at `x₀`.
- The exact derivative value at `x₀`.
- The theoretical error bound.
- The actual error.

## How to Use

1. Modify the function `f(x)` in the code to your desired function.
2. Set the values for:
   - `x₀`: The point where the derivative is to be calculated.
   - `h`: The step size for finite differences.
   - `n`: The order of the finite difference method.
3. Run the program to see the results and error estimations.

## Example

For the function `f(x) = ln(x)`, at `x₀ = 1`, with `h = 0.1` and `n = 4`, the program calculates:
- Approximate value of `f'(1)`.
- Exact value of `f'(1)` as determined symbolically.
- Theoretical and actual errors.

## Requirements

- A MATLAB environment or equivalent software capable of running MATLAB code.

## License

This project is open-source and licensed under the MIT License.
"# Numerical-Differentiation" 
