# Document Similarity Algorithm Comparison

This project compares different similarity algorithms used in text analysis, focusing on Cosine Similarity and Jaccard Similarity. It also explores the use of Strassen's algorithm for matrix multiplication in the context of all-pairs similarity calculations.

## Table of Contents

1. [Introduction](#introduction)
2. [Requirements](#requirements)
3. [Project Structure](#project-structure)
4. [Algorithms Analyzed](#algorithms-analyzed)
5. [Key Findings](#key-findings)
6. [Usage](#usage)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

In the field of data science, efficiently handling and analyzing large amounts of text data is crucial. This project delves into the world of algorithmic efficiency, comparing and contrasting algorithms used for finding similarities between documents. The study focuses on Cosine and Jaccard similarity measures and explores Strassen's algorithm for potential application in calculating all-pairs cosine similarity.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- joblib

You can install the required packages using:
pip install pandas numpy matplotlib joblib

## Project Structure

The project is divided into several sections:

1. Cosine Similarity Analysis
2. Jaccard Similarity Analysis
3. All-Pairs Similarity Analysis
4. Parallel Computing for All-Pairs Similarities
5. Strassen's Method Analysis

Each section includes both theoretical analysis and empirical testing.

## Algorithms Analyzed

- Cosine Similarity
- Jaccard Similarity
- Strassen's Algorithm for Matrix Multiplication

## Key Findings

The investigation into various computational approaches for similarity measures and matrix multiplication demonstrated the importance of aligning theoretical understanding with empirical testing. Theoretical efficiencies must be balanced with practical considerations like data characteristics and computational overhead. In my case, standard approaches and parallel computing provided the best performance for cosine similarity calculations and matrix multiplication tasks. This emphasizes the need for empirical validation in algorithm selection, especially in data science and machine learning applications, where data characteristics and environmental factors play a significant role in algorithm performance.

## Usage

1. Clone the repository:
git clone https://github.com/fesarikaya/SimilarityAlgorithms.git

2. Run the Jupyter notebook to reproduce the analysis.

## Author

Ferhat Sarikaya

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
