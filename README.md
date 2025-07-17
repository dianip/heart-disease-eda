# Heart Disease EDA

This project performs exploratory data analysis (EDA) on a heart disease dataset to explore patterns in age, cholesterol, chest pain types, blood pressure, and outlier behaviour related to the presence of heart disease.

---

## Project Structure

- `Heart_Disease_EDA.ipynb`: Main notebook containing all analysis steps.
- `data/Heart_Disease_Data.csv`: Dataset used for exploration.
- `images/`: Folder containing saved plots used in the notebook and README.

---

## Tools & Libraries

- Python (Jupyter Notebook)
- pandas, numpy
- matplotlib, seaborn

---

## What’s Inside

The notebook includes:

- **Age Group Analysis**: Groups patients by age brackets and compares heart disease presence vs absence using a line plot.
- **Chest Pain Type vs Heart Disease**: Uses a bar chart to show which pain types are most associated with diagnosed heart disease.
- **Cholesterol vs Age**: Plots cholesterol levels against age to detect trends and potential outliers.
- **Outlier Detection**: Uses boxplots to highlight outliers in numerical features like BP and cholesterol.
- **Blood Pressure by Gender**: A KDE plot visualises differences in blood pressure distributions between male and female patients.

---

## Insights

- Patients aged 55–64 had the highest heart disease presence; those aged 45–54 had the highest absence.
- Chest pain type 4 had the strongest link to heart disease (91 cases).
- Cholesterol tends to increase with age, with a few notable outliers around 65–70 years old.
- BP and cholesterol had the highest number of outliers among all features.
- Blood pressure density was higher for sex 1 between 120–130 mmHg, while sex 2 distributions were more gradual.
