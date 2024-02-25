
# AtliQ HR-Analytics Dashboard 

### Dashboard Link :https://app.powerbi.com/groups/me/reports/170b7469-486a-4acd-9e4b-7536bbf1dfa4/ReportSection?experience=power-bi

## Problem Statement

This dashboard helps the HR of AtliQ company to understand their employees attendance better. It helps the company to know if their employees working prefernce is either WFH or WFO, along with their attendence percentage and sick leave percentage. With given 3 months of real dataset and through different measures like attendance keys for example, WFH, WFO, SL, WO, HO, etc.to get to know their improvement area, & thus they can improve their attendence by identifying these area. It also lets them know the percentage of employees working from home as well as office, thus since by using this dashboard they have identified this problem, they can further work on preference factors of employees as well as there attendence.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor and checked there were 4 sheets of data including 3 months data and an attendance sheet. 
- Step 3 : To combine all the 3 months data in a single sheet we select only a single sheet and open it.
- Step 4 : It was observed that there were no specific headers so we removed the top rows and made the 1st row as the headers and changed the column names.
- Step 5 : By using unpivot columns all the columns were merge into a single column. 
- Step 6 : Dates column name was change to Date along with its datatype by removing texts rows. 
- Step 7 : A parameter is created to limit the data which is named as worksheet, and a template is also created which is converted into a function by selecting invoke custom function.
- Step 8 : Metrics such as 'Total Working Days', 'Non-workdays','WFH count', 'SL count', and many more are created using DAX function for quantitative assesment in a new measure table.
- Step 9 : Calculated feilds like 'WHO%', 'SL%', 'Attendance%'  were created to know the percentage of the employees throught the 3 months, which were used as slicers.
- Step 10 : 3 area stacked charts are created to know the flow of attendence%, WFH%, and SL%. 
- Step 11 : Matrix Visuals was used to represent percentage of attendence, WFH, and SL of employees throught the 3 months.

# Snapshot of Dashboard (Power BI Desktop)

![dashboard_snapo] ![Screenshot 2024-02-23 225634](https://github.com/ashubhagwat/Data-Analytics-Projects/assets/147173907/72569332-7d55-4b15-aa02-e76e369c68f4)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Attendence in APR month = 94%

WFH% in APR = 9% 

SL% in APR = 0%  

### [1.1] Total Attendence in May month = 90%

WFH% in APR = 11% 

SL% in APR = 2%  

### [1.2] Total Attendence in June month = 91%

WFH% in APR = 14% 

SL% in APR = 1%  

### Attendence percentage has declined from month of April having 93% to the month of June 17th having 90%.

### WFH percentage has increased from month of April having 9.59% to the month of June 17th having 16.31% 

### Sick Leave percentage has increased from month of April having 0% to the month of June 17th having 2.5%.
