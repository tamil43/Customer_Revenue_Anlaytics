
# Project Setup Guide

## 1. Prerequisites

Make sure you have:

- Python 3.x
- Git
- Jupyter Notebook or JupyterLab

## 2. Clone the Repository

```bash
git clone <your-github-repository-url>
cd customer-revenue-analytics
```

## 3. Install Dependencies

Install the required packages using:

```bash
pip install -r requirements.txt
```

## 4. Dataset Setup

The raw transaction dataset is not included in the repository due to its size.

Place the dataset in the `data/` directory before running the notebooks.

```text
data/
└── <your-dataset-file>.xlsx
```

## 5. Run the Project

Start Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebooks in this order:

```text
01_customer_revenue_analysis.ipynb
        ↓
02_customer_purchase_prediction.ipynb
```

The notebooks contain the complete data analysis, customer segmentation, machine learning, revenue prediction, and customer targeting workflow.
