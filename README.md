# FINAL REVIEW 
## Index
- [FINAL REVIEW](#final-review)
  - [Index](#index)
  - [Topics](#topics)
    - [1. Solution of systems of equations](#1-solution-of-systems-of-equations)
    - [2. Row echelon form and reduced echelon form](#2-row-echelon-form-and-reduced-echelon-form)
    - [Matrix operations and transformations](#matrix-operations-and-transformations)

## Topics
### 1. Solution of systems of equations
- PROBLEMS: 1 - 13, 18 - 25
- You can use substitution, elimination, and augmented matrix row reduction.
- In any case, the system may end up having infinite many solutions. For that, in matrix row reduction, at least one row will be all zero. If a row ends up being $\begin{bmatrix}\text{ } 0 & 0 & 0 & \bigm| & \text{number other than 0 } \end{bmatrix}$, then there is no solution.
- To know if the system has infinite many solutions, the number columns (n), has to be greater than the number of rows (m). This also applies to 
<br><br> [Back to Index](#index)

### 2. Row echelon form and reduced echelon form
- Problems: 14 - 17
- Echelon form: Has pivot ones in diagonal and zeroes below it 
<br> $\begin{bmatrix} 1 & 4 & 1 \\ 0 & 1 & 1 \\ 0 & 0 & 1 \end{bmatrix}$
- Reduced echelon form: Has pivot numbers in diagonal and zeroes below it and above it<br>
$\begin{bmatrix}1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1\end{bmatrix}$
- Non-echelon form: Does not have pivot's diagonally. Doesn't have staircase 0's structure. It also applies if a row entirely comprised of 0's is in any of the beginning or middle positions <br>  $\begin{bmatrix}1 & 0 & 4 \\ 4 & 7 & 8 \\ 0 & 0 & 0\end{bmatrix}$
<br><br> [Back to Index](#index)

### Matrix operations and transformations
- Problems:
- Addition: To perform addition, matrices must have the exact same dimmensions <br>
$\begin{bmatrix} 5 &  7 \\ 5 & 8 \end{bmatrix} + \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix} = \begin{bmatrix} 6 & 7 \\ 5 & 9 \end{bmatrix}$
- Scalar multiplication: When a vector is multiplied by a scalar, we just distribute the scalar to each of the values of the vectors
$$2 \cdot \begin{bmatrix} 8 & 4 \\ 5 & 2 \end{bmatrix} = \begin{bmatrix} 16 & 8 \\ 10 & 4 \end{bmatrix}$$
<br><br>[Back to index](#index)