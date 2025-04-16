# Insurance Claims Data Analysis

Analysis on insurance claim amounts and related factors.

This repository contains source code and documentation for analyzing insurance claim data.

## Data Columns (in insurance_data.csv)

* `age` - Age of the insured individual
* `sex` - Gender of the insured (male/female)
* `bmi` - Body Mass Index
* `children` - Number of children/dependents
* `smoker` - Smoking status (yes/no)
* `Claim_Amount` - Insurance claim amount
* `past_consultations` - Number of past medical consultations
* `num_of_steps` - Number of steps (possibly physical activity)
* `Hospital_expenditure` - Hospital expenditure amount
* `NUmber_of_past_hospitalizations` - Number of past hospitalizations
* `Anual_Salary` - Annual salary of the insured
* `region` - Geographic region of residence
* `charges` - Additional charges related to insurance

## Label Encoding Mapping
* `label_encoding_mapping.csv` - Provides a mapping of encoded categorical values to their original strings (e.g., male/female to 0/1 for the 'sex' column).
*  This is used for interpreting encoded data.
