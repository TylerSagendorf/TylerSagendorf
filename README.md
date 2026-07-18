# Select Work

## Code Repositories

- [High-performance gene set enrichment analysis R package](https://github.com/pnnl/fast.ssgsea)
  - Highly optimized variant of pre-ranked gene set enrichment analysis (GSEA), written in R, C, and C++.
  - Capable of testing standard gene set databases, as well as directional databases where each gene (or biomolecule) has an expected direction of change derived from prior experiments.
  - **Tens of thousands to hundreds of thousands of times faster** than the existing implementation ([broadinstitute/ssGSEA2.0](https://github.com/broadinstitute/ssGSEA2.0)) and hundreds of times faster than the simple implementation of Fast Gene Set Enrichment Analysis (FGSEA-simple).

- [Fast list to sparse incidence matrix converter](https://github.com/TylerSagendorf/list2mat)
  - R code that converts a named list of character vectors to a sparse incidence matrix.

## Other Contributions

- `collapse` R package:
  - Implemented SIMD optimizations to improve performance of `fsum()` and `fmean()`: [link to collapse v2.1.7 release notes](https://github.com/fastverse/collapse/releases/tag/v2.1.7)
