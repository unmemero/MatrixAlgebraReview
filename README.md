# FINAL REVIEW 
NOTE: PLEASE DOWNLOAD THE `README.md` file and open it in any markdown editor if it gives you any problems viewing the equations
## Index
- [FINAL REVIEW](#final-review)
  - [Index](#index)
  - [Topics](#topics)
    - [1. Solution of systems of equations](#1-solution-of-systems-of-equations)
    - [2. Row echelon form and reduced echelon form](#2-row-echelon-form-and-reduced-echelon-form)
    - [3. Matrix operations and transformations](#3-matrix-operations-and-transformations)
    - [4. Linear combination of vectors](#4-linear-combination-of-vectors)

## Topics
### 1. Solution of systems of equations
- PROBLEMS: 1 - 13, 18 - 25,32 - 34
- You can use substitution, elimination, and augmented matrix row reduction.
- In any case, the system may end up having infinite many solutions. For that, in matrix row reduction, at least one row will be all zero. If a row ends up being 
  $$\begin{bmatrix}\text{ } 0 & 0 & 0 & \bigm| & \text{number other than 0 } \end{bmatrix}$$
  , then there is no solution.
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

### 3. Matrix operations and transformations
- Problems: 26-31, 38-49
- Addition: To perform addition, matrices must have the exact same dimmensions <br>
$\begin{bmatrix} 5 &  7 \\ 5 & 8 \end{bmatrix} + \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix} = \begin{bmatrix} 6 & 7 \\ 5 & 9 \end{bmatrix}$
- Scalar multiplication: When a vector is multiplied by a scalar, we just distribute the scalar to each of the values of the vectors
$$2 \cdot \begin{bmatrix} 8 & 4 \\ 5 & 2 \end{bmatrix} = \begin{bmatrix} 16 & 8 \\ 10 & 4 \end{bmatrix}$$
- Transpose. Denoted as $A^{T}$. This means that the rows and the columns in matrix $A$ will switch 
$$A=\begin{bmatrix} 1 & 5 & 7 \\ 7 & 4 & 2 \end{bmatrix}\text{, } A^{T}=\begin{bmatrix} 1 & 7 \\ 5 & 4 \\ 7 & 2 \end{bmatrix}$$
- Multiplication: <span style="color:red;">IMPORTANT</span> To perform this operation, the first matrix $A$ has to have the same number of comlumns as the number of rows in the second matrix $B$
$$A=\begin{bmatrix} 1 & 5 & 7 \\ 7 & 4 & 2 \end{bmatrix}, 2 \times 3$$
$$B=\begin{bmatrix} 4 & 8 \\ 2 & 3 \\ 4 & 6 \end{bmatrix}3\times 2$$
  The resulting matrix will have as dimensions the same number of rows as matrix $A$ and the same number of columns as matrix $B$. To multiply, we multiply row times column
  $$AB=\begin{bmatrix} 1 & 5 & 7 \\ 7 & 4 & 2 \end{bmatrix}\begin{bmatrix} 4 & 8 \\ 2 & 3 \\ -4 & 6 \end{bmatrix}=\begin{bmatrix}1(4)+5(2)+7(-4) & 1(8)+5(3)+7(6)\\ 7(4)+4(2)+2(-4) & 7(8)+4(3)+2(6) \end{bmatrix}=\begin{bmatrix}-14 & 65 \\ 28 & 80 \end{bmatrix}$$
<br><br>[Back to index](#index)

### 4. Linear combination of vectors
- Problems: 35 - 37
- Systems of equations with free variables (infinite number of solutions) can be expressed  as linear combinations of vectors 
  $$x_{1}=4+9s_{1}$$
  $$x_{2}=3+2s_{1}$$
  $$\begin{bmatrix}x_{1} \\ x_{2} \end{bmatrix} = \begin{bmatrix}4 \\ 3 \end{bmatrix} + \begin{bmatrix}9 \\ 2 \end{bmatrix} s_{1}$$
<br><br>[Back to Index](#index)