# Math in Machine Learning

A structured math learning resource for ML — annotated, runnable Jupyter notebooks organized by topic and difficulty.

## Structure

```
linear-algebra-1/       # Foundations of linear algebra (4 notebooks)
linear-algebra-2/       # Advanced linear algebra for deep learning (4 notebooks)
tasks-linear-algebra-1/ # Practice exercises for LA-1 (easy → complex)
tasks-linear-algebra-2/ # Practice exercises for LA-2 (easy → complex)
ml-libraries/           # NumPy, PyTorch, TensorFlow command references
```

## Linear Algebra 1

| Notebook | Topics |
|----------|--------|
| scalars-vectors-matrix | Scalars, vectors, matrices, basic operations |
| operations-in-linear-algebra | Broadcasting, reshape, masking, norms, cosine similarity |
| ml-critical-extensions | Linear transforms, projection, SVD, QR, Cholesky, eigenvalues |
| advanced-linear-algebra | Rank, determinant, inverse, PCA, LoRA, autograd |

## Linear Algebra 2

| Notebook | Topics |
|----------|--------|
| systems-and-orthogonality | Gaussian elimination, LU decomposition, null space, Gram-Schmidt |
| matrix-calculus-and-optimization | Gradient, Jacobian, Hessian, chain rule, positive definite matrices |
| advanced-tensor-and-spectral | einsum, Kronecker, spectral decomposition, matrix sqrt, pseudoinverse |
| deep-learning-applications | Attention, weight init, batch norm, layer norm, gradient flow |

## Tasks

Each task set has three levels — easy, medium, and complex — with `None` placeholders to fill in.

| File | Difficulty | Focus |
|------|-----------|-------|
| task-1.ipynb | Easy | Core operations, single-concept problems |
| task-2.ipynb | Medium | Multi-step problems combining concepts |
| task-3.ipynb | Complex | End-to-end implementations (PCA, attention, transformer block) |

## ML Libraries

| Folder | Contents |
|--------|----------|
| numpy/ | NumPy array operations and common patterns |
| pytorch/ | PyTorch tensor operations and autograd |
| tensorflow/ | TensorFlow tensor operations and GradientTape |

## How to Use

1. Open a notebook in `linear-algebra-1/` or `linear-algebra-2/` and read through the examples.
2. Open the matching task notebook, read each problem, and replace `None` with your solution.
3. Run the cell to check your answer — each task prints a verification.

## Requirements

- Python 3.10+
- `numpy`, `scipy`, `torch`, `tensorflow`: `pip install numpy scipy torch tensorflow`
- Jupyter: `pip install jupyter`
