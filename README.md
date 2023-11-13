

# Matrix_operation



### matrix_multiplication(matrixA,matrixB)

matrix_multiplication is a matrix multiple function, the function return new matrix

    [ A₀₀ A₀₁ A₀₂ ]       [ B₀₀ B₀₁ B₀₂ ]      [ C₀₀ C₀₁ C₀₂ ]
    [ A₁₀ A₁₁ A₁₂ ]   *   [ B₁₀ B₁₁ B₁₂ ]  =   [ C₁₀ C₁₁ C₁₂ ]
    [ A₂₀ A₂₁ A₂₂ ]       [ B₂₀ B₂₁ B₂₂ ]      [ C₂₀ C₂₁ C₂₂ ]



C<sub>i,j</sub> = A<sub>i,1</sub> * B<sub>1,j</sub> + A<sub>i,2</sub> * B<sub>2,j</sub> + A<sub>i,3</sub> * B<sub>3,j</sub>

Where C<sub>0,0</sub> = A<sub>0,1</sub> * B<sub>1,0</sub> + A<sub>0,2</sub> * B<sub>2,0</sub> + A<sub>0,3</sub> * B<sub>3,0</sub>


    [ 1  2  3 ]       [ 3  4  5 ]      [ 36   29   41 ]
    [ 4  5  6 ]   *   [ 6  5  9 ]  =   [ 84   71  101 ]
    [ 7  8  9 ]       [ 7  8  9 ]      [132  113  161 ]


### transpose(matrixB)

The row of the current matrix becomes a column for the new matrix
It something like that.
* The first row in old matrix is first column in new matrix
* The secound row in old matrix is secound column in new matrix
* The third row in old matrix is third column in new matrix

          Original Matrix A:
              [ A₁₁ A₁₂ A₁₃ ]
              [ A₂₁ A₂₂ A₂₃ ]
              [ A₃₁ A₃₂ A₃₃ ]

          Transpose A^T:
              [ A₁₁ A₂₁ A₃₁ ]
              [ A₁₂ A₂₂ A₃₂ ]
              [ A₁₃ A₂₃ A₃₃ ]

          Matrix Transformation:
              [ 1  2  3 ]       [ 1  4  7 ]
              [ 4  5  6 ]  -->  [ 2  5  8 ]
              [ 7  8  9 ]       [ 3  6  9 ]



### algebraic_multiplication(multipler ,& matrix)
This function operate in our matrix, all element in matrix is multiple by multipler.

                            [ A₁₁ A₁₂ A₁₃ ]     [ 4*A₁₁ 4*A₁₂ 4*A₁₃ ]
                        4 * [ A₂₁ A₂₂ A₂₃ ]  =  [ 4*A₂₁ 4*A₂₂ 4*A₂₃ ]
                            [ A₃₁ A₃₂ A₃₃ ]     [ 4*A₃₁ 4*A₃₂ 4*A₃₃ ]

                            [ 3  4  5 ]       [ 4*3  4*4  4*5 ]       [ 12  16  20 ]
                        4 * [ 6  5  9 ]   =   [ 4*6  4*5  4*9 ]   =   [ 24  20  36 ]
                            [ 7  8  9 ]       [ 4*7  4*8  4*9 ]       [ 28  32  36 ]
### determinant(matrix)		
determinant function is a function which counts the determinant of the matrix


                                            | 1  2  3 |
                                  det(A) =  | 4  5  6 | --> 0
                                            | 7  8  9 | 

