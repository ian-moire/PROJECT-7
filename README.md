# Analyzing Childhood Anemia Trends in Kenya
## NON-TECHNICAL 
1. **TABLEAU:[Link](https://public.tableau.com/app/profile/ian.moire/viz/KENYACHILDHEALTHANEMIAINSIGHTS/KENYACHILDHEALTHANEMIAINSIGHTS)**
2. **PRESENTATION:[Link](https://docs.google.com/presentation/d/13A2BUqxmFqjX_2VwJZNKwf7GUzNIGoylNEJQbn8A35o/edit?usp=sharing)**

   ## Background
Anemia remains a major public health challenge, particularly among children under the age of five. It affects physical development, cognitive abilities, and overall well-being. The dataset provides key indicators on anemia prevalence in Kenya, capturing trends from national surveys conducted in 2015 and 2020. Understanding these patterns can help guide health interventions, policy decisions, and resource allocation to handle childhood anemia effectively.

## Objectives
1. Measure the prevalence of anemia among children under five.
2. Compare trends between 2015 and 2020, identifying any changes in severity.
3. Evaluate the impact of weighted and unweighted denominators.
4. Generate meaningful features like percentage-based prevalence rates for deeper analysis.
5. Provide actionable insights that can support public health strategies.

## Research Questions
1. What is the prevalence of anemia among children under five in Kenya?
2. How have anemia rates changed between 2015 and 2020?
3. Do weighted and unweighted denominators significantly impact reported anemia rates?
4. What is the distribution of anemia severity (mild, moderate, severe) among affected children?

## Data Description
The dataset used in this analysis is the "anemia_national_ken" dataset from `Data.Humdata.org`. It contains 19 records with features such as'ISO3','DataId','Indicator','Value','Precision','DHS_CountryCode','CountryName','SurveyYear','SurveyId','IndicatorId','IndicatorOrder', 'IsTotal', 'IsPreferred','SurveyType', 'DenominatorWeighted',and 'DenominatorUnweighted'. Missing values, duplicates, and outliers were addressed as Feature engineering metrics like ratios, and percentages features were added in the dataset.

## Methodology
The analysis involves the following:

1. **Data Cleaning:** Handling missing values using mode and median imputation. Standardizing categorical variables for consistency.

2. **Exploratory Data Analysis (EDA):** Visualizing data through box plots, scatter plots, histograms, and heatmaps. Analyzing correlations between variables using statistical techniques. Time-based trend analysis to examine anemia prevalence over survey years.

3. **Feature Engineering:** Creating percentage-based features for anemia prevalence. Calculating ratios for severity comparisons (moderate-to-severe anemia).

## Significance
Supports decision-makers in identifying priority areas for intervention. Helps researchers examine how anemia prevalence shifts over time. Evaluates differences between weighted and unweighted data to ensure accuracy in national estimates. Facilitates targeted public health efforts in Kenya to reduce childhood anemia prevalence.

## Conclusion

## Summary of Key Findings
1. Anemia prevalence rates show variation between 2015 and 2020, with a notable increase in moderate cases.
2. Weighted denominators adjust values slightly, affecting some calculated prevalence rates.
3. Moderate anemia is more prevalent than severe anemia, as observed in the computed severity ratio.
4. No extreme outliers detected, indicating data consistency across survey years.

## Implications
Develop Public Health Strategies to provide evidence for intervention efforts focused on moderate anemia reduction.
The results of Resource Allocation can guide targeted strategies for anemia prevention and treatment in children under five.
Long-Term Monitoring supports early detection of anemia progression.

## Limitations
Only includes survey data from Kenya, limiting broader generalization. Missing values were imputed, but assumptions may affect precision.
Dataset lacks detailed geographic segmentation for deeper regional comparisons.

## Future Work
Expand geographic scope to analyze anemia trends across multiple countries. Investigate socioeconomic factors influencing anemia prevalence. Enhance predictive modeling to forecast future anemia trends using time series analysis. Refine feature engineering to explore additional anemia-related indicators.
References
# ***data.Humdata.org***

**(https://data.humdata.org/dataset/dhs-data-for-kenya?force_layout=desktop)**
