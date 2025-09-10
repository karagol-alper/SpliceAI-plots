# SpliceAI-plots

This repository provides Python scripts and examples to visualize very long, sparse datasets (millions of rows, mostly zeros).
It includes optimized static plotting with matplotlib and seaborn for publication-quality figures.

# 📊 Features

Heatmap visualization of large, sparse data

Non-zero focused heatmaps (zeros hidden)

Custom colormaps for better contrast

Line plots and stacked area plots for trends

Automatic downsampling of x-axis ticks (clean labels even for long data)


# 📂 Example Data Format

Input file should be tab-separated with an index column and multiple numeric columns:

Index   Col1   Col2   Col3   Col4
1       0.00   0.00   0.00   0.00
2       0.00   0.00   0.01   0.00
3       0.00   0.00   0.00   0.00
...
