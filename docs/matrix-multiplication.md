# matrix multiplication
It can be performed only when number of columns of first matrix is equal to number of rows of the second matrix, e.g. where $\mathbf{A}$ is $m \times n$ matrix and $\mathbf{B}$ is ${n \times p}$ matrix

$$
\mathbf{C} = \mathbf{A} \mathbf{B},
$$

will produces $\mathbf{C}$, a $m \times p$ matrix, where its element

$$
c_{ik} = \sum_{j = 1}^n a_{ij} b_{jk},
$$

with $i = 1, .., m$, $j = 1, .., n$, and $k = 1, .., p$. 
