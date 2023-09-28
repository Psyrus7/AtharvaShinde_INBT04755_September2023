# This project is strictly made for internship purpose for the company " iNeuBytes " by Atharva Shinde

# Machine Learning Project with Iris Dataset

## Overview

This repository contains the source code and documentation for a machine learning project focused on the Iris dataset. The project involves loading the dataset, splitting it, training supervised models, evaluating their performance, and applying unsupervised K-means clustering for clustering analysis.

## Table of Contents

- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Project Description](#project-description)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Structure

The project is organized as follows:

- `notebooks/`: Jupyter notebooks containing code and analysis.
- `data/`: Data files and datasets used in the project.
- `src/`: Source code for machine learning models and utility functions.
- `requirements.txt`: List of Python dependencies required to run the code.

## Installation

To run this project locally, you need to set up a Python environment and install the required dependencies. You can use the following steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Psyrus7/AtharvaShinde_INBT04755_September2023.git
   ```

2. Navigate to the project directory:

   ```bash
   cd AtharvaShinde_INBT04755_September2023
   ```

3. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source venv/bin/activate
     ```

5. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

Once you've set up the environment and installed the dependencies, you can run the project code. The primary entry points are Jupyter notebooks in the `notebooks/` directory. Use these notebooks to explore and execute the code.

```bash
jupyter notebook
```

## Project Description

This machine learning project focuses on the Iris dataset, a well-known dataset in the field of data science and machine learning. Here's a brief overview of the project's main components:

1. **Data Loading and Splitting:**
   - The dataset is loaded and split into training and testing sets.
   - Three supervised machine learning models are trained: Support Vector Machine (SVC), Decision Tree, and Random Forest.

2. **Evaluation of Classification Models:**
   - Metrics such as confusion matrix, accuracy, precision, and recall are used to evaluate model performance.
   - A custom function is provided for streamlined evaluation.

3. **Additional Model Evaluation:**
   - Models are evaluated on both training and testing sets to assess overfitting.

4. **Unsupervised Learning (K-means Clustering):**
   - K-means clustering is applied to identify natural clusters within the dataset.
   - Cluster results are visualized for further insights.

## Results

The project results, including model evaluation metrics and clustering insights, can be found in the Jupyter notebooks in the `notebooks/` directory. Detailed documentation and analysis are provided within the notebooks.

## Contributing

If you'd like to contribute to this project, please follow the standard GitHub fork and pull request workflow. We welcome contributions, bug fixes, and improvements.

