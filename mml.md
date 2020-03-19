Link to book https://mml-book.github.io/book/mml-book.pdf
# Linear Algebra
 1. Systems of Linear Equations

    In general, for a real-valued system of linear equations we obtain either no, exactly one, or infinitely many solutions.
    
 2. Matrices
 
    ** Matrix Addition and Multiplication
    - The sum of two matrices is defined as the element-wise sum.
    - Matrix multiplication is not defined as an element-wise operationon matrix elements. This kind of element-wise multiplication often appears in programming languages when we multiply (multi-dimensional) arrays with each other, and is called a Hadamard product.

    ** Identity Matrix
    - We define the identity matrix as the n×n-matrix containing 1 on the diagonal and 0 everywhere else.

    ** Some properties of matrices
    - Associativity: (AB)C = A(BC)
    - Distributivity: (A+B)C = AC+BC; A(C+D) = AC+AD
    - Multiplication with the identity matrix: IA = AI = A
 
    ** Inverse and Transpose
    - Consider a square matrix. B have the property that AB = I = BA. B is called the inverse of A and denoted by A^−1. Unfortunately, not every matrix A possesses an inverse A^−1. If this inverse does exist, A is called regular/invertible/nonsingular, otherwise singular/noninvertible. When the matrix inverse exists, it is unique.
    - For A ∈ Rm×n the matrix B ∈ Rn×m with bij = aji is called the transpose of A. We write B = A^T.
    - The following are important properties of inverses and transposes:
 
        AA^−1 = I = A^−1A; (AB)^−1 = B^−1A^−1; (A+B)^−1 # A^−1+B^−1; (A^T)^T = A; (A+B)^T = A^T+B^T; (AB)^T = B^TA^T
    - Symmetric Matrix: A matrix A is symmetric if symmetric matrix A = A^T.
 
    ** Multiplication by a Scalar

    ** Compact Representations of Systems of Linear Equations

    ** Solving Systems of Linear Equations
    1. Find a particular solution to Ax = b.
    2. Find all solutions to Ax = 0.
    3. Combine the solutions from steps i. and ii. to the general solution.
    
    ** Row-Echelon Form: A matrix is in row-echelon form if
    - All rows that contain only zeros are at the bottom of the matrix; correspondingly, all rows that contain at least one nonzero element are on top of rows that contain only zeros.
    - Looking at nonzero rows only, the first nonzero number from the left (also called the pivotor the leading coefficient) is always strictly to the pivot leading coefficient right of the pivot of the row above it.

    ** Basic and Free Variables: The variables corresponding to the pivots in the row-echelon form are called basic variables and the other variables are free variables.
