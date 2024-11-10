---
title: "SECRET-GWAS: Confidential Computing for Population-Scale GWAS"
date:
image: 
tags: ["CITEME"]
description: 
draft: false
---
@article {Rosenblum2024.04.24.590989,
	author = {Rosenblum, Jonah and Dong, Juechu and Narayanasamy, Satish},
	title = {SECRET-GWAS: Confidential Computing for Population-Scale GWAS},
	elocation-id = {2024.04.24.590989},
	year = {2024},
	doi = {10.1101/2024.04.24.590989},
	publisher = {Cold Spring Harbor Laboratory},
	abstract = {Genomic data from a single institution lacks global diversity representation, especially for rare variants and diseases. Confidential computing can enable collaborative GWAS without compromising privacy or accuracy, however, due to limited secure memory space and performance overheads previous solutions fail to support widely used regression methods. We present SECRET-GWAS: a rapid, privacy-preserving, population-scale, collaborative GWAS tool. We discuss several system optimizations, including streaming, batching, data parallelization, and reducing trusted hardware overheads to efficiently scale linear and logistic regression to over a thousand processor cores on an Intel SGX-based cloud platform. In addition, we protect SECRET-GWAS against several hardware side-channel attacks, including Spectre, using data-oblivious code transformations and optimized speculative load hardening. SECRET-GWAS is an open-source tool and works with the widely used Hail genomic analysis framework. Our experiments on Azure{\textquoteright}s Confidential Computing platform demonstrate that SECRET-GWAS enables multivariate linear and logistic regression GWAS queries on population-scale datasets (one million patients, four million SNPs, 12 covariates) from ten independent sources in just 4.5 and 29 minutes, respectively.Competing Interest StatementThe authors have declared no competing interest.},
	URL = {https://www.biorxiv.org/content/early/2024/04/28/2024.04.24.590989},
	eprint = {https://www.biorxiv.org/content/early/2024/04/28/2024.04.24.590989.full.pdf},
	journal = {bioRxiv}
}
