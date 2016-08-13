# BPDM 2016

## In The Lab (Data Hack)

### Problem
Predict whether or not a person has Health Insurance based on collected demographic information.

### Data
#### Variables
All data for this Data Hack comes from the National Center for Health Statistics, part of the Center for Disease Control (CDC). Specifically, [http://www.cdc.gov/nchs/nhanes/nhanes_questionnaires.htm](http://www.cdc.gov/nchs/nhanes/nhanes_questionnaires.htm).
 1. [Independent Variables](http://wwwn.cdc.gov/Nchs/Nhanes/2011-2012/DEMO_G.htm) - Demographic Information for ~10,000 people interviewed in 2011-12 and 2013-14.
 2. [Dependent Variable](http://wwwn.cdc.gov/Nchs/Nhanes/2011-2012/HIQ_G.htm) - If person has insurance (HIQ011 = 0.0) or does not (HIQ011 = 1.0).

#### Predictive Modeling
Two comma-delimited files are being provided:
  * train_2011_12_DATA.csv
  * test_2013_14_DATA.csv

For binary classification, use "train_2011_12_DATA.csv" for training and validating model(s), and "test_2013_14_DATA.csv" for estimating the performance of the model(s)
