# Clustering and Principal Component Analysis

Explore how preprocessing, clustering algorithms and dimensionality reduction affect the structure found in data.

**Python · scikit-learn · K-Means · DBSCAN · PCA**

## Project at a glance

The executed notebook contains clustering comparisons and PCA outputs. Review those figures alongside the report; visual separation alone is not evidence of useful clusters.

## Technical work

- Mixed-feature encoding and scaling
- K-Means and K-Means++ comparison
- Silhouette analysis and repeated clustering runs
- DBSCAN parameter exploration and gene-expression PCA

## Explore the evidence

- [SIT720_4_1P_Zenith_Anthony_s225534396_Final_Code_Executed.ipynb](SIT720_4_1P_Zenith_Anthony_s225534396_Final_Code_Executed.ipynb)
- [SIT720_4_1P_Zenith_Anthony_s225534396_Final_Report.pdf](SIT720_4_1P_Zenith_Anthony_s225534396_Final_Report.pdf)

## Run locally

```bash
python -m venv .venv
# Activate the environment, then:
python -m pip install jupyter numpy pandas matplotlib scikit-learn
jupyter notebook
```

Follow obesity_path, gene_data_path and gene_labels_path in the notebook. Gene-expression files can be large.

Open the linked notebook and run the cells in order. Package names reflect the source imports; a fresh environment was not tested during this documentation update. Dataset downloads require internet access.

## Limitations and status

Two distinct public datasets: obesity and gene-expression data. Internal clustering measures and comparisons with supplied labels answer different questions.

The repository preserves saved notebook outputs. Results are from those outputs, not a new execution.

**Author:** Zenith Anthony Dabarera · SIT720 Machine Learning  
[AI/ML portfolio](https://github.com/Zenith1997)
