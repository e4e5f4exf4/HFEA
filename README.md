Analyzing the Relationship Between Age of Male and IVF Cycle Outcomes


Description
This project focuses on analyzing the relationship between the age of males (Sperm Donors for 1991-2016, Male Partners for 2017-2018) and IVF treatment outcomes using data from the publicly available Human Fertilisation and Embryology Authority (HFEA) in the UK. The data spans over 27 years and provides a comprehensive view of reproduction treatments in UK. The project will involve data cleaning, constructing two panel datasets, Power BI dashboard building and performing statistical analyses on the chosen independent variables (age and cycle-specific variables) and the dependent variables (Live birth and Early Outcome). The project serves as a first step in exploring the HFEA data which the data researchers employed at Originelle Fertility Center will use to publish an academic paper. This project assists them in understanding the nuance of the data and exploring possible research orientations.

Tech Assets and URLs
•	GitHub Repository: https://github.com/e4e5f4exf4/HFEA/

•	Power BI Dashboard: the pbix files named HFEA 2016.pbix for 1991-2016 and HFEA 2018.pbix for 2017-2018. Measures created using DAX are put in the separate table called myMeasures. 

To Clone the repository:
bash
Copy code
git clone https://github.com/e4e5f4exf4/HFEA/
cd repo

Install the following required libraries:
bash
Copy code
pip install -r requirements.txt
Prerequisites
•	Python 3.7+
•	pandas
•	numpy
•	matplotlib
•	seaborn
•	scikit-learn
•	statsmodels
•	stargazer
•	catboost
•	xgb
•	lgbm
•	patsy


Key Components of the Project includes
•	Data Merging (Final Merge.ipynb)
•	Data cleaning and preprocessing (1991-2016.ipynb, 2017-2018.ipynb, cleaned data can be found in the data folder: 1991_2016 Donor Patient.csv, 2017_2018 cleaned data.7z)
•	Statistical analysis (1991_2016 Model.ipynb, 2017-2018 Model.ipynb)
•	Power BI dashboard for data visualization (HFEA 2016.pbix, HFEA 2018.pbix, in both files the dashboard whose name starts with "page" are the experimentation with certain graphs types. The official dashboards are given a proper name. I leave the experiments there to show the though process and hours of work. Maybe client can find something interesting there too)

Data Sources

Details about the data sources used in the project.
•	Human Fertilisation and Embryology Authority (HFEA) database (https://www.hfea.gov.uk/about-us/publications/research-and-data/)

Troubleshooting
Possible issues and how to troubleshoot them.

•	Data Loading Issues: Ensure the path to the data file is correct.
•	Library Installation Issues: Make sure all prerequisites are installed using pip install -r requirements.txt.

Passwords and credentials
•	No passwords or credentials required for the initial setup.

