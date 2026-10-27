# 🧬 Finding Hidden Messages in DNA (Bioinformatics I)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Bioinformatics](https://img.shields.io/badge/Bioinformatics-Computational_Biology-brightgreen?style=for-the-badge)
![Algorithms](https://img.shields.io/badge/Algorithms-String_Matching_%7C_Randomized-blue?style=for-the-badge)

## 📌 Project Overview
This repository contains my algorithmic implementations and computational workflows developed during the Coursera course **Finding Hidden Messages in DNA (Bioinformatics I)**. 

The codebase bridges computer science and biology by applying string processing, pattern matching, and randomized algorithms to decode complex biological languages, analyze DNA replication, and identify regulatory motifs in genomic data.

## 🔬 Core Algorithms & Computational Biological Problems

### 1. DNA Replication Origin Prediction
*   **Biological Problem:** Identifying the precise genomic coordinates where DNA replication begins in bacterial genomes.
*   **Algorithmic Approach:** Implemented sliding window algorithms, frequency arrays, and GC-skew array calculations to locate "hidden messages" (DnaA boxes) and predict the origin of replication (oriC).

### 2. Molecular Clocks & Motif Finding
*   **Biological Problem:** Discovering hidden DNA patterns that regulate gene expression and maintain circadian rhythms.
*   **Algorithmic Approach:** Designed and deployed probabilistic and randomized algorithms—including Gibbs Sampling and Greedy Motif Search—to score, profile, and identify recurring regulatory motifs within complex genomic sequences.

### 3. Applied Pathogen Analysis (*Mycobacterium tuberculosis*)
*   **Biological Problem:** Locating biological motifs responsible for triggering dormancy in *Mycobacterium tuberculosis*, allowing it to evade host immune systems.
*   **Algorithmic Approach:** Integrated existing bioinformatics command-line software to parse real-world genetic data and extract survival-critical sequence motifs.

## 🛠️ Tech Stack & Environment
*   **Language:** Python 3.10
*   **Core Concepts:** Algorithmic Design, Probabilistic Models, String Manipulation, Pattern Recognition
*   **Bioinformatics Tools:** Command-line sequence analysis utilities

## 🚀 Quick Start
Clone the repository to explore the algorithmic solutions. 

```bash
# Clone the repository
git clone [https://github.com/rahuldgofficial/Bioinformetics-1.git](https://github.com/rahuldgofficial/Bioinformetics-1.git)
cd bioinformetics-1

# Recommended: Run inside an isolated environment (e.g., Micromamba/Conda)
micromamba create -n bio_env python=3.10
micromamba activate bio_env
