# Matrix Multiplication

Test for 2500 * 2500 size matrix multiplication, and try to optimize calculating speed by reducing CPU cache miss

## Result

Every problem use various way to calculate multiplication

a and b version is different from only the coding optimization

### Problem 1 - Trivial Way

Used Time: **93.91s**

### Problem 2 - Index Reordering

Used Time: **52.11s**

### Problem 3 - Column Major

Used Time: **45.64s**

### Problem 4 - Blocks by Index

Used Time: a.**49.75s** ; b.**49.73s**

### Problem 5 - Blocks by Submatrix

Used Time: a.**46.29s** ; b.**44.45s**
