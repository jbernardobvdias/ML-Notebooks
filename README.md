# ML-Notebooks

A collection of Jupyter notebooks for machine learning experiments.

## Structure

```
ML-Notebooks/
├── notebooks/      # Experiment notebooks
├── data/           # Downloaded/local datasets (not tracked in git)
├── .gitignore
├── requirements.txt
└── README.md
```

## Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/jbernardobvdias/ML-Notebooks.git
   cd ML-Notebooks
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Data

Datasets used by the notebooks are stored in the `data/` folder. They are not committed to the repository, download or generate them as needed before running a notebook (see the relevant notebook for source/instructions).
