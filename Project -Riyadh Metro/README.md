# Project - Riyadh Metro

Brief data analysis and reporting for Riyadh Metro integrated dataset.

Contents
- `riyadh_integrated_analysis_Cleaned.csv` — cleaned dataset used for analysis
- `Riyadh_integrated_analysis_using_python.ipynb` — main analysis notebook (Python)
- `upload to PostgreSQL.ipynb` — notebook to demonstrate loading data to PostgreSQL
- `First Report using PowerBI.pbix` — Power BI report (binary)
- `commercial_services_by_category_sub_2024 _before cleaning.xlsx` — supplementary Excel data
- `requirements.txt` — Python dependencies

How to use
1. Create and activate a virtual environment (recommended).
2. Install dependencies:

```
pip install -r "Project - Riyadh Metro/requirements.txt"
```

3. Open and run `Riyadh_integrated_analysis_using_python.ipynb` in Jupyter Notebook or JupyterLab.
4. Optionally open the Power BI file with Power BI Desktop to view the dashboard.

Notes
- Large binary files (Power BI report, Excel) are included in the folder; they are not required to run the notebook if you only use the CSV.
- If you plan to load data to PostgreSQL, update the connection parameters in `upload to PostgreSQL.ipynb`.

Author
- Repository owner: yasir239
