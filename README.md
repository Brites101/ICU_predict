# COVID-19 - Clinical Data to assess diagnosis

Competition: https://www.kaggle.com/S%C3%ADrio-Libanes/covid19

# Context

COVID-19 pandemic impacted the whole world, overwhelming healthcare systems - unprepared for such intense and lengthy request for ICU beds, professionals, personal protection equipment and healthcare resources.
Brazil recorded first COVID-19 case on February 26 and reached community transmission on March 20.

# all to action

There is urgency in obtaining accurate that to better predict and prepare healthcare systems and avoid collapse, defined by above capacity need of ICU beds (assuming human resources, PPE and professionals are available), using individual clinical data - in lieu of epidemiological and populational data.


# Task 01

Predict admission to the ICU of confirmed COVID-19 cases.
Based on the data available, is it feasible to predict which patients will need intensive care unit support?
The aim is to provide tertiary and quarternary hospitals with the most accurate answer, so ICU resources can be arranged or patient transfer can be scheduled.

# Task 02

Predict NOT admission to the ICU of confirmed COVID-19 cases.
Based on the subsample of widely available data, is it feasible to predict which patients will need intensive care unit support?
The aim is to provide local and temporary hospitals a good enough answer, so frontline physicians can safely discharge and remotely follow up with these patients.

# The Data

Label output
ICU should be considered, as the first version of this dataset, the target variable.

# Window Concept

We were carefull to include real life cenarios of with window of events and available data.
Data was obtain and grouped

# Dataset

This dataset contains anonymized data from Hospital Sírio-Libanês, São Paulo and Brasilia. All data were anonymized following the best international practices and recommendations.
Data has been cleaned and scaled by column according to Min Max Scaler to fit between -1 and 1.

# Available data

Patient demographic information (03)
Patient previous grouped diseases (09)
Blood results (36)
Vital signs (06)
In total there are 54 features, expanded when pertinent to the mean, median, max, min, diff and relative diff.

diff = max - min

relative diff = diff/median
Expected submission
Submit a notebook that implements the full lifecycle of data preparation, model creation and evaluation.
