# Awesome In Silico Modelling [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A carefully curated list with papers and code regarding in silico perturbation modelling and gene regulatory network (GRN) inference

This list focuses on computational approaches to model cellular responses to perturbations and infer gene regulatory networks, primarily from single-cell RNA sequencing data and related omics modalities.

## Contents

- [Perturbation Modelling](#perturbation-modelling)
  - [Transformer-Based Models](#transformer-based-models)
  - [Variational & Latent Models](#variational--latent-models)
  - [Optimal Transport & Manifold Methods](#optimal-transport--manifold-methods)
  - [Graph & Attention Models](#graph--attention-models)
- [Gene Regulatory Network Inference](#gene-regulatory-network-inference)
  - [Single-Cell Methods](#single-cell-methods)
  - [Tree-Based & Ensemble Methods](#tree-based--ensemble-methods)
  - [Deep Learning Approaches](#deep-learning-approaches)
- [Benchmarks & Evaluation](#benchmarks--evaluation)
- [Reviews & Surveys](#reviews--surveys)
- [Datasets](#datasets)
- [Software & Tools](#software--tools)

## Perturbation Modelling

### Transformer-Based Models

- **scGPT** (2024) — Foundation model for single-cell multi-omics using generative AI with perturbation prediction capabilities. [[paper](https://www.nature.com/articles/s41592-024-02201-0)] [[code](https://github.com/bowang-lab/scGPT)]
- **Geneformer** (2023) — Transformer encoder pretrained on single-cell transcriptomes for in silico gene perturbations and network analysis. [[paper](https://www.nature.com/articles/s41586-023-06139-9)] [[code](https://huggingface.co/ctheodoris/Geneformer)]
- **scGenePT** (2024) — Language-enriched embeddings for single-cell perturbation prediction with comprehensive tutorial resources. [[paper](https://www.biorxiv.org/content/10.1101/2024.10.23.619972v1)] [[code](https://github.com/czi-ai/scGenePT)]
- **scFoundation** (2023) — Large-scale foundation model on single-cell transcriptomics with perturbation modeling capabilities. [[paper](https://www.biorxiv.org/content/10.1101/2023.05.29.542705v2)]
- **Mouse-Geneformer** (2025) — Species-specific variant demonstrating cross-species perturbation experiments. [[paper](https://journals.plos.org/plosgenetics/article?id=10.1371%2Fjournal.pgen.1011420)]

### Variational & Latent Models

- **scGen** (2019) — VAE with latent arithmetic for cross-cell-type and cross-species perturbation prediction. [[paper](https://www.nature.com/articles/s41592-019-0494-8)] [[code](https://github.com/theislab/scgen)]
- **trVAE** (2020) — Conditional VAE for out-of-distribution perturbation generation and batch integration. [[paper](https://academic.oup.com/bioinformatics/article/36/Supplement_2/i610/6055927)]
- **CPA** (2023) — Compositional Perturbation Autoencoder for drug combinations, dosages, and unseen compounds. [[paper](https://www.embopress.org/doi/abs/10.15252/msb.202211517)]
- **scCausalVI** (2025) — Causality-aware generative model for disentangling perturbation responses. [[paper](https://www.biorxiv.org/content/10.1101/2025.02.02.636136v1)]
- **CoupleVAE** (2025) — Coupled variational autoencoders for predicting perturbation responses with uncertainty quantification. [[paper](https://academic.oup.com/bib/article/26/2/bbaf126/8104857)]

### Optimal Transport & Manifold Methods

- **CellOT** (2023) — Neural optimal transport for learning cellular responses to perturbations with unpaired data. [[paper](https://www.nature.com/articles/s41592-023-01969-x)]
- **sc-OTGM** (2024) — Single-cell perturbation modeling by solving optimal transport on Gaussian mixture manifolds. [[paper](https://arxiv.org/abs/2405.03726)]
- **Conditional Monge Gap** (2025) — Generalizable perturbation modeling via conditional optimal transport. [[paper](https://arxiv.org/abs/2504.08328)]
- **W1 Neural OT Solver** (2024) — Fast and scalable Wasserstein-1 solver for perturbation prediction. [[paper](https://academic.oup.com/bioinformatics/article/41/Supplement_1/i513/8199349)]

### Graph & Attention Models

- **GEARS** (2023) — Graph-based model predicting transcriptional outcomes of novel multigene perturbations. [[paper](https://www.nature.com/articles/s41587-023-01905-6)]
- **scPRAM** (2024) — Attention mechanism-based model for perturbation response prediction. [[paper](https://academic.oup.com/bioinformatics/article/doi/10.1093/bioinformatics/btae265/7646141)]
- **BioDSNN** (2024) — Dual-stream neural network with biological knowledge integration for multi-gene perturbations. [[paper](https://academic.oup.com/bib/article/doi/10.1093/bib/bbae617/7908004)]

## Gene Regulatory Network Inference

### Single-Cell Methods

- **SCENIC** (2017) — Single-cell regulatory network inference and clustering via regulon discovery. [[paper](https://www.nature.com/articles/nmeth.4463)] [[code](https://github.com/aertslab/SCENIC)]
- **pySCENIC** — Python implementation of SCENIC with enhanced performance and scalability. [[code](https://github.com/aertslab/pySCENIC)]
- **SCENIC+** (2023) — Multi-omic extension integrating enhancer-gene regulatory circuits. [[paper](https://www.nature.com/articles/s41592-023-01938-4)]
- **scSGL** (2022) — Kernelized signed graph learning for single-cell GRN inference with activating/inhibitory relationships. [[paper](https://academic.oup.com/bioinformatics/article/38/11/3011/6572335)]
- **PMF-GRN** (2024) — Variational inference approach using probabilistic matrix factorization. [[paper](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-024-03226-6)]

### Tree-Based & Ensemble Methods

- **GENIE3** (2010) — Tree-based ensemble method for gene regulatory network inference. [[paper](https://journals.plos.org/plosone/article?id=10.1371%2Fjournal.pone.0012776)]
- **Inferelator 3.0** (2021) — Scalable single-cell gene regulatory network inference with latent transcription factor activities. [[paper](https://www.biorxiv.org/content/10.1101/2021.05.03.442499v1)]

### Deep Learning Approaches

- **HGATLink** (2025) — Heterogeneous graph attention networks with transformer for GRN inference. [[paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-025-06071-x)]
- **CVGAE** (2024) — Self-supervised generative approach for GRN inference from scRNA-seq data. [[paper](https://link.springer.com/10.1007/s12539-024-00633-y)]

## Benchmarks & Evaluation

- **Benchmarking Foundation Models** (2025) — Systematic evaluation of foundation models for post-perturbation RNA-seq prediction. [[paper](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-025-11600-2)]
- **Systematic Comparison** (2024) — Comprehensive comparison of single-cell perturbation response prediction models. [[paper](https://www.biorxiv.org/content/10.1101/2024.12.23.630036v1)]
- **scArchon** (2025) — Benchmarking platform for tracking biological hallucinations in perturbation predictions. [[paper](https://www.biorxiv.org/content/10.1101/2025.06.23.661046v1)]
- **scEval** — Standardized evaluation framework for single-cell analysis methods including perturbation prediction. [[link](https://sites.google.com/yale.edu/sceval/task-results/gene-perspective-tasks/perturbation-prediction)]

## Reviews & Surveys

- **Perturbation Modelling Review** (2024) — Mini-review on perturbation modelling across single-cell omic modalities. [[paper](https://www.sciencedirect.com/science/article/pii/S2001037024001417)]
- **Machine Learning for Perturbations** (2024) — Comprehensive review on machine learning approaches to dissect cellular perturbations. [[paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC11915099/)]
- **GRN Benchmarking Approaches** (2023) — Survey of benchmarking methods for single-cell gene regulatory network inference. [[paper](https://www.semanticscholar.org/paper/e75f54c44241cfe95d1d065fd87b2915e0f3c00e)]

## Datasets

- **Perturb-seq** — CRISPR-based perturbation experiments with single-cell readouts
- **sci-Plex** — Single-cell combinatorial indexing for chemical perturbations
- **CRISPRa/i screens** — Activation and interference screens with scRNA-seq
- **Drug perturbation datasets** — Chemical compound treatments with single-cell profiling

## Software & Tools

- **Scanpy** — Single-cell analysis toolkit with perturbation modeling utilities. [[code](https://github.com/scverse/scanpy)]
- **CellOracle** — In silico gene perturbation analysis using GRNs. [[code](https://github.com/morris-lab/CellOracle)]
- **BEELINE** — Evaluation framework for gene regulatory network inference methods. [[code](https://github.com/murali-group/Beeline)]
- **Single-cell best practices** — Community guidelines including perturbation modeling workflows. [[link](https://www.sc-best-practices.org/conditions/perturbation_modeling.html)]

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.