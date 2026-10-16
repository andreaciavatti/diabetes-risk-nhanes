# Data

The raw files are not committed. They come from the public CDC National Health and Nutrition Examination Survey (NHANES), 2013–2014 cycle, as published on Kaggle:
https://www.kaggle.com/datasets/cdc/national-health-and-nutrition-examination-survey

Original source and documentation: https://www.cdc.gov/nchs/nhanes/

The notebook expects these files in this folder:

- `demographic.csv`
- `examination.csv`
- `labs.csv`
- `diet.csv`
- `questionnaire.csv`

The download also contains `medications.csv`, which the analysis does not use. All files share the participant identifier `SEQN`.
