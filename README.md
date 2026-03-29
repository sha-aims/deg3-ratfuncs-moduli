# deg3-ratfuncs-moduli
[<image-card alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" ></image-card>](https://opensource.org/licenses/MIT)
[<image-card alt="arXiv" src="https://img.shields.io/badge/arXiv-2503.10835-b31b1b.svg" ></image-card>](https://arxiv.org/abs/2503.10835)

**Software for Computing Moduli and Automorphism Groups of Degree-3 Rational Functions**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![arXiv](https://img.shields.io/badge/arXiv-2503.10835-b31b1b.svg)](https://arxiv.org/abs/2503.10835)

This repository contains the complete open-source SageMath/Python software accompanying the paper 
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
## Quick Start

```python
# Load the core library
run notebooks/deg3F.ipynb

# Example usage
q = [0, 1, 0, 0, 1, a, b, 1]
p = inv(q)
print(AutGroup(p))      # e.g. "C3"
print(wheight(p))
---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sha-aims/deg3-ratfuncs-moduli.git
   cd deg3-ratfuncs-moduli
