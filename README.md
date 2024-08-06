Worked on dataset consumer complaints of finance companies who provide variety of services like Loan,escrow account,Billing etc.The given data was not entirely in tabular form and proper data types.
So followed these steps for Data Cleaning,Exploration,Visualization and interpretation .

Data in the worksheet State_Code_Name were available in JSON format. Performed the following tasks as part of data preparation																
1. Created two new columns in the State_Code_Name worksheet and named them as STATE and CODE respectively.																
2. From the JSON format, fetched the data (STATE and CODE) in tabular form using excel options / excel functions like text to column.																
3. Created a new column in the worksheet Consumer_Complaints and named it State_Name																
4. Filled the column State_name in the worksheet Consumer_Complaints with the data from the State_Code_Name worksheet using Xlookup functions.
After that Worked on dates	as dates were not in proper date formats and performed data cleaning steps to get proper dates														
1. Resolution time (in days) after which the issue/complaint is resolved by the company?																
2. Created a new column YEAR using the date when complaint was received.																
3. Created a new column QTR (US FY) using the date when complaint was received.Based on US FY i.e. Q1 - JAN, FEB and MAR
Data Analysis:																
The count of records for which the State Name values didn't showed up (records with #N/A)															
Created a summary table to display number of complaints for only those State_Codes where State_Name is not mapped to State_Code in the worksheet Consumer_Complaints																
Given inferences for the possible reasons of non availabilty of the State_Name using the above steps.				         				
Then Created a report with following details for each Company Name 																
1. Company wise total number of complaints. Sorted the data in desc order of number of complaints																
2. The number and %age of complaints where the timely response was not shared.																
3. How many complaints were disputed. Also displayed the %age of number of complaints of the total complaints for each company.																
4. Average delay in days for closure of the complaints.																
Then Created a report with following details.																
1. Top five companies with maximum number of complaints along with count of complaints																
2. Top five issues with maximum number of complaints along with count of complaints																
3. Monthly trends of the number of complaints.
After making reports Create a Dashbord with following details on the year level																
1. For KPIs																
i. Total number of complaints registered in percentage with YOY change in the numbers														
ii. Number of complaints for which timely response was given with YOY change.													
iii. Average resolution time for the complaints with YoY change.															
2. Proportion of the # of complaints by different products																
3. Proportion of the # of complaints by different channels which were used to file the complaint 																
4. There is a limited bandwidth to look in all the complaints / issues raised by customers. Displayed graphically using pareto chart which complaints should be taken on priority.															
5. Monthly trend of the number of complaints in form of line / area chart 									
Used Slicers and filters to make dashboard interactive.
After that provide the key takeaways by seeing and using dashboard

             				
																		

