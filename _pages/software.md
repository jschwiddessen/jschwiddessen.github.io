---
title: "Software"
permalink: /software/
layout: single
author_profile: true
description: "Open-source software projects by Jan Schwiddessen."
toc: true
---

This page lists my open-source projects with links to code, docs, and releases. Questions? Open an issue on GitHub or email me.

## AugmentedMixing.jl

[AugmentedMixing.jl](https://github.com/jschwiddessen/AugmentedMixing.jl) is a Julia package that implements the *Augmented Mixing Method*, an algorithm for computing high-accuracy primal–dual solutions to large-scale semidefinite programs (SDPs).

It is based on the following preprint:

> Daniel Brosch, **Jan Schwiddessen**, Angelika Wiegele.  
> *The Augmented Mixing Method: Computing High-Accuracy Primal-Dual Solutions to Large-Scale SDPs via Column Updates.*  
> **Preprint**, (2025).  
> [arXiv](https://arxiv.org/abs/2507.20386)

---

## SDP-S3VM

[SDP-S3VM](https://github.com/jschwiddessen/SDP-S3VM) provides an exact SDP-based algorithm for semi-supervised support vector machines (S3VMs).

It is based on the following paper:

> Veronica Piccialli, **Jan Schwiddessen**, Antonio M. Sudoso.  
> *Optimization meets machine learning: an exact algorithm for semi-supervised support vector machines.*  
> **Mathematical Programming**, Series B, (2024).  
> [SpringerLink](https://link.springer.com/article/10.1007/s10107-024-02175-z) · [DOI](https://doi.org/10.1007/s10107-024-02175-z) · [arXiv](https://arxiv.org/abs/2312.09789)

---

## s3vm-mixing-c

[s3vm-mixing-c](https://github.com/jschwiddessen/s3vm-mixing-c) is a parallel C implementation of a mixing-method variant solving the basic SDP relaxation of semi-supervised support vector machine (S3VM) models, including variable bound computations.

It is research code that will be discussed in my upcoming PhD thesis.

---

## SRFLP-BB

[SRFLP-BB](https://github.com/jschwiddessen/SRFLP-BB) is a C implementation of a parallel branch-and-bound (B&B) solver for the single-row facility layout problem (SRFLP) using semidefinite programming bounds.

The solver is exact and always finds the optimal solution when terminating. Moreover, the branch-and-bound implementation is parallelized using POSIX Threads.

Check out my master's thesis [PDF](/assets/pdfs/master_thesis.pdf) for details about the single-row facility layout problem and its semidefinite programming relaxations.

---

## mastermind-solver

[mastermind-solver](https://github.com/jschwiddessen/mastermind-solver) implements an artificial intelligence (AI) engine for playing the board game _Mastermind_. It is fully parallelized using OpenMP and you can choose between two engine modes: optimizing the average case or the worst case.
