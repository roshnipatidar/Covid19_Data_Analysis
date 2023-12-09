![image](https://github.com/roshnipatidar/Covid19_Data_Analysis/assets/143728620/cf255fd4-3dd4-4981-a7a4-c09a8833d474)


## Introduction
COVID-19, caused by the SARS-CoV-2 virus, has been a global respiratory pandemic since 2019. It can lead to mild or severe symptoms, impacting every aspect of our lives. To mitigate its spread, preventive measures like vaccination, mask usage, and social distancing are crucial. Research and cooperation are essential in its management.

## Problem Aimed to Solve

This project's objective is to conduct an analysis of the COVID-19 pandemic using publicly accessible data. It encompasses a Jupyter notebook containing Python code for the extraction, cleansing, and visualization of COVID-19 data from diverse sources. Moreover, the project offers an interactive dashboard for exploring this data.
<h2>
 📈COVID-19_ANALYSIS - 📑Brief Summary
</h2>

 Used Pandas and Json to gather data from API and then data cleaning.

 For K.P.I.’s and insights Used SQL to get useful data sets.
 
 Then transferred datasets to Excel for visualization.
  
  For the presentation used M.S. PowerPoint with the help of team members.
<h2>
 🪨Challenges and 🧠learnings-
</h2>

**JSON Data Extraction**: Skillfully navigated nested JSON structures to extract pertinent COVID-19 information.

**Data Cleaning**: Addressed missing values and discrepancies in COVID-19 data to ensure precise analysis.

**Code Optimization**: Enhanced processing efficiency for extensive COVID-19 datasets, improving overall performance.

**Domain Understanding**: Developed insights into public health and epidemiology by analyzing COVID-19 data.
 
  

## <img src="https://github.com/Sannidhi-Shetty2/COVID-19-Analysis/assets/62684303/1f211524-e1d5-46be-a421-2662597281d7" width="48" height="48" > Methodology
#### 1. Import the data from API using the requests library.
#### 2. The imported data was in JSON format hence we used JSON library to read the data.
![image](https://github.com/roshnipatidar/Covid19_Data_Analysis/assets/143728620/58280140-af56-4d78-8d62-afeb2b3db0ff)



#### 3. We looked for null values and replaced them with zero, looking for duplicates.
#### 4. Stated analyzing the data by using pandas functions like group by, sort_values, etc.
#### 5. Used nested 'for' loops to extract the relevant data from the nested dictionary.
![image](https://github.com/roshnipatidar/Covid19_Data_Analysis/assets/143728620/84f9342e-b851-4222-ac97-455f30187e42)
![image](https://github.com/roshnipatidar/Covid19_Data_Analysis/assets/143728620/2858e607-3b7f-4477-9092-339abbcf0e08)



#### 6. Extracted the individual state data from the data frame in CSV format and imported data into MySQL.
#### 7. Aggregated the distribution by month and week wise for each state.
#### 8. Imported the aggregated data into Excel for further Analysis.

##  <img src="https://github.com/Sannidhi-Shetty2/COVID-19-Analysis/assets/62684303/8e952995-c32d-4703-a9dd-92d1914cc6d9"  width="48" height="48"> Analysis/Insights
![image](https://github.com/roshnipatidar/Covid19_Data_Analysis/assets/143728620/334c8988-b055-4522-b747-0163e8d78f85)
![image](https://github.com/roshnipatidar/Covid19_Data_Analysis/assets/143728620/afb11aca-2d24-4578-bc20-d6f64d2486c1)
![image](https://github.com/roshnipatidar/Covid19_Data_Analysis/assets/143728620/9a65718d-859e-41c2-82f5-f759a9adcb28)


##  <img src="https://github.com/Sannidhi-Shetty2/COVID-19-Analysis/assets/62684303/126ceca9-e69e-43b4-851a-9de69526d082" width="48" height="48"> Dashboard
![image](https://github.com/roshnipatidar/Covid19_Data_Analysis/assets/143728620/235a1fba-4cd4-4f1a-afa7-2da4256a1c01)



## <img src="https://user-images.githubusercontent.com/108053296/185796560-b5035cfb-d8e4-4b61-b6fe-e0e75487bd94.gif" width="48" height="48" > Conclusions
1. Focusing on the weekly progression of COVID-19 cases, recoveries, deaths, and tests, the study offers valuable insights into the pandemic's impact across various regions and timeframes.
2. Observations revealed fluctuations in the number of cases and deaths, emphasizing the dynamic nature of the pandemic's effects in different geographical areas.
3. Through effective data visualization employing charts and graphs, this work enhances data clarity, facilitating the interpretation of trends and patterns.
4. The findings have practical importance for public health authorities, equipping them with the means to formulate more targeted and efficient strategies for curbing the virus's spread.

