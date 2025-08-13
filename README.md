# Objective:To study and implement 2D arrays in C++ for storing and processing data (Matrix operations).

# Apparatus / Software Required:
VS code

# Theory:

A 2D array is a collection of elements arranged in rows and columns.
It is declared as:
data_type array_name[rows][columns];

Rows: Horizontal arrangement of elements.

Columns: Vertical arrangement of elements.

Example:
int matrix[3][3]; — A 3×3 integer array.

2D arrays are commonly used to store matrices, tables, and grids.
They are accessed using two indices:
matrix[i][j] → Element in the ith row and jth column.

# Algortithm:

Display a 3×3 Matrix:

1.Start

2.Declare a 3×3 integer array matrix[3][3].

3.For i = 0 to 2 (row index):

  For j = 0 to 2 (column index):
  
- Display message "Enter element-(i,j):"
- 
- Read matrix[i][j] from user.

4.For k = 0 to 2 (row index):

 For l = 0 to 2 (column index):
 
 5.Print matrix[k][l] followed by a space.
 
 6.Move to next line after printing all columns in the row.

 7.Stop

 Addition of Two 3×3 Matrices:

 1.Start

 2.Declare three 3×3 integer arrays: matrixA[3][3], matrixB[3][3], and matrixC[3][3].

 3.Input Matrix A:
 
   For i = 0 to 2:
- For j = 0 to 2:
- 
- Display "Enter element (i,j):"
- 
- Read value into matrixA[i][j].

4.Display Matrix A:

 For i = 0 to 2:
- For j = 0 to 2:
- 
- Print matrixA[i][j] with a space.
- 
- Move to the next line after each row.

5.Input Matrix B:

 For i = 0 to 2:
- For j = 0 to 2:
- 
- Display "Enter element (i,j):"
- 
- Read value into matrixB[i][j].

6.Display Matrix B:

 For i = 0 to 2:
- For j = 0 to 2:
- 
- Print matrixB[i][j] with a space.
- 
- Move to the next line after each row.

7.Perform Matrix Addition:

  For i = 0 to 2:
- For j = 0 to 2:
- 
- Compute matrixC[i][j] = matrixA[i][j] + matrixB[i][j].

8.Display Result Matrix C:

  For i = 0 to 2:
- For j = 0 to 2:
- 
- Print matrixC[i][j] with a space.
- 
- Move to the next line after each row.

9.Stop

Multiplication of Two 3×3 Matrices:

1.Start

2.Declare three integer matrices:

A[3][3] for the first matrix

B[3][3] for the second matrix

C[3][3] for the result

3.Input Matrix A:

 For i = 0 to 2 (rows):
- For j = 0 to 2 (columns):
- Display "A[i][j]: "
- Read value into A[i][j]

4.Input Matrix B:
 For i = 0 to 2 (rows):
- For j = 0 to 2 (columns):
- Display "B[i][j]: "
- Read value into B[i][j]

5.Initialize Result Matrix C to zeros:

 For i = 0 to 2:
- For j = 0 to 2:
- Set C[i][j] = 0

6.Multiply Matrices (Triple Nested Loop):

 For i = 0 to 2 (rows of A):
- For j = 0 to 2 (columns of B):
- For k = 0 to 2 (columns of A / rows of B):
- Update C[i][j] = C[i][j] + (A[i][k] * B[k][j])

7.Display Result Matrix C:

 For i = 0 to 2:
- For j = 0 to 2:
- Print C[i][j] with a space
- Move to next line after each row

8.Stop

 Transpose of a Matrix:

1. Start

2.Declare integers i, j, r1, c1, r2, c2 for loop control and dimensions.

3.Input Matrix Dimensions:

Display "Enter number of rows & column: "

Read r1 and c1

4.Declare Matrix ar[r1][c1]

5.Input Matrix Elements:
 For i = 0 to r1-1:
- For j = 0 to c1-1:
- Display "Enter element-(i+1)(j+1): "
- Read ar[i][j]

6.Set Transpose Dimensions:

r2 = c1

c2 = r1

7.Declare Transpose Matrix t[r2][c2]

8.Compute Transpose:
For i = 0 to r2-1:
- For j = 0 to c2-1:
- Set t[i][j] = ar[j][i]
- Print t[i][j] with two spaces
- Move to next line after each row

9.Stop

# Conclusion:

We successfully implemented a program in C++ to perform operations on 2D arrays, demonstrating the concept of storing and processing matrix data.













