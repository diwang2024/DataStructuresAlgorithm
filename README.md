# DataStructuresAlgorithm
This Jupyter Notebook is created for the online course [Data Structure and Algorithms in Python](https://jovian.com/learn/data-structures-and-algorithms-in-python) at [Jovian](https://jovian.com). It can be run on Google Colab or Kaggle. 

In this project, I solve the problem of `matrix chain multiplication` (see [this](https://en.wikipedia.org/wiki/Matrix_chain_multiplication) and [this](https://www.techiedelight.com/matrix-chain-multiplication/). Leveraging on the associative nature of the chain multiplications, we can minimize the number of operations needed by choosing the order of the parentheses. 

> Determine the optimal parenthesization of a product of n matrices. The multiplication is associative. For example, for four matrices A, B, C, and D, we would have: ((AB)C)D = ((A(BC))D) = (AB)(CD) = A((BC)D) = A(B(CD)). However, the order in which the product is parenthesized affects the number of simple arithmetic operations needed to compute the product. or example, if A is a 10 × 30 matrix, B is a 30 × 5 matrix, and C is a 5 × 60 matrix, then computing (AB)C needs (10×30×5) + (10×5×60) = 1500 + 3000 = 4500 operations while computing A(BC) needs (30×5×60) + (10×30×60) = 9000 + 18000 = 27000 operations. Clearly, the first method is more efficient.

To solve the problem, I use the following steps.
- State the problem clearly. Identify the input & output formats.
- Come up with some example inputs & outputs. Try to cover all edge cases.
- Come up with a solution (in this case, divide-and-conquer using recursion).
- Implement the solution and test it using example inputs.
- Analyze the algorithm's time and space complexity and identify inefficiencies. 
- Apply the technique to improve the efficiency (in this case, memoization).
