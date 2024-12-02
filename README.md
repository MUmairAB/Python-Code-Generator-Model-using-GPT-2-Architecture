# Causal Language Model for Python Code Generation

## Overview

The project aims to train a Causal Language Model (CLM) tailored for generating Python code. The goal is to enable the model to learn patterns, dependencies, and best practices in Python programming by leveraging a diverse and curated dataset of Python code. This initiative holds significant value for advancing automated code generation and contributing to broader AI research in software engineering.


## Motivation

Automated code generation can assist developers by providing accurate, context-sensitive code snippets, reducing repetitive coding tasks, and improving productivity.


## Project Scope

Given the vast ecosystem of Python libraries and frameworks, the model’s scope has been narrowed to cater specifically to Data Science libraries. This focused approach ensures optimized resource usage and processing time while delivering high accuracy for targeted tasks.

The model is tailored to the following key Data Science libraries:

  - **Pandas**: For data manipulation and analysis, providing powerful and flexible tools.
  - **Matplotlib**: To create static, interactive, and animated visualizations in Python.
  - **Seaborn**: Built on Matplotlib, designed to generate attractive and informative statistical graphics.
  - **Scikit-Learn**: A comprehensive library for machine learning tasks, offering robust algorithms and tools.
 

## Dataset Overview

The Codeparrot dataset serves as the backbone of this project. This dataset is sourced from public Python repositories on GitHub and includes diverse examples representing real-world programming practices.

  - **Training Subset**: A curated dataset comprising 5,000 samples to conserve computational resources while ensuring sufficient representativeness.
  - **Validation Subset**: 500 samples reserved to monitor performance during training.
  - **Features**: Each dataset entry includes fields like repository name, file path, number of copies, file size, content, and license.


## Objectives

  - Efficient Code Completion: Automate Python code generation to enhance efficiency for developers working with Data Science tasks.
  - Domain-Specific Optimization: Tailor the model’s understanding and output to the nuances of the targeted libraries.
  - Resource Efficiency: Narrow the scope to specific libraries to ensure faster training and inference.

By leveraging the capabilities of this Causal Language Model, we aim to create a robust tool for Python code generation that is particularly suited for the Data Science community.


#### Model artifacts can accessed on [HuggingFace](https://huggingface.co/MUmairAB/python-code-generator/tree/main).
