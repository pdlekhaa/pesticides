# pesticides
This project assesses the effect of using household pesticides on various health indicators for our STATS 571 (Causal Inference) final project. 

This project specifically uses the most recent data from the National Health and Nutrition Examination Survey (NHANES), the period of August 2021 to August 2023, to see if there is a causal relationship between frequent household insecticide use and the health outcomes hearing condition and blood pressure. The data needed recoding and cleaning (EDA.Rmd). Missing values were then imputed, matched on propensity scores with calipers, and finally tested for a causal effect (prop_scores_imputed.Rmd). This was compared to only matching complete cases (prop_scores_matching.Rmd). Final-Project-Report.pdf contains detailed methodology and results.

Data Source (NHANES): https://wwwn.cdc.gov/nchs/nhanes/default.aspx
