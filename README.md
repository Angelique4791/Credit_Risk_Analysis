# Credit_Risk_Analysis
## Overview

This analysis is meant to determine the viability of machine learning models to accurately predict credit risk of credit applicants. Using historical data of credit risk from 2019, four prediction models were created. One random oversampling model and one SMOTE (Synthetic Minority Oversampling TEchnique) were used to increase the size of the high-risk category. One random undersampling model was created which reduced the number of low risk applicants. Finally, one combination model (a SMOTEEN algorithm combines SMOTE with Edited Nearest Neighbors (ENN)) was created representing comarably sized data sets. All of these models creaate equal or camparable data sets in an effort to improve the accuracy, precision and sensitivity of the predictions. Each model was evaluated on these three criteria to correctly classify high risk applicants.

## Results

### Random oversampling
<ul>
  <li>Balanced accuracy score of .637 shows that only about 64 out of 100 applications are correctly predicted as high-risk or low-risk</li>
  <li>Prcision of low-risk is 1.00 combined with precision of hig-risk is 0.01 is a questionable indicator of accuracy of time</li>
  <li>Sensitivity of low-risk is .62 with sensitivity of high-risk of .65 indicates that the model is susceptible to missing high-risk applicants</li>
  <li>F1 score comfirms the presicision and sensitivity of both low-risk (.79) and high-risk (.02) are questionable</li>
</ul>
