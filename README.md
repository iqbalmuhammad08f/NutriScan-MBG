# Capstone Project

This repository contains the codebase and resources for the capstone project. 

## Project Structure

- `notebook.ipynb`: Main Jupyter Notebook containing data preprocessing, model experimentation, and analysis (incorporating tools like OpenCV, Scikit-learn, and COCO utilities).
- `dataset/`: Directory to store input datasets.
- `ompreng_mbg_coco/`: Directory containing data structured in COCO format.
- `requirements.txt`: List of Python dependencies required to run the project.

## Prerequisites

Before running the notebook, ensure you have Python installed. It is highly recommended to use a virtual environment to manage dependencies.

## Installation

1. **Set up a virtual environment (optional but recommended):**
   ```bash
   python -m venv .venv
   
   # On Windows
   .venv\Scripts\activate
   
   # On macOS/Linux
   source .venv/bin/activate
   ```

2. **Install required libraries:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Activate your virtual environment (if used).
2. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `notebook.ipynb` in your browser and execute the cells.
