# Introduction
Analysis for a fictional costumer support dataset.

---

# Project Name: Costumer Support Analysis (Deriving insights From Data)
---

# Problem Objective <br>

Data Analysis amd visualization using Power BI<br>
Creating a Bussiness dashboard that gives the insights on a fictional Customer Support datasets

---

# Tools used in actualizing the project

Power Bi<br>
Excel<br>
Notepad<br>

---

# Data Sourcing
The dataset was provided by my we_visualize community leader <br>
[Kola Ali](https://www.linkedin.com/in/adekolaaliu/) <br>
## The dataset includes 1 excel sheets;
- Closed trip list: This iclude more than 7 columns: 
    - City
    - Country
    - Creation Date
    - CSR priority 
    - CSR Status
    - CSR Type
    - CSR Number
    - Department
    - Neighborhood 
    - Overdue Flag
    - Date
---

# Data Transformation & Modeling

## Data Cleaning & Transformation
### - Step 1
After importing the datasets using the import method in power bi:<br>
Then, the first task i did was to clean the data by renaming misspelt values in columns, changing data-types and splitting the date-time columns (in tables that had them) to increase performance.<br>
I also created 
<br/>
![{A1E47CDE-A1CE-4396-837E-87C9E33EFCD6} png](https://user-images.githubusercontent.com/92920156/214124801-afb0d284-862a-4d20-a70e-d8b8ad27a625.jpg)


### - Step 2
I created a date table using blank query and M code.<br>
I also disabled power bi's defualt date table by setting my created table as my date table

## Data Modeling
I enabled many to one relationship and cross filter direction from the destination table (fact table) to other tables using their respective keys.
<br>
<br>
![model](https://user-images.githubusercontent.com/92920156/194776944-7cab5945-3346-414e-9f5a-8e61d43288d4.jpg)

---

# Findings and Recommendations 

## This dashboard contains
Which contains 5 main visuals, 5 cards and 1 slicers
### The cards shows:
- The Total Request
- Customer report by priority
  - Standard
  - Hazardous 
  - Emergency

### The slicers shows:
- Year Slicer to filter between years
- Status Slicer to filter overdue and under due customer report

### Now to the Visuals
- ### The first visual contains a bar charts showing thetotal request by neighborhood.
#### Importance of The visual
This visual will make its easier for the decision makers to know the neighbourhood with the most request.

- ### Treemap showing the total request by type
This visual shows the number of request by type
#### Importance of The visual
This will enable the stakeholders know the type of request which are being received.

- ### Pie chart showing the no of request by department
#### Importance of The visual
This will enable the stakeholders know the department that's receiving the most requests.

- ### Bar Charts Showing the number of request by day
#### Importance of The visual
This will enable the stakeholders know the days/ period they are receiving the most requests


## Findings
South queens neighborhood had the most requests, with public services department having the most requests.<br>
While mental and funitures had the most reports.

## Recommendation
I will recommed the stakeholders to take critical note of department with the most reports and those with the most report over due and compare them with those with lesser report in other to recommed and effective way to reduce the overdue status
<br><br>


[Link to live Report](https://app.powerbi.com/view?r=eyJrIjoiYTQ5NzhkZWMtMmM2OS00NmM2LTk5MTgtMmY1NzA0NDBjZjI1IiwidCI6Ijg4ZTlhN2RjLTU2MzMtNGM2Ni1iNjZjLTkyZGY1Y2E3NDhmYyJ9&pageName=ReportSection)



