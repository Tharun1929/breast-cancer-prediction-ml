# Breast Cancer Prediction (ML)

Predictive modeling for early breast cancer detection using **Logistic Regression** on cell-measurement features. This repo contains a Jupyter notebook that covers data loading, preprocessing, training, and evaluation.

## Project structure

- `notebook/`
  - `breast_cancer_model.ipynb` — end-to-end workflow (EDA → preprocessing → model → metrics)
- `data/`
  - `Breast_cancer_data.csv` — dataset used by the notebook

## Dataset

The CSV includes a `diagnosis` target column:
- `M` = Malignant
- `B` = Benign

> If you publish or reuse the dataset, make sure you have the right to share it and follow the dataset’s license/source requirements.

## How to run

### Option A: Run locally (recommended)

1. Clone the repo:

```bash
git clone https://github.com/Tharun1929/breast-cancer-prediction-ml.git
cd breast-cancer-prediction-ml
```

2. Create and activate a virtual environment:

```bash
python -m venv .venv
```

- Windows (PowerShell):

```powershell
.\.venv\Scripts\Activate.ps1
```

- macOS/Linux:

```bash
source .venv/bin/activate
```

3. Install dependencies:

```bash
python -m pip install --upgrade pip
pip install pandas numpy seaborn matplotlib scikit-learn jupyter
```

4. Start Jupyter and open the notebook:

```bash
jupyter notebook
```

Then open `notebook/breast_cancer_model.ipynb` and run the cells.

### Option B: Run in Google Colab

- Upload `notebook/breast_cancer_model.ipynb` to Colab
- Upload `data/Breast_cancer_data.csv` to the Colab session
- Update the file path in the notebook if needed

## Model & evaluation

The notebook trains a Logistic Regression classifier and evaluates it using standard classification metrics (e.g., accuracy, precision, recall, F1-score, ROC-AUC).

## License

Add a license if you plan to reuse/distribute this project widely (MIT is common for ML demos).
