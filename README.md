# Task 5 – Titanic Exploratory Data Analysis (EDA)

## Objective
Extract insights using statistical and visual exploration, as required by the Elevate Labs Task 5 brief.

## Dataset
`titanic.csv` – classic Titanic passenger dataset (891 rows, 12 columns). Source: [Data Science Dojo Titanic CSV](https://github.com/datasciencedojo/datasets/blob/master/titanic.csv).

## Deliverables
- `Task_5_Titanic_EDA.ipynb` – runnable Jupyter Notebook.
- `titanic.csv` – dataset used by the notebook.
- `Task_5_EDA_Findings_Report.pdf` – findings report with visualizations and observations.
- `Interview_Questions_Answers.md` – answers to all seven task interview questions.
- `01_...png` to `08_...png` – exported EDA charts.

## Run
1. Install Python 3.9+.
2. Run `pip install pandas numpy matplotlib seaborn jupyter`.
3. Keep the notebook and CSV in the same folder.
4. Run `jupyter notebook`, open the notebook, then select **Kernel → Restart & Run All**.

If the CSV is missing, the notebook attempts to download it from the public source URL (internet required).

## Findings
- Overall survival rate: 38.4%.
- Female survival rate: 74.2%; male survival rate: 18.9%.
- Class survival rates: first 63.0%, second 47.3%, third 24.2%.
- Cabin and Age contain missing values; Fare is right-skewed.

## Limitations
This is descriptive analysis. Associations are not proof of causation. Handle missing values and outliers according to the downstream objective.
