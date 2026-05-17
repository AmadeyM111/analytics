# Analytics

A collection of educational and practical Jupyter notebooks focused on `pandas`, `scikit-learn`, and core analytics/ML tasks.

## Repository Contents

- `Drills.ipynb` - basic classification exercises (`LogisticRegression`).
- `Drills_train_tree.ipynb` - training a `DecisionTreeClassifier`.
- `Drills_train_rndm_forest.ipynb` - training a `RandomForestClassifier`.
- `operators.ipynb` - quick reference for core `pandas` operations.
- `train_task.ipynb` - practice analytics tasks on order data.
- `challenge_task.ipynb`, `challenge_task_v0.1.ipynb` - challenge tasks for order analytics.
- `ml_py_interview_questions.ipynb` - ML/Python interview-oriented practice and questions.

## Tech Stack

- Python 3.10+
- Jupyter Notebook / JupyterLab
- pandas
- scikit-learn

## Quick Start

```bash
python -m venv .venv
source .venv/bin/activate   # macOS/Linux
pip install --upgrade pip
pip install jupyter pandas scikit-learn
jupyter notebook
```

## How to Use

1. Open any notebook from the list above.
2. Run cells from top to bottom.
3. For data-related tasks, ensure required input files are available (for example, JSON order files used in notebooks).

## Notes

- This repository is intended for hands-on learning and notebook-based experimentation.
- There is currently no separate production package/module structure.

## Suggested Improvements

- Add `requirements.txt`.
- Pin library versions.
- Add a `data/` directory with sample input datasets.
- Move reusable logic into `.py` modules.
