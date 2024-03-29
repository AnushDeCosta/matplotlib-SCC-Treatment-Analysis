# Pymaceuticals Inc. Analysis

![Mice](https://github.com/AnushDeCosta/matplotlib-SCC-Treatment-Analysis/assets/67308030/bf29c70f-c056-4e4b-a91b-568aab290733)

## Summary
The Pymaceuticals Inc. Analysis project aims to analyze the effectiveness of different drug regimens in treating tumors in mice. The analysis involves dataset processing, data visualization, statistical analysis, and drawing conclusions based on the findings.

## Introduction
This repository contains the analysis of the Pymaceuticals Inc. dataset, which focuses on the effectiveness of different drug regimens in treating tumors in mice. The analysis includes various visualizations and statistical summaries to understand the relationship between the drug regimens, tumor volume, metastatic sites, and mouse characteristics.
The analysis revolves around three core aspects:
- Dataset Processing
- Data Visualization and Statistical Analysis
- Drawing Conclusions

## Dataset Processing
The initial part of the project involves handling the Pymaceuticals Inc. dataset, which concentrates on assessing the efficacy of various drug regimens in treating mouse tumors. Data from this dataset is prepared for statistical summaries and graphical visualizations to elucidate the relationship between the drug regimens, tumor volume, metastatic sites, and mouse characteristics.

## Data Visualization and Statistical Analysis
### Drug Regimen and Tumor Volume
The first phase of the analysis indicates that the final tumor volume in mice treated with Capomulin and Ramicane is generally smaller than in those treated with other regimens. Nonetheless, the median and mean final tumor volumes for Capomulin and Ramicane are quite similar.

![01 Drug Regimen and Tumor Volume](https://github.com/AnushDeCosta/matplotlib-SCC-Treatment-Analysis/assets/67308030/9519ae29-a181-4376-bb32-3835ee28d8d0)

### Time-dependent Tumor Volume Variation
The project also monitors the tumor volume variation over time for a selected mouse (ID l509) treated with Capomulin. The trend of the tumor volume changes over the timepoints studied, hinting at a possible spread of the cancerous cells.

![02 Time-dependent Tumor Volume Variation](https://github.com/AnushDeCosta/matplotlib-SCC-Treatment-Analysis/assets/67308030/1edd4f15-a2f7-4ec4-90e8-369ec718a668)

### Weight and Tumor Volume Correlation
The last phase of the analysis focuses on establishing a correlation between the mouse weight and average tumor volume, revealing a strong positive correlation. However, it's crucial to remember that correlation does not imply causation.

![03 Weight and Tumor Volume Correlation](https://github.com/AnushDeCosta/matplotlib-SCC-Treatment-Analysis/assets/67308030/01111c1a-6431-4123-980c-c542dcdeecc4)

## Conclusions
The project's conclusion centers around the effectiveness of different drug regimens in treating tumors in mice. Though the results are promising, they are not definitive, and further research is necessary. Other factors could also influence the observed relationships.

## Tools
- Jupyter Notebook
- Python
- Matplotlib
- Pandas
- Numpy
- Scipy

## Files
- [Dataset Processing and Visualization](./pymaceuticals_Final.ipynb)
- [Mouse Data](./data/Mouse_metadata.csv)
- [Study results](./data/Study_results.csv)




