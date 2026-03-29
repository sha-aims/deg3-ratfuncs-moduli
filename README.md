# deg3-ratfuncs-moduli

**Software for Computing Moduli and Automorphism Groups of Degree-3 Rational Functions**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![arXiv](https://img.shields.io/badge/arXiv-2503.10835-b31b1b.svg)](https://arxiv.org/abs/2503.10835)

This repository contains the complete open-source software accompanying the paper  
**"Software for Computing Moduli and Automorphism Groups of Degree-3 Rational Functions"** by Tony Shaska.

It implements:
- Computation of the six absolute invariants \(\xi_0, \dots, \xi_5\)
- Detection of automorphism groups via algebraic loci \(L_1,\dots,L_7\)
- Enumeration of rational functions of bounded height
- Explicit locus equations via Gröbner bases
- Machine-learning classification experiments (99.992% accuracy)

---

## Contents

- `notebooks/` — five SageMath/Python Jupyter notebooks
- `data/` — pre-computed dataset (2,078,697 rational functions, naive height ≤ 4)
- Full implementation of the theoretical framework from [arXiv:2503.10835](https://arxiv.org/abs/2503.10835)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sha-aims/deg3-ratfuncs-moduli.git
   cd deg3-ratfuncs-moduli
