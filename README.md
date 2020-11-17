# Matrix_operation



mnozenie(matrixA,matrixB)

mnozenie is a matrix multiple function, the function return new matrix

[	1	2	3	]		[	3	4	5	]		[	36	29	41	]
[	4	5	6	]	x	[	6	5	9	] 	=	[	84	71	101	]
[	7	8	9	]		[	7	8	9	]		[	132	113	161	]


transpose(matrixB)

this function change rows and columns position.
it something like that.
The first row in old matrix is first column in new matrix
The secound row in old matrix is secound column in new matrix
The third row in old matrix is third column in new matrix

[	1	2	3	]				[	1	4	7	]
[	4	5	6	]		-->	[	2	5	8	]
[	7	8	9	]				[	3	6	9	]


algebraic_multiplication(multipler ,& matrix)
This function operate in our matrix, all element in matrix is multiple by multipler.


		[	1	2	3	]				[	4*1	4*2	4*3	]			[	4	8	12	]
4	*	[	4	5	6	]		=		[	4*4	4*5	4*6	]	=		[	16	20	24	]
		[	7	8	9	]				[	4*7	4*8	4*9	]			[	28	32	36	]
		


wyznaczik(matrix)		
wyznacznik function is a function which counts the determinant of the matrix

	  [	1	2	3	]				  |	1	2	3	|
det	[	4	5	6	]		-->		|	4	5	6	|	=0
	  [	7	8	9	]				  |	7	8	9	|
	

