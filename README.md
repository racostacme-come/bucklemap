# BuckleMap

An original C++17/Python investigation of how rotational end restraint changes
the first buckling load of a slender elastic column, and how finite-element
eigenvalue error differs from an algebraic eigensolver residual.

Implementation and validation are in progress. This repository contains no
course handouts, solutions, private data, or copied teaching code.

## Development plan

1. `feat/column-eigenproblem`: native Hermite element, Python assembly, boundary
   conditions, analytical checks, API and CLI.
2. `validation/experiments-paper`: reproducible restraint/convergence study,
   academic manuscript, build tooling and CI.

Branches are merged only after their applicable checks pass. Git uses the
configured author identity and actual commit times.
