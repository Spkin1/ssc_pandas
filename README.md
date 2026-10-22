# Data Manipulation with Pandas Demonstration

## 📌 Overview
This repository contains a structured demonstration of essential data manipulation workflows using Python's `pandas` library. It covers core analytical operations including explicit structure configuration, data inspection, complex multi-conditional filtering, and file exporting pipelines. 

The analysis is performed on the **Wine Reviews Dataset**, showcasing clean code principles and practical evaluation patterns typical workflows.

## 🛠️ Core Features Demonstrated
* **Pandas Structures:** Manual construction of time-indexed `Series` and custom-indexed `DataFrames` directly from memory.
* **Data Ingestion & Slicing:** Handling implicit tracking indexes during file loads alongside positional (`iloc`) and label-based (`loc`) data slicing.
* **Conditional Filtering:** Executing complex logical evaluation masks combining bitwise operators (`&`, `|`), set inclusion (`isin`), and null handling (`notnull`).
* **Feature Engineering & Pipelines:** Dynamic feature generation, sequence index track mapping, and targeted baseline schema exporting.

## 📊 Dataset Requirements
The notebook processes the **Wine Mag Reviews Dataset** containing approximately 130,000 unique records. 
* To run the evaluation pipeline, ensure you place the dataset file (`winemag-data-130k-v2.csv`) inside a local repository directory named `Data_002/`.
* The notebook safely handles missing local data errors using structured exception blocks.

## 🚀 How to Run the Notebook

### 1. Prerequisites
Ensure you have Python 3.x installed along with `pandas` and `numpy`. You can install the dependencies via pip:
```bash
pip install pandas numpy notebook
```
Open `sscpandas.ipynb` and execute the cells sequentially.

## 📂 Outputs Generated
Running this notebook automatically processes a validation slice of the initial matrix and generates a localized snapshot file titled `wine_analysis_snapshot.csv` in your root working directory.
