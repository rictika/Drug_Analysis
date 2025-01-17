Impact of Drug Usage on Population in the US
Project Overview
This project analyses accidental drug-related deaths in the United States using two datasets:
1.	Accidental Drug-Related Deaths (2012-2023): Contains over 11,000 records of drug-related deaths across the U.S., with key attributes like age, gender, substances used (e.g., Fentanyl, Heroin), and location (county and state).
2.	Monthly Counts of Deaths by Cause (2014-2019): Includes data on deaths categorized by cause (e.g., drug overdose, accidents, suicide, and natural causes). This dataset allows for the comparison of drug-related deaths with other leading causes of mortality.
Key Insights
•	Rising Drug-Related Deaths: A dramatic increase in drug-related deaths over the past decade, especially driven by synthetic opioids like Fentanyl.
•	Gender Disparities: Males consistently represent the majority of drug-related incidents across various substances and regions.
•	Age Distribution: The 40-60 age group is most impacted, with a significant portion of incidents also occurring in the 20-40 age range.
•	Trends and Comparison: Drug-related deaths have tripled in the past decade, with a noticeable rise in proportion compared to other causes like accidents and suicides.
Dataset Overview
1. Primary Dataset
File:”Accidental_Drug_Related_Deaths_2012-2023.csv”
Details: This dataset provides details about drug-related deaths, including:
•	Age, gender, and county information.
•	Substances involved, such as Fentanyl and Heroin.
•	Dates of the incidents.
2. Supplemental Dataset
File: Monthly_Counts_of_Deaths_by_Select_Causes__2014-2019.csv
Details: This dataset tracks yearly deaths from causes like:
•	Car accidents
•	Suicide
•	Homicide
•	Drug overdose

How the Data Was Used:

Primary Dataset: “Accidental_Drug_Related_Deaths_2012-2023.csv”

Why We Used It:
We relied on this dataset to understand the specifics of drug-related deaths. The goal was to identify trends and patterns linked to demographics, substances, and times.

Key Applications:

1.	Who Is Affected?
   
We examined gender, age, and location to identify which groups are most at risk.
o	Cleaned up data inconsistencies, like filling missing ages and standardizing gender categories.

3.	Substance Trends:
	
Explored patterns in the use of substances like Fentanyl, Heroin, Cocaine, and others.
o	Used Simple techniques to make comparisons easier across different substances.

6.	Tracking Changes Over Time:
Looked at yearly incident trends to see how drug-related deaths evolved over time.

8.	Relationships Between Variables:
Built a correlation matrix to see how age and different substances might relate.

What We Learned:
•	Men are disproportionately affected by drug-related deaths.
•	The 40–60 age group is the most impacted.
•	Fentanyl use has surged in recent years, indicating a growing crisis.

Supplemental Dataset: “Monthly_Counts_of_Deaths_by_Select_Causes__2014-2019.csv”

Why We Used It:
This dataset helped us understand the broader context of drug-related deaths by comparing them to other causes of death, like suicides and car accidents.

Key Applications:
Year-by-Year Totals:
•	Analyzed yearly deaths for causes such as overdoses, suicides, and car accidents.
•	Summarized the total deaths for each cause to identify significant trends.

1.	Spotting Patterns:
Used a heatmap to highlight how deaths from different causes changed year by year.

3.	Comparing Drug Deaths:
Showed how drug overdoses stand out compared to other causes of death.

What We Learned:

•	Drug overdoses have risen consistently, emphasizing the need for urgent attention.
•	Suicide rates have remained stable, while car accident deaths showed fluctuations but ended on a downward trend.
•	Homicide rates, while lower overall, stayed steady compared to overdoses and suicides.

Requirements:

How to Set Up in Google Colab:

1. Upload the Repository to Google Colab
2.	Clone the repository:
!git clone https://github.com/your-repo.git
%cd your-repo

2. Upload Datasets
You can store your datasets in Google Drive and mount the drive:
from google.colab import drive drive.mount('/content/drive')

4. Run the Scripts:
   
Run the following scripts to clean, analyze, and visualize the data:

1.	Data Cleaning: Prepare the data using data_cleaning.py:
2.	Visualization: Generate visualizations using visualization.py:
3.	Analysis: Perform statistical analysis using analysis.py:

Project Files:

1. Datasets
•	Accidental_Drug_Related_Deaths_2012-2023.csv: Contains data on drug-related deaths across the U.S.
•	Monthly_Counts_of_Deaths_by_Select_Causes__2014-2019.csv: Data on deaths categorized by cause.
2. Scripts steps
•	Data Cleaning: Cleans the data and fills in missing values.
•	Visualization: Creates visualizations, such as bar charts and line plots.
•	Analysis: Handles deeper statistical exploration, including correlation analysis and identifying trends.
3. PowerPoint Presentation
Drug_Analysis_Finalized_Presentation.pptx: A detailed presentation summarizing the findings, visualizations, and insights from the analysis.

