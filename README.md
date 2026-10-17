# CT4101-machine-learning
CT4101 Machine Learning Portfolio Project - predicting cervical cancer diagnosis from patient risk factors

## Overview:
This project investigates whether patient demographics, behaviours and medical history can be used to predict a positive cervical cancer biopsy result. The project uses the cervical cancer dataset from the UCI Machine Learning Repository. 

Source: https://archive.ics.uci.edu/dataset/383/cervical+cancer

## Setup instructions:
1. Clone the repository: 
git clone https://github.com/lf1313/CT4101-machine-learning.git
cd CT4101-machine-learning

2. Create a Python virtual environment:
python -m venv .venv

3. Activate the environement:
.\.venv\Scripts\Activate.ps1

4. Install the required libraries:
python -m pip install -r requirements.txt

## Running the project:
1. Make sure risk_factors_cervical_cancer.csv is located in the data folder
2. Open notebooks/milestone2.ipynb in VS Code with the Python and Jupyter extensions installed
3. Select the Python interpreter from the .venv environment as the notebook kernel.
4. Run all cells in order to reproduce the data audit, preprocessing and baseline evaluation.
