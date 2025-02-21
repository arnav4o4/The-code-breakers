# Health Detective Dashboard
## Project Overview
### Theme: "The Health Detective": Unmasking the Hidden Influences
Scenario: A mysterious health epidemic is sweeping the nation, and your team of data detectives must uncover the root causes. Using the County Health Rankings dataset, the team will analyze and visualize relationships between health metrics to identify hidden influences on public health.

Challenge: Develop an interactive Health Detective Dashboard in Power BI that enables users to explore correlations, investigate specific counties, and propose hypotheses about health disparities.

Team Members
Shubham Kansal

Arnav Gupta

Kaushik Bhattacharya

Parth Shukla

Key Features of the Dashboard
1. Correlation Analysis
Use scatter plots and heatmaps to visualize relationships between different "Measure Names" (e.g., obesity rates vs. diabetes rates, smoking rates vs. life expectancy).

Identify strong positive or negative correlations that may indicate hidden influences on public health.

2. Clue Tracker
Allow users to investigate specific counties or regions.

Compare county-level health metrics (e.g., obesity, smoking, physical inactivity) to national averages.

Highlight counties with significant deviations from the norm.

3. Suspect Board (Bonus Feature)
Enable users to propose and test hypotheses about the causes of health disparities.

For example, users can explore whether low-income areas have higher rates of chronic diseases or if access to healthcare correlates with better outcomes.

4. Data Preprocessing & Analysis
Perform correlation analysis to identify relationships between variables.

Use regression analysis to explore causal relationships.

Detect outliers and anomalies in the data that may indicate unusual health trends.

Apply data filtering to focus on specific regions, states, or health metrics.

Data Sources
County Health Rankings Dataset: Includes a wide range of health metrics such as obesity rates, smoking rates, physical inactivity, diabetes prevalence, and more.

National Averages: Used as a benchmark for comparison.

Tools & Technologies
Power BI: For dashboard development, visualization, and interactivity.

Python/R (Optional): For advanced data preprocessing, correlation analysis, and regression modeling.

Excel: For initial data exploration and cleaning.

Dashboard Components
1. Home Page
Overview of the health epidemic scenario.

Summary of key findings from the dataset.

2. Correlation Analysis Page
Scatter plots and heatmaps showing relationships between health metrics.

Filters to explore specific metrics or regions.

3. Clue Tracker Page
Interactive map or table to select counties/regions.

Comparison of county-level metrics to national averages.

Highlight outliers and anomalies.

4. Suspect Board Page (Bonus)
User-driven hypothesis testing.

Visualizations to support or refute proposed hypotheses.

Steps to Build the Dashboard
1. Data Preprocessing
Clean the dataset (handle missing values, remove duplicates, etc.).

Normalize data for comparison (e.g., convert rates to percentages).

Identify key metrics for analysis (e.g., obesity, smoking, diabetes).

2. Correlation Analysis
Calculate correlation coefficients between health metrics.

Visualize correlations using scatter plots and heatmaps.

3. Regression Analysis
Explore causal relationships (e.g., does smoking rate predict diabetes rate?).

Use regression models to quantify relationships.

4. Outlier Detection
Identify counties with unusually high or low health metrics.

Highlight these counties in the Clue Tracker.

5. Dashboard Development
Design an intuitive and interactive layout in Power BI.

Add filters, slicers, and tooltips for user interactivity.

Incorporate visualizations (e.g., maps, bar charts, line graphs).

6. Testing & Validation
Test the dashboard with sample data and user scenarios.

Validate correlations and regression results for accuracy.

Bonus Features
Predictive Analytics: Use machine learning models to predict future health trends based on current data.

Geospatial Analysis: Overlay health metrics on a map to identify regional patterns.

User Feedback: Allow users to provide feedback on hypotheses and suggest new areas of investigation.

Deliverables
Power BI Dashboard: Interactive and user-friendly.

Documentation: Explanation of data preprocessing, analysis, and insights.

Presentation: A summary of findings and a demo of the dashboard.

Timeline
Week 1: Data preprocessing and initial analysis.

Week 2: Correlation and regression analysis.

Week 3: Dashboard development and testing.

Week 4: Final refinements and presentation preparation.
