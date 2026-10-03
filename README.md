# Medical Patient Data Analysis Using R

## Project Overview
This academic project demonstrates basic medical patient data analysis using R. The dataset contains patient age, gender, blood pressure, cholesterol, glucose level, and health status.

## Objectives
- Import and inspect data
- Check and clean the dataset
- Calculate descriptive statistics
- Create graphical visualizations
- Interpret the sample data

## Project Structure

```text
medical-patient-data-analysis-r/
├── data/
│   └── medical_data.csv
├── docs/
│   └── project_documentation.md
├── output/
│   └── Generated plots after running the R script
├── medical_patient_analysis.R
├── README.md
└── requirements.txt
```

## Requirements
- R 4.x or later
- No external R packages are required; the project uses base R functions.

## How to Run

1. Install R.
2. Clone/download this repository.
3. Open a terminal in the project folder.
4. Run:

```bash
Rscript medical_patient_analysis.R
```

The script reads `data/medical_data.csv` and generates PNG charts inside the `output/` folder.

## Dataset
The sample dataset contains 15 patient records and 7 variables:
- Patient_ID
- Gender
- Age
- Blood_Pressure
- Cholesterol
- Glucose
- Health_Status

## Important Note
This dataset and analysis are for academic demonstration only. The results should not be considered medical diagnosis or clinical advice.
