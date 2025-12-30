# Week 1 Python Assessment

## Problem Understanding
The task is to analyze a CSV file without using Pandas by manually reading and processing raw text data. The goal is to handle missing values, perform statistical calculations, and generate a summary report.

## Approach & Logic
The CSV file is read using file handling. The first row is treated as headers and the remaining rows as data. Columns are accessed dynamically using header names to avoid hardcoding indexes.

## Missing Value Handling
Missing values such as empty strings, NA, null, and None are ignored during calculations to prevent incorrect statistics and runtime errors.

## Why NumPy Was Used
NumPy was used only for statistical calculations (mean, median, standard deviation) because it provides accurate and efficient numerical operations.

## How to Run
```bash
python analysis.py
