Author: yaochieh_yao

4/14/2024

Cirrhosis Status Prediction (Multi-Class) 
This competition dataset is a model-synthesized version of Cirrhosis Patient Survival Prediction (Dickson et al., 2023), and the original version (Fleming et al., 2013), also posted in Kaggle initially from the Mayo Clinic, collects 418 patients with primary biliary cirrhosis (PBC) of the liver carried out from 1974 to 1984. The competition dataset has 19 columns (6 categorical, 13 numerical) and 5,270 rows, compared to 418 in the original. The goal is to predict the patient’s cirrhosis status. 
Competition link: https://www.kaggle.com/competitions/playground-series-s3e26 
Original link: https://www.kaggle.com/datasets/joebeachcapital/cirrhosis-patient-survival-prediction/data 

Feature Description 
Numerical features: 

| Feature       | Description |
|---------------|-------------|
| N_Days        | Day counts from registration to the day of record (dead, transplanted, or alive). |
| Age           | Patient's age in days. |
| Bilirubin     | Bilirubin level; high levels for a long period can indicate severe liver disease. |
| Cholesterol   | Cholesterol level; high levels can progress steatosis into more severe stages. |
| Albumin       | Albumin protein level in blood; low levels can indicate liver disease. |
| Copper        | Copper level in serum/liver; deficiency relates to liver diseases. |
| Alk_Phos      | High Alkaline phosphatase (ALP) enzyme level can indicate liver disorders. |
| SGOT          | High Glutamic-oxaloacetic transaminase (SGOT) level could indicate liver damage. |
| Tryglicerides | Level of esters produced by the liver; high levels can indicate steatosis. |
| Platelets     | Platelet count; often low in cirrhosis patients. |
| Prothrombin   | Prothrombin time (PT); prolonged time indicates severe liver damage. |
Categorical features:

| Feature      | Description |
|--------------|-------------|
| Sex          | Patient's biological gender: Female or Male. |
| Drug         | Medication type: D-penicillamine or Placebo. |
| Ascites      | Presence of excess abdominal fluid. |
| Hepatomegaly | Presence of an enlarged liver. |
| Spiders      | Presence of spider angiomas. |
| Edema        | N (no edema), S (edema without diuretics), or Y (edema despite diuretic therapy). |
| Status       | Patient's status on record day: C (alive), D (dead), CL (liver transplant & alive). |
| Stage        | Disease stage: 1 (Steatosis), 2 (Fibrosis), 3 (Cirrhosis), 4 (Liver Failure). |


Reference 
Dickson,E., Grambsch,P., Fleming,T., Fisher,L., and Langworthy,A.. (2023). Cirrhosis Patient Survival Prediction. UCI Machine Learning Repository. https://doi.org/10.24432/C5R02G. 
Fleming, Thomas R., and David P. Harrington. Counting processes and survival analysis. Vol. 625. John Wiley & Sons, 2013.
