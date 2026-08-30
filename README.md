# STAT 645 — Statistical Computing

Course repository for **STAT 645: Statistical Computing**.

This repository contains assignments, projects, R code, and exploratory notebooks developed during the course.

## Development Environment

The primary language for the course is **R**.

The development environment includes:

* **R 4.6**
* **RStudio**
* **R Markdown**
* **knitr**
* **JupyterLab**
* **IRkernel** for running R notebooks in Jupyter

RStudio is used primarily for course materials and R Markdown documents, while JupyterLab provides an additional environment for exploratory statistical computing.

## Repository Structure

```text
Stat645/
├── Assignments/     # Course assignments
├── Projects/        # Statistical computing projects
├── .gitignore
└── README.md
```

Instructor-provided lecture materials are maintained locally in a `Lectures/` directory and are not included in this repository.

## R Markdown

Course assignments may use **R Markdown (`.Rmd`)** with `knitr` to combine:

* R code
* Markdown
* Mathematical notation
* Statistical output
* Tables and figures

R Markdown documents can be rendered to formats such as HTML and PDF.

## Jupyter Notebooks

JupyterLab is configured with an **R kernel (IRkernel)** for exploratory analysis and practice.

Notebook files (`.ipynb`) may be used to investigate statistical concepts interactively before incorporating finalized analysis into course assignments or projects.

## Reproducibility

Source files are version controlled with Git. Temporary R workspace files, command history, RStudio state, and Jupyter checkpoint files are excluded from the repository.

The goal is to keep analyses reproducible from the source code and data rather than relying on saved R workspace state.

## Topics

Topics and examples will be added as the course progresses.
