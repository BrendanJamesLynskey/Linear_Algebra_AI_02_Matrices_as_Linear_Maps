# Matrices as Linear Maps

Deck 02 of the [Linear Algebra for AI / ML](https://github.com/BrendanJamesLynskey/LLM_Hub_Linear_Algebra) series.

**Live presentation:** https://brendanjameslynskey.github.io/Linear_Algebra_AI_02_Matrices_as_Linear_Maps/

A matrix is a linear map between coordinate spaces. Once you read it that way, every layer of every neural network becomes a structural object, not a grid of numbers. Includes an interactive 2D linear-map visualiser with rotation / shear / scale / rank-1 presets.

## What's inside

- A matrix is a function: $T(\mathbf{x}) = A\mathbf{x}$
- Column picture vs row picture &mdash; both are needed
- Range, null space and the rank-nullity theorem
- Rank, full rank, rank-deficiency
- The four fundamental subspaces and their orthogonal decomposition
- Composition is multiplication &mdash; why dimensions must match, why matmul isn't commutative, why deep linear networks collapse to one matrix
- Inverse vs pseudoinverse, with the least-squares formula
- Interactive 2D visualiser (drag $a, b, c, d$, see the unit square deform; live rank and determinant)
- Reading an MLP layer as $W_2 \sigma(W_1 \mathbf{x} + \mathbf{b}_1) + \mathbf{b}_2$

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.
