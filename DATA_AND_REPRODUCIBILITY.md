# Dataset and reproducibility notes

The notebook studies **two distinct UCI datasets**: an obesity dataset and gene-expression data. To run it, provide the files referenced by the notebook's `obesity_path`, `gene_data_path` and `gene_labels_path` settings.

- Obesity: `ObesityDataSet_raw_and_data_sinthetic.csv` (UCI Estimation of Obesity Levels Based on Eating Habits and Physical Condition).
- Cancer RNA-Seq: unpack the UCI gene-expression archive so its data and label CSVs are accessible, then set `gene_data_path` and `gene_labels_path` in the notebook.

Neither full dataset is committed to this repo; the study requires downloading/unpacking them under the source terms. Inspect feature order and file names in the notebook. Recorded PCA/clustering outputs come from the saved original run, **not** the repository's static-check CI.

## Running the original notebook

```bash
python -m pip install -r requirements.txt
jupyter notebook SIT720_4_1P_Zenith_Anthony_s225534396_Final_Code_Executed.ipynb
```

These are version *ranges*, not an exact captured original environment. A fresh run has not been validated by this documentation update.
