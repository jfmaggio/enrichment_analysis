# Enrichment Analysis

This repository contains a collection of scripts and workflows designed to perform **Functional Enrichment Analysis** from differential expression results (RNA-Seq). It focuses on identifying biological pathways, gene ontologies, and molecular signatures that are significantly overrepresented in specific gene sets.

## 📊 Overview

The main objective of this project is to streamline the transition from a list of differentially expressed genes (DEGs) to biological interpretation. 

Key features include:
- **Over-Representation Analysis (ORA)**: Using hypergeometric tests to find enriched terms.
- **Visualization**: Generation of dot plots, enrichment plots (GSEA curves), and bar plots for results interpretation.

## 🛠️ Tools & Libraries

The analysis is primarily implemented Python:
- `clusterProfiler`: For ORA.
- `org.Hs.eg.db`: For genome-wide annotation (Human).
- `enrichplot`: For advanced visualization of enrichment results.
- `ggplot2`: For custom data plotting.

## 📂 Project Structure

- `data/`: Contains input files.
- `scripts/`: R scripts for data processing and running the enrichment algorithms.
- `results/`: Output tables and high-resolution figures.

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/jfmaggio/enrichment_analysis.git