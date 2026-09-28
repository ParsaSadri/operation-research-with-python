# Operations Research with Python

A practical collection of **Operations Research (OR)** course materials and Python-based implementations, including mathematical modeling, optimization, sensitivity analysis, network optimization, and decision-making.

This repository is designed to connect the fundamental concepts of Operations Research with practical computational implementations in Python.

## About the Course

This course material has been prepared based on the structure and topics of the **Operations Research course taught by Dr. Golroo at Amirkabir University of Technology (Tehran Polytechnic)**, with an emphasis on implementing and exploring the concepts using Python.

The purpose of this repository is to provide a practical computational companion to the theoretical concepts of Operations Research. Instead of relying solely on traditional tools such as spreadsheet-based optimization, the notebooks demonstrate how OR concepts can be formulated, analyzed, and implemented programmatically.

## Syllabus

The current repository covers the following topics:

1. **Operations Research Problem Definition**
2. **Operations Research Problem Solutions**
3. **Assumptions of Operations Research Models**
4. **Shadow Price**
5. **Dual Problem**
6. **Sensitivity Analysis**
7. **Network Optimization**
8. **Decision Making**
9. **Genetic Algorithm**

The course is developed progressively, starting from the formulation and understanding of Operations Research problems and moving toward optimization analysis, network models, decision-making, and computational optimization methods.

## Notebooks

### 01 — OR Problem Definition

`01-OR-Problem-Definition.ipynb`

Introduces the process of defining an Operations Research problem and translating a real-world problem into a mathematical optimization model.

### 02 — OR Problem Solutions

`02-OR-Problem-Solutions.ipynb`

Explores approaches for solving formulated Operations Research problems and demonstrates computational solution methods using Python.

### 03 — OR Problem Assumptions

`03-OR-Problem-Assumptions.ipynb`

Covers the assumptions underlying Operations Research and optimization models and discusses their role in constructing valid mathematical formulations.

### 04 — Shadow Price

`04-OR-Shadow-Price.ipynb`

Introduces the concept of **Shadow Price** and its interpretation in optimization models, particularly in understanding the marginal value of available resources.

### 05 — Dual Problem

`05-OR-Dual-Problem.ipynb`

Introduces the concept of the **Dual Problem** and its relationship with the original optimization problem, providing a computational perspective on primal-dual formulations.

### 06 — Sensitivity Analysis

`06-OR-Sensitivity-Analysis.ipynb`

Explores **Sensitivity Analysis** and examines how changes in model parameters can affect an optimization problem and its solution.

### 07 — Network Optimization

`07-OR-Network-Optimization.ipynb`

Introduces **Network Optimization** problems and demonstrates computational approaches for working with network-based optimization models.

The repository also includes:

`data/tehran_drive.graphml`

which provides graph/network data used in the network optimization material.

### 08 — Decision Making

`08-OR-Desicion-Making.ipynb`

Covers concepts related to **Decision Making** in Operations Research and demonstrates computational approaches for analyzing decision problems.

### 09 — Genetic Algorithm

`09-OR-Genetics-Algorithm.ipynb`

Introduces **Genetic Algorithms** as a computational optimization approach and demonstrates their application using Python.

## Repository Structure

```text
operations-research-with-python/
│
├── notebooks/
│   ├── 01-OR-Problem-Definition.ipynb
│   ├── 02-OR-Problem-Solutions.ipynb
│   ├── 03-OR-Problem-Assumptions.ipynb
│   ├── 04-OR-Shadow-Price.ipynb
│   ├── 05-OR-Dual-Problem.ipynb
│   ├── 06-OR-Sensitivity-Analysis.ipynb
│   ├── 07-OR-Network-Optimization.ipynb
│   ├── 08-OR-Desicion-Making.ipynb
│   └── 09-OR-Genetics-Algorithm.ipynb
│
├── data/
│   └── tehran_drive.graphml
│
├── requirements.txt
└── README.md
```

## Python Environment

The notebooks use Python and a collection of scientific computing and optimization libraries.

The required packages are listed in:

```text
requirements.txt
```

To install the required dependencies:

```bash
pip install -r requirements.txt
```

## How to Use

Clone the repository:

```bash
git clone https://github.com/parsasadri/operations-research-with-python.git
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Then open the notebooks using Jupyter Notebook, JupyterLab, or another compatible environment.

```bash
jupyter notebook
```

## Learning Approach

The main focus of this repository is to combine:

* Operations Research concepts
* Mathematical modeling
* Optimization
* Python programming
* Computational problem solving
* Practical interpretation of optimization results

The notebooks are intended to be used alongside the theoretical study of Operations Research, providing a bridge between mathematical concepts and computational implementation.

## Course Reference

The structure and subject coverage of this material are based on the **Operations Research course taught by Dr. Golroo at Amirkabir University of Technology**.

The Python implementations and organization of this repository are part of an independent educational effort to make Operations Research concepts more practical and computational.

## Author

**Parsa Sadri**
**Based on OR course taught by Dr. Golroo at Amirkabir University of Technology (Tehran Polytechnic)**

This repository is developed as an educational project for learning and practicing Operations Research with Python.

These materials can also be used as supplementary resources for **course review sessions, teaching assistant (TA) classes, and practical exercises** in Operations Research.
