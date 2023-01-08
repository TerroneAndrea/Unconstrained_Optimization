# IMPLEMENTATION OF THE TRUNCATED NEWTON METHOD 

The aim of this project is to solve an uncostrained optimization problem by applying the **Truncated Newton Algorithm**.

The direction is computed by applying the **Conjugate-Gradient method**.

The step along this direction is calculated by the **Armijo conditions**.

I didn't use any pre-built optimization method.
I only used autograd for calculating the gradient of the function to minimize and autograd.numpy for vectors and matrix operations.