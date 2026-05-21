# Cystic Fibrosis Forecasting App

## Description
This application forecasts the Canadian cystic fibrosis (CF) population through 2033 using data from the Canadian Cystic Fibrosis Registry (CCFR).

The application projects the overall CF population, survival outcomes, hospitalizations, home IVs, pregnancies, and many comorbidities.
Results are stratified by age group, disease severity, and CFTR modulator status. Forecasts are based on transition probabilities between disease severity states calculated using 2022 and 2023 CCFR data, while accounting for differences by age group and cystic fibrosis transmembrane conductance regulator (CFTR) modulator use.

Users can choose to use either evidence based transition probabilities, or custom transition probabilities. Evidence based transition probabilities were created using CCFR data from 2022 and 2023. Custom probabilities allow users to scale the evidence-based transition probabilities by applying multipliers, creating a customized simulation that reflects their experience, target population, and goals.

The Cystic Fibrosis Forecasting App can be accessed <a href="https://resplab.shinyapps.io/forecasting-cf/"> here</a>. Please email hlungs@dal.ca for authorization to use the application. 

## User Guide
The Cystic Fibrosis Forecasting App allows users to project patients counts by:
<ul>
  <li>Age group</li>
  <li>Disease severity</li>
  <li>CFTR modulator use</li>
  <li>Comorbidity</li>
    <ul>
      <li>Pancreatic insufficiency</li>
      <li>Cystic fibrosis related diabetes (CFRD)</li>
      <li>Respiratory related comorbidities</li>
      <li>Digestive related comorbidities</li>
      <li>Liver related comorbidities</li>
      <li>Mental health related comorbidities</li>
      <li>Bone related comorbidities</li>
      <li>Malignancies</li>
</ul>
<br>
<img width="975" height="390" alt="image" src="https://github.com/user-attachments/assets/272c16ef-6fc5-4c0d-b740-7f8d3714fd08" />
<br>
<br>
Users can view projected counts through 2033 and adjust population settings and simulation details to fit their needs. Inputs for the simulation details include the time period (minimum: 2023, maximum: 2033), number of simulations (maximum: 50), transition probability scenario (evidence based or custom), and result display intervals.
<br>
<br>
<img width="1076" height="542" alt="image" src="https://github.com/user-attachments/assets/f4c63290-521f-409e-bcef-232a8ac58f71" />
<br>

## Change Log

Changes in version 2:

- Output graphs in a 1 column grid and they are not fillable.
