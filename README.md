# Introductory Bioinformatics with R

This repository contains a set of practical Jupyter notebooks developed while following the free Persian course **“مقدمه‌ای بر بیوانفورماتیک (تحلیل داده‌های زیستی)”** (*Introduction to Bioinformatics: Biological Data Analysis*) by **Ali Sharifi Zarchi (علی شریفی زارچی)**, available on **Maktabkhooneh**.

The main purpose of this repository is educational. It can be considered a **dynamic and practical course notebook**: a place where the concepts from the course are implemented, tested, visualized, and organized as reproducible hands-on exercises using R.

## Project Overview

The notebooks cover introductory bioinformatics and data analysis concepts using R, with a focus on working with biological/gene-expression data. The project starts from basic R programming and gradually moves toward data handling, visualization, exploratory analysis, and statistical testing.

The repository includes:

- Practical Jupyter notebooks for course sessions
- A sample biological dataset (`Endoderm.txt`)
- Example outputs from data visualization
- R-based workflows for exploratory analysis and basic statistics

## Educational Source and Attribution

This repository is based on practical learning from the free Maktabkhooneh course:

**Course:** [مقدمه‌ای بر بیوانفورماتیک (تحلیل داده‌های زیستی)](https://maktabkhooneh.org/course/%D9%85%D9%82%D8%AF%D9%85%D9%87-%D8%A8%DB%8C%D9%88%D8%A7%D9%86%D9%81%D9%88%D8%B1%D9%85%D8%A7%D8%AA%DB%8C%DA%A9-%D8%AA%D8%AD%D9%84%DB%8C%D9%84-%D8%AF%D8%A7%D8%AF%D9%87-%D8%B2%DB%8C%D8%B3%D8%AA%DB%8C-mk374/)  
**Instructor:** [Ali Sharifi Zarchi (علی شریفی زارچی)](https://maktabkhooneh.org/teacher/%D8%B9%D9%84%DB%8C-%D8%B4%D8%B1%DB%8C%D9%81%DB%8C-%D8%B2%D8%A7%D8%B1%DA%86%DB%8C/)  
**Platform:** [Maktabkhooneh](https://maktabkhooneh.org/)

The notebooks in this repository reflect my own practical implementation, organization, and learning process based on the course material. This repository is not intended to replace the original course, but rather to document my hands-on practice and progress in introductory bioinformatics with R.

## Repository Structure

```text
introductory-bioinformatics-with-R/
│
├── all jupyter notebooks/
│   ├── intro bioinf sharifi practical 1.ipynb
│   ├── intro bioinf sharifi practical 2.ipynb
│   ├── ...
│   └── intro bioinf sharifi practical 12.ipynb
│
├── some results of data visualisation/
│   └── Example visualization outputs
│
├── Endoderm.txt
├── README.md
├── LICENSE
└── .gitignore
```

## Topics Covered

The notebooks include hands-on practice with:

- Basic R syntax and variables
- Vectors, data frames, and indexing
- Reading and inspecting biological datasets
- Data transformation and preprocessing
- Log transformation of gene-expression values
- Exploratory data analysis
- Data visualization using base R and `ggplot2`
- Boxplots, violin plots, bar plots, heatmaps, and PCA plots
- Correlation analysis, including Pearson and Spearman correlation
- Use of `apply`, `sapply`, and custom functions
- Principal component analysis (PCA)
- Basic statistical testing
- Normality testing
- t-test, Wilcoxon test, and ANOVA

## Dataset

The repository uses a small gene-expression dataset named:

```text
Endoderm.txt
```

This dataset is used across the notebooks to practice data import, transformation, visualization, and basic statistical analysis in R.

## Example Outputs

Some visualization outputs are saved in the folder:

```text
some results of data visualisation/
```

Examples include plots such as:

- Heatmaps
- PCA plots
- Correlation heatmaps
- Boxplots
- Bar plots generated with `ggplot2`

## Tools and Environment

This project mainly uses:

- R
- Jupyter Notebook
- R kernel for Jupyter
- `ggplot2`
- Basic R statistical functions
- Data visualization packages used during the practical sessions

## How to Use This Repository

1. Clone the repository:

```bash
git clone https://github.com/AbolDpirate/introductory-bioinformatics-with-R.git
```

2. Open the repository folder:

```bash
cd introductory-bioinformatics-with-R
```

3. Open the notebooks in Jupyter Notebook or JupyterLab.

4. Make sure that the required R packages are installed before running the notebooks.

5. Run the notebooks step by step to follow the learning workflow.

## Notes for Reproducibility

Some notebooks may contain local file paths from the original working environment. For smoother reproducibility, these paths can be replaced with relative paths such as:

```r
read.table("Endoderm.txt", header = TRUE)
```

This makes the notebooks easier to run after cloning the repository.

## Purpose of This Repository

This repository demonstrates my learning progress in introductory bioinformatics and R-based biological data analysis. It is useful as:

- A practical learning archive
- A dynamic course notebook
- A beginner-friendly R bioinformatics practice repository
- A reference for basic biological data analysis workflows

## Future Improvements

Possible future updates include:

- Cleaning and standardizing file paths
- Adding package installation instructions
- Adding short explanations at the beginning of each notebook
- Organizing notebooks by topic
- Adding more comments to improve readability
- Expanding the project with additional biological datasets

## License

This repository includes an MIT License for the code and materials created or organized in this repository. The original educational course content is credited to the instructor and platform listed above.
