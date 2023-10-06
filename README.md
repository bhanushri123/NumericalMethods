# NumericalMethods


- `pivot(row_i, row_j, A)`: Performs row pivoting on a given matrix `A` by swapping rows `row_i` and `row_j`.

- `scale(row_i, λ, A)`: Scales a specified row `row_i` of a matrix `A` by a scalar factor `λ`.

- `Tmatrix(A)`: Computes the upper triangular matrix using Gaussian elimination on matrix `A`.

- `matmul(A, B)`: Calculates the number of arithmetic operations required to multiply two matrices `A` and `B`.

- `checksym(A)`: Checks if a matrix `A` is symmetric and returns `True` if it is.

- `cholesky_decomposition(A)`: Computes the Cholesky decomposition of a matrix `A`.

- `gaus_seidal(A, b, x0, tol, max_iterations)`: Implements the Gauss-Seidel method to solve a system of linear equations.

- `jacobi(A, b, x0, tol, max_iterations)`: Implements the Jacobi method to solve a system of linear equations.

- `CycTridJacobi(n, tol, max_iterations)`: Solves a tridiagonal linear system using the Jacobi iterative method.

- `bisection(f, x0, x1, kmax, tol)`: Implements the bisection method to find the root of a given function `f` within an interval `[x0, x1]`.



These bullet points provide a brief overview of each method's purpose and functionality in your code. You can include these descriptions in your README file for users to reference.
