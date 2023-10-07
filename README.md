# NumericalMethods


- `pivot(row_i, row_j, A)`: Performs row pivoting on a given matrix `A` by swapping rows `row_i` and `row_j`.

- `scale(row_i, λ, A)`: Scales a specified row `row_i` of a matrix `A` by a scalar factor `λ`.

- `Tmatrix(A)`: Computes the upper triangular matrix using Gaussian elimination on matrix `A`.

- `matmul(A, B)`: Calculates the number of arithmetic operations required to multiply two matrices `A` and `B`.

- `checksym(A)`: Checks if a matrix `A` is symmetric and returns `True` if it is.

- `cholesky_decomposition(A)`: Computes the Cholesky decomposition of a matrix `A`.

- `gaus_seidal(A, b, x0, tol, max_iterations)`: Implements the Gauss-Seidel method to solve a system of linear equations.<br>


- `jacobi(A, b, x0, tol, max_iterations)`: Implements the Jacobi method to solve a system of linear equations.

- `CycTridJacobi(n, tol, max_iterations)`: Solves a tridiagonal linear system using the Jacobi iterative method.

- `bisection(f, x0, x1, kmax, tol)`: Implements the bisection method to find the root of a given function `f` within an interval `[x0, x1]`.


1. `pivot` - Used for row pivoting in matrix operations.
2. `scale` - Used for scaling a row in a matrix.
3. `Tmatrix` - Used for computing the upper triangular matrix using Gaussian elimination.
4. `matmul` - Used for matrix multiplication and counting arithmetic operations.
5. `checksym` - Used for checking if a matrix is symmetric.
6. `cholesky_decomposition` - Used for computing the Cholesky decomposition of a matrix.
7. `gaus_seidal` - Used for solving a system of linear equations using the Gauss-Seidel method.
8. `jacobi` - Used for solving a system of linear equations using the Jacobi method.
9. `CycTridJacobi` - Used for solving a tridiagonal linear system using the Jacobi iterative method.
10. `bisection` - Used for finding the root of a function within an interval using the bisection method.

These are the method names used throughout code for various mathematical and computational operations.


