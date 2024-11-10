---
title: "mm2-gb: GPU Accelerated Minimap2 for Long Read DNA Mapping"
date: 
image: 
tags: ["CITEME"]
description:
draft: false
---
@article {Dong2024.03.23.586366,
	author = {Dong, Juechu and Liu, Xueshen and Sadasivan, Harisankar and Sitaraman, Sriranjani and Narayanasamy, Satish},
	title = {mm2-gb: GPU Accelerated Minimap2 for Long Read DNA Mapping},
	elocation-id = {2024.03.23.586366},
	year = {2024},
	doi = {10.1101/2024.03.23.586366},
	publisher = {Cold Spring Harbor Laboratory},
	abstract = {Long-read DNA sequencing is becoming increasingly popular for genetic diagnostics. Minimap2 is the state-of-the-art long-read aligner. However, Minimap2{\textquoteright}s chaining step is slow on the CPU and takes 40-68\% of the time especially for long DNA reads. Prior works in accelerating Minimap2 either lose mapping accuracy, are closed source (and not updated) or deliver inconsistent speedups for longer reads. We introduce mm2-gb which accelerates the chaining step of Minimap2 on GPU without compromising mapping accuracy. In addition to intra- and inter-read parallelism exploited by prior works, mm2-gb exploits finer levels of parallelism by breaking down high latency large workloads into smaller independent segments that can be run in parallel and leverages several strategies for better workload balancing including split-kernels and prioritized scheduling of segments based on sorted size. We show that mm2-gb on an AMD Instinct{\texttrademark} MI210 GPU achieves 2.57-5.33x performance improvement on long nanopore reads (10kb-100kb), and 1.87x performance gain on super long reads (100kb-300kb) compared to SIMD accelerated mm2-fast. mm2-gb is open-sourced and available at https://github.com/Minimap2onGPU/minimap2.Competing Interest StatementThe authors have declared no competing interest.},
	URL = {https://www.biorxiv.org/content/early/2024/03/27/2024.03.23.586366},
	eprint = {https://www.biorxiv.org/content/early/2024/03/27/2024.03.23.586366.full.pdf},
	journal = {bioRxiv}
}
