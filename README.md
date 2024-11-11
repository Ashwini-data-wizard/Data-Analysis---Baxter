# Data-Analysis-Baxter
It is designed to support lean Six Sigma analysis, focusing on quality improvement, process optimization, and defect reduction across various stages of the manufacturing process.​

## Business Problem:
During my research project at Baxter, I conducted a Quality Assurance project aimed at enhancing manufacturing quality by identifying and reducing defects. The project was designed to support Lean Six Sigma initiatives by developing a comprehensive dataset from scratch, incorporating diverse data sources, and facilitating in-depth analysis to optimize processes and minimize defects.

## Task:
The primary objective was to build a dataset that could support detailed correlation analysis, predictive modeling, and forecasting for quality improvement. This dataset needed to integrate information from multiple departments—production lines, quality control, and supply chain—enabling us to analyze defect types, severity, and associated repair costs and identify improvement opportunities.

## Action:
I constructed and managed a workflow with six key stages:

-  Data Extraction: Collected data from various sources, including production outputs, machine utilization rates, defect reports, and supplier quality metrics.
-  Data Cleaning and Preprocessing: Applied preprocessing steps, such as handling missing values with mean/median, mode, KNN, and regression imputation methods to ensure data quality.
- Data Transformation: Converted dates to appropriate formats and applied numeric mappings for categorical variables to prepare the data for machine learning.
- Correlation Analysis: Used the corr() function to analyze the relationship between severity and repair cost, among other key metrics, to understand which defects had the most significant financial impact.
- Visualization: Created visual representations of the data, such as heatmaps and scatter plots, to identify trends and patterns visually.
- Prediction Models and Forecasting: Built predictive models to forecast defect occurrences and associated repair costs, assisting in resource allocation and process adjustments for quality improvement.

## Key Insights
### Time-Series Analysis

- Bar Chart: Monthly Defect Occurrences (Jan to June 2024)
1. January shows the highest defect occurrences, with around 191 incidents.
2. June has the lowest count, with 151 defects, indicating a noticeable reduction compared to the earlier months.
3. Other months, such as March and April, have similar defect occurrences, around 170-175, which suggests some consistency in defect rates.
4. The trend shows a peak in January, followed by a gradual decrease through the next few months, suggesting potential improvements or seasonal factors affecting defect rates.

- Line Chart: Defect Occurrences Over Time
1. The line chart reinforces the observation from the bar chart, showing a sharp increase in defects in January (191), followed by a significant drop to June (151).
2. There's an upward trend from February to January and from June to March, suggesting that some months experience higher defect rates than others.
3. The spike in January may indicate an anomaly or a period where quality issues were more prevalent, while the subsequent decrease could reflect improved quality measures or process changes.

- Key Insights
Peak in January: The significant peak in January may indicate a need to investigate root causes, such as process, environmental, or material issues during that time.
Improvement in June: The drop to 151 in June suggests effective corrective actions or seasonal improvements in quality.
Stable Months: Months like February, April, and March show relatively stable defect counts, suggesting consistent quality issues that may require targeted improvements.
Overall, this data indicates both a seasonal trend and potential success in recent quality interventions.
