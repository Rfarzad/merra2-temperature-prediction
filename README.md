# MERRA-2 Temperature Prediction

This project predicts the winter temperature of South Bend, Indiana using NASA’s MERRA-2 reanalysis data.  
It includes feature scaling, linear regression, model validation, and diagnostics.  
A simulation study compares model selection criteria (R², Adjusted R², AIC, BIC) to evaluate their performance.

## Structure
- `data/` – Training and prediction datasets as well as longitude and latitudes (Winter 2017–2018)
- `notebooks/` – Jupyter notebook for data analysis and simulation
- `reports/` – Final report (PDF) and exam instructions
- `requirements.txt` – Python dependencies
- Structure is shown below:

merra2-temperature-prediction/
│
├── data/                 # Input files
│   ├── data_prediction.pkl
│   └── data_training.pkl
│   ├── lat.pkl
│   └── lon.pkl
│
├── notebooks/           # Code file
│   └── Python_file.ipynb
│
├── reports/             # Written report and project instruction
│   ├── Final_Report.pdf
│   └── Project_Instruction.pdf
│
├── README.md            # Explanation of the project
└── requirements.txt     # List of required Python packages

## How to Run
1. Open the notebook in Jupyter or VS Code.
2. Install dependencies using `pip install -r requirements.txt`
3. Put the four input files in the same address the python file is located.
4. Run all cells to reproduce results and figures.

## Author
**Reza Farzad**  
University of Notre Dame – ACMS 60786 (Applied Linear Models, Fall 2024)
