# DPCP: Differentiable Projections to Convex Polytopes

![Tests](https://github.com/teddykoker/torchsort/workflows/Tests/badge.svg)

Fast, Differentiable projections to Convex Polytopes via reduction to isotonic optimization.

NOTICE: This code builds on `https://github.com/teddykoker/torchsort` and generalizes 
to many convex polytope types for usage in machine learning pipelines

Pure PyTorch implementation of [Fast Differentiable Sorting and
Ranking](https://arxiv.org/abs/2002.08871) (Blondel et al.). Much of the code is
copied from the original Numpy implementation at
[google-research/fast-soft-sort](https://github.com/google-research/fast-soft-sort),
with the isotonic regression solver rewritten as a PyTorch C++ and CUDA
extension.
