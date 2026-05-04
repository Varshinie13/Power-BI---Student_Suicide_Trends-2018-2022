# Student_Suicide_Trends-2018-2022
Project Overview
This data analysis project investigates the trends and demographics associated with student suicides over a five-year period (2018–2022). By examining variables such as educational attainment, geographic location, and gender, the goal is to identify high-risk groups and provide data-driven insights that could inform mental health interventions and educational policy.

🛠️ Tools & Technologies

Visualization: Power BI Desktop

Data Cleaning: Power Query (M Language)

Analytics: DAX (Data Analysis Expressions) for custom measures

Data Source: [Mention source, e.g., NCRB India / Open Government Data Portal]

🛠️ Technical Stack - Data Visualization:  Power BI (Tree Maps, Donut Charts, and Slicers).

Data Cleaning: Managing multi-year datasets to ensure consistency across state names and educational categories.

Domain Focus: EdTech, Social Analytics, and Student Welfare.

🚀 The Data Pre - Process

1. Data Cleaning & Transformation (Power Query)
 
Standardization: Handled inconsistent naming conventions across state names (e.g., correcting "West Bengal" vs "W.B.").

Pivoting: Transformed year-wise columns into a long format for better time-series analysis.

Data Typing: Ensured "Number of Deaths" was formatted as an integer and "Year" as a date/period for accurate X-axis plotting.

2. Key DAX Measures Created
   
Total Deaths: SUM('Suicide Data'[Deaths])

YoY Growth %: To calculate the percentage increase in cases from 2018 to 2022.

Gender Distribution %: DIVIDE([Male Deaths], [Total Deaths], 0)

Dashboard:
<img width="1466" height="784" alt="Screenshot 2026-03-24 125842" src="https://github.com/user-attachments/assets/bb799cbe-64fc-4ea7-ad0d-e25bcf3920c9" />


📈 Visual Analysis Breakdown

Time Series Chart: Displays a sharp rise in cases, peaking at 15.4K in 2022, suggesting a post-pandemic impact on student mental health.

Treemap (Geographic): Highlights Maharashtra and Madhya Pradesh as the states with the highest volume of reported incidents.

Donut Chart (Gender): Reveals a significant disparity, with Males representing ~69.8% of the total cases.

Bar Chart (Education): Identifies that students at the Matriculate/Secondary level are at the highest statistical risk.

🔍 Key Insights & Analysis

1. Educational Status Impact: Primary Concentration: The data indicates that students at the "Matriculate/Secondary" and "Middle" educational levels represent a significant portion of the total deaths. This suggests a critical need for mental health resources during early adolescent transitions.Professional & Higher Ed: While lower numbers are seen in "Professionals" and "Diploma" holders, the qualitative pressure in these fields remains a distinct area for investigation.


2. Demographic Trends - Gender Distribution: The donut chart reveals a stark disparity, with Male students accounting for approximately 69.81% of the reported cases, compared to 30.18% for Female students.Temporal Trends: The "Number of Deaths by Year" line chart shows a volatile trend, with a notable peak in 2019 ($14.3K$) and a rising trajectory toward 2022 ($15.4K$).


3. Geographic Distribution - Regional Hotspots: The Tree Map ("Sum of Number of Deaths by State Name") highlights Maharashtra, Madhya Pradesh, and Telangana as states with the highest reported figures, indicating potential regional socio-economic or academic stressors.


📈 Statistical Framework : 

Time-Series Forecasting: By analyzing the growth rate from 2020 ($10.4K$) to 2022 ($15.4K$), a moving average or exponential smoothing could be applied to forecast potential future trends if interventions are not scaled.

Categorical Analysis: Using the "Educational Status" as a categorical variable, we can perform a Chi-Square Test of Independence to determine if the frequency of these tragic events is significantly dependent on the level of education attained.

Ratio Analysis: Calculating the Male-to-Female ratio provides a clear metric for targeted outreach programs, specifically addressing the high prevalence among male students.




💡 Conclusion & Recommendations:

The upward trend observed between 2020 and 2022 necessitates immediate focus on student mental health. High-risk areas (Maharashtra) and high-risk educational levels (Secondary) should be the primary focus for pilot counseling programs and digital divide bridging efforts.Note: This data is analyzed for the purpose of identifying trends to support preventative measures. If you or someone you know is struggling, please reach out to local mental health professionals or helplines.

#DataAnalytics #DataDriven #Analytics #SQL  #Python #PowerBI #Tableau #Excel #DataAnalysis #LearningToCode #DataVisualization #CareerTransition #DataStrategy #BusinessIntelligence #TechTrends
