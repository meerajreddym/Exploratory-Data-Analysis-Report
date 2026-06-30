wine-eda-project/
├── data/
│   └── wine_dataset.csv              # Raw dataset (UCI Wine Recognition Dataset)
├── notebooks/
│   └── EDA_Wine_Dataset.ipynb        # Full executed analysis notebook (run this first)
├── src/
│   └── eda_analysis.py               # Standalone script — regenerates all charts/stats
├── images/
│   ├── 01_class_distribution.png
│   ├── 02_feature_histograms.png
│   ├── 03_boxplots_by_class.png
│   ├── 04_correlation_heatmap.png
│   ├── 05_pairplot_key_features.png
│   ├── 06_key_relationships.png
│   └── 07_violin_key_features.png
├── reports/
│   ├── EDA_Report.md                 # Structured written report of findings
│   ├── summary_statistics.csv        # Exported descriptive statistics
│   └── top_correlations.txt          # Exported ranked correlation pairs
├── requirements.txt
├── LICENSE
└── README.md
