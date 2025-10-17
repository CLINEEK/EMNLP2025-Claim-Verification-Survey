# EMNLP 2025 Claim Verification Survey

A comprehensive survey analyzing claim verification research, including 316 papers and two in-depth case studies examining evidence-based verification and claim decomposition strategies.

## Repository Contents

- **`survey-paper-list.xlsx`** - Complete list of 316 papers included in the survey
- **`case-study1/`** - Annotation results for Case Study #1 (Evidence-Bearing Sentences)
- **`case-study2/`** - Annotation results for Case Study #2 (Claim Decomposition)

## Research Questions

This survey addresses three fundamental questions in claim verification research:

1. **What corpora are available for claim verification and how are they created?**
2. **What system designs and modeling strategies dominate current CV research?**
3. **What challenges persist in corpus and system development, and how can they be addressed?**

## Case Studies

### Case Study #1: Evidence-Bearing Sentences Analysis

Investigates how the **number and nature of evidence-bearing sentences (EBSs)** affect the difficulty of veracity annotation and verification.

**Datasets analyzed:**
- **HealthFC** (Vladika et al., 2024)
- **MSVEC** (Evans et al., 2023)
- **WiCE** (Kamoi et al., 2023)

**Focus:** Measures how many sentences typically support or refute a claim and evaluates inter-annotator consistency in veracity labeling.

### Case Study #2: Claim Decomposition

Examines how **decomposing complex claims into subclaims** influences the accuracy and interpretability of claim verification.

**Datasets analyzed:**
- **ClaimDecomp** (Chen et al., 2022)
- **FactLens** (Mitra et al., 2024)
- **WiCE** (Kamoi et al., 2023)

**Focus:** Assesses subclaim generation, evaluation methodologies, and aggregation strategies.

## Data Availability

- All datasets referenced in this survey are **publicly available**
- Repository includes metadata, analysis annotations, and summary materials
- Full annotation data available **upon request**

## Citation

If you use this work in your research, please cite our EMNLP 2025 paper:
```bibtex
@inproceedings{yourname2025claimverification,
  title={A Survey of Claim Verification: Corpora, Systems, and Challenges},
  author={Zhaxi Zerong, Chenxi Li, Xinyi Liu, Ju-hui Chen, Fei Xia},
  booktitle={Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing},
  year={2025}
}
```

## Contact

For questions or to request full annotation data, please contact zhaxizerong@gmail.com
