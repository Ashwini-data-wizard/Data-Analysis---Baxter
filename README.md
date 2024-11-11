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

### Product based analysis

### 1. Top 10 Products with Most Defects
The first graph identifies Product IDs with the highest defect counts, with Product 63 having the most. Products 81 and 97 also show high defect counts, indicating that certain products consistently encounter quality issues.

#### Recommendations:

- Focused Quality Control: Increase inspection frequency and quality control measures for high-defect products, particularly Products 63, 81, and 97.
- Root Cause Analysis: Conduct a root cause analysis on these specific products to determine why they are prone to defects. Consider factors like raw materials, manufacturing processes, or design flaws.
- Supplier Evaluation: If these products have components sourced from specific suppliers, review supplier quality performance and implement corrective actions as needed.

### 2. Number of Defect Types
Structural, Functional, and Cosmetic defects are prevalent, with Structural defects slightly leading.

#### Recommendations:

- Prioritize Structural Issue Resolution: Since structural defects are the most common, focus on enhancing the materials and design standards to minimize such issues.
- Segmented Quality Improvements: For functional and cosmetic defects, create separate improvement plans. For instance, functional issues might need design alterations, while cosmetic issues may require a review of the finishing processes.

### 3. Number of Defect Locations
Defects occur most frequently on the Surface, followed by Component and Internal locations.

#### Recommendations:

Enhanced Surface Inspection: Since surface defects are the most common, invest in automated visual inspection technologies to catch these early in the production process.
Internal Component Checks: For component and internal issues, consider using more advanced scanning or testing methods to detect defects that are harder to spot visually.

### 4. Defect Severity
The majority of defects are Minor, followed by Critical and Moderate levels.

#### Recommendations:

- Focus on Critical Defects: While minor defects are more frequent, critical defects can have a significant impact on product performance and customer satisfaction. Allocate resources to minimize critical issues as a priority.
- Quality Standards for Minor Defects: Set thresholds for acceptable minor defects, focusing on cosmetic issues that do not affect functionality. This approach can improve inspection efficiency by allowing inspectors to focus on more serious issues.

