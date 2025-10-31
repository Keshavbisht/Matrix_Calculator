# Matrix Operations with NumPy

An interactive Python program for performing various matrix operations using NumPy. This program supports 1D, 2D, and 3D matrices with operations like addition, subtraction, and multiplication.

## Features

- ✨ Support for 1D, 2D, and 3D matrices
- ➕ Matrix Addition
- ➖ Matrix Subtraction
- ✖️ Matrix Multiplication (Element-wise and Dot Product)
- 🔢 Identity Matrix Generation
- 💬 Interactive menu-driven interface
- ✅ Input validation


When you run the program, you'll see:
```
Enter 1 for Addition
Enter 2 for Subtraction
Enter 3 for Multiplication
```

### Matrix Input

After selecting an operation, choose your matrix dimension:
- **1** - 1D Matrix (Vector)
- **2** - 2D Matrix
- **3** - 3D Matrix
- **4** - Identity Matrix

### Examples

#### Example 1: 2D Matrix Addition
```
Enter 1 for Addition
Hello Choose your Matrix Dimension
Enter 2 for 2-D

Enter matrix shape like 3,4 or 4,4
2,2

Enter Matrix in String form row wise
1 2
3 4

[Repeat for second matrix]
```

#### Example 2: Matrix Multiplication
```
Enter 3 for Multiplication

[Input first matrix]
[Input second matrix]

Choose 1 for Element Wise
Choose 2 for Dot Product
2
```

## Input Format

### 1D Matrix
- Enter space-separated values: `1 2 3 4`

### 2D Matrix
- Enter shape: `3,4` (3 rows, 4 columns)
- Enter each row space-separated:
  ```
  1 2 3 4
  5 6 7 8
  9 10 11 12
  ```

### 3D Matrix
- Enter shape: `2,3,4` (2 matrices of 3×4)
- Enter values row by row for each 2D matrix



## Functions Overview

- `oneDMatrix()` - Creates and returns a 1D NumPy array
- `twoDMatrix()` - Creates and returns a 2D NumPy array
- `threeDMatrix()` - Creates and returns a 3D NumPy array
- `identityMatrix()` - Generates an identity matrix
- `Addition()` - Performs matrix addition
- `Subtraction()` - Performs matrix subtraction
- `Multiplication()` - Performs matrix multiplication (element-wise or dot product)
- `inputFunc()` - Handles matrix dimension selection
- `main()` - Main program loop


⭐ If you find this project helpful, please consider giving it a star!
