# Python Data Science & Machine Learning Tutorials

A collection of hands-on Jupyter notebooks documenting my practice with the core Python data-science and machine-learning ecosystem. Each tutorial focuses on practical workflows, reproducible examples, and the reasoning behind common tools.

## Tutorials

| Topic | Notebook | What it covers |
| --- | --- | --- |
| Pandas | [Pandas Functions Mastery Guide](pandas_tutorial/pandas_functions_mastery_guide.ipynb) | Data selection, reshaping, joins, grouping, multi-indexes, and practical tabular-data workflows. |
| Matplotlib | [Matplotlib Tutorial](matplotlib/plt_tutorial.ipynb) | Essential chart types, styling, subplots, export, 3D plots, and animation. |
| SciPy | [SciPy for Quantitative Finance](scipy_tutorial/scipy_quantitative_finance_mastery_guide.ipynb) | Statistics, optimisation, linear algebra, signal processing, and finance-inspired examples. |
| Scikit-learn | [Financial Machine Learning](sklearn_tutorial/sklearn_financial_machine_learning_mastery_guide.ipynb) | Model workflows, pipelines, cross-validation, hyperparameter tuning, and time-series-aware validation. |
| PyTorch | [Deep Neural Networks](pytorch_tutorial/pytorch_deep_neural_networks_mastery_guide.ipynb) | Configurable neural networks, training loops, regularisation, early stopping, and hyperparameter tuning. |

## Getting started

Create and activate a virtual environment, then install the libraries used by the notebooks:

```bash
python -m venv .venv
source .venv/bin/activate
pip install jupyter pandas matplotlib scipy scikit-learn torch optuna
jupyter notebook
```

Open any notebook from the Jupyter interface and run its cells in order. The notebooks use generated or small local practice data, so no credentials are required.

## Repository scope

This public repository intentionally contains only the tutorial material listed above. Generated files, local environments, caches, datasets, and other experiments are excluded.

## Notes

These notebooks are learning materials and examples, not financial advice or production trading systems.
