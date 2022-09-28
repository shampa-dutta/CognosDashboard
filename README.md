Dashboard Link :
https://dataplatform.cloud.ibm.com/dashboards/71f7f0e1-2d78-4c42-bb6c-e4808cb7c162/view/4709c92a238f02c71fc5f6e4079d7a577d33240eb2bbd200d3d17b490e682597a96114c5c8794908df420d67f4ba130dcf


Guidelines: 
	1. Download the 2 files [m5_survey_data_demographics.csv](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/LargeData/m5_survey_data_demographics.csv?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-wwwcourseraorg-SkillsNetworkCoursesIBMDA0321ENSkillsNetwork21426264-2022-01-01) and [m5_survey_data_technologies_normalised.csv](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/LargeData/m5_survey_data_technologies_normalised.csv?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-wwwcourseraorg-SkillsNetworkCoursesIBMDA0321ENSkillsNetwork21426264-2022-01-01). Upload these 2 CSV files as data assets to your project in CDE.
	
  2. Create 3 dashboards (3 separate tabs under a single dashboard) as follows:
		○ One dashboard using the 2 x 2 rectangle areas tabbed template - rename this dashboard tab to Current Technology Usage.
		○ One dashboard using the 2 x 2 rectangle areas tabbed template - rename this dashboard tab to Future Technology Trend.
		○ One dashboard using the 2 x 2 rectangle areas tabbed template - rename this dashboard tab to Demographics.
		
	3. On the Current Technology Usage dashboard tab, use the data asset m5_survey_data_technologies_normalised.csv and capture the following metrics as visualizations:
		○ In the first rectangle (Panel 1):
			§ Capture Top 10 LanguageWorkedWith.
			§ Visualize as a Bar chart.
			§ Utilize Bars, Length, Color fields of Bar chart.
			§ Include Show value labels feature.
			§ Include a proper Chart title.
		○ In the second rectangle (Panel 2):
			§ Capture Top 10 DatabaseWorkedWith.
			§ Visualize as a Column chart.
			§ Utilize Bars, Length, Color fields of Column chart.
			§ Include Show value labels feature.
			§ Include a proper Chart title.
		○ In the third rectangle (Panel 3):
			§ Capture PlatformWorkedWith.
			§ Visualize as a Word cloud chart.
			§ Utilize Words, Size, Color fields of Word cloud chart.
			§ Include a proper Chart title.
		○ In the fourth rectangle (Panel 4):
			§ Capture Top 10 WebFrameWorkedWith.
			§ Visualize as a Hierarchy bubble chart.
			§ Utilize Bubbles, Size, Color fields of Hierarchy bubble chart.
			§ Include a proper Chart title.
	4. On the Future Technology Trend dashboard tab, use the data asset m5_survey_data_technologies_normalised.csv and capture the following metrics as visualizations:
		○ In the first rectangle (Panel 1):
			§ Capture Top 10 LanguageDesireNextYear.
			§ Visualize as a Bar chart.
			§ Utilize Bars, Length, Color fields of Bar chart.
			§ Include Show value labels feature.
			§ Include a proper Chart title.
		○ In the second rectangle (Panel 2):
			§ Capture Top 10 DatabaseDesireNextYear.
			§ Visualize as a Column chart.
			§ Utilize Bars, Length, Color fields of Column chart.
			§ Include Show value labels feature.
			§ Include a proper Chart title.
		○ In the third rectangle (Panel 3):
			§ capture PlatformDesireNextYear.
			§ Visualize as a Tree map chart.
			§ Utilize Area hierarchy, Size, Heat fields of Tree map chart.
			§ Include Contrast label color feature.
			§ Include a proper Chart title.
		○ In the fourth rectangle (Panel 4):
			§ Capture Top 10 WebFrameDesireNextYear.
			§ Visualize as a Hierarchy bubble chart.
			§ Utilize Bubbles, Size, Color fields of Hierarchy bubble chart.
			§ Include a proper Chart title.
	5. On the Demographics dashboard tab, use the data asset m5_survey_data_demographics.csv and capture the following metrics as visualizations:
		○ Use Filters for this tab feature to filter out entries of other types except Man and Woman from the data point Gender.
		○ In the first rectangle (Panel 1):
			§ Capture Respondent classified by Gender.
			§ Visualize as a Pie chart.
			§ Utilize Segments, Size fields of Pie chart.
			§ Include Dispay % feature.
			§ Include a proper Chart title.
		○ In the second rectangle (Panel 2):
			§ Capture Respondent Count for Countries.
			§ Visualize as a Map chart.
			§ Utilize Regions-Locations, Regions-Location color fields of Map chart.
			§ Include a proper Chart title.
		○ In the third rectangle (Panel 3):
			§ Capture Respondent Count by Age.
			§ Visualize as a Line chart.
			§ Utilize x-axis, y-axis fields of Line chart.
			§ Include Show value labels feature.
			§ Include Show markers feature.
			§ Include a proper Chart title.
		○ In the fourth rectangle (Panel 4):
			§ Capture Respondent Count by Gender, classified by Formal Education Level.
			§ Visualize as a Stacked bar chart.
			§ Utilize Bars, Length, Color fields of Stacked bar chart.
			§ Include Show value labels feature.
			§ Include a proper Chart title.

