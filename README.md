# vanguard-ab-test

**Link to the Google Presentation** https://docs.google.com/presentation/d/128DoqeuZ-MgDq1mq9aH-VO09iQbc-dkC1BiGo90oAgc/edit?usp=sharing

**Link to Trello** https://trello.com/b/FwU1pFdD/week4project

**Vanguard Data Analysis**
Project week 4 and 5

**Introduction**
Welcome to the Vanguard Project! This project focuses on analyzing and understanding client behaviors and demographics through various data analysis techniques. The primary goal is to draw insights from the data, identify trends, and improve client engagement strategies.

**About the Project**
Context The dataset comprises detailed information about client profiles, their digital footprints, and their interactions with different interfaces. This data helps to understand client behaviors, preferences, and the effectiveness of different interfaces in terms of user engagement and completion rates.

**Content**
This project involves several datasets including:

Client Profiles Experiment Roster Digital Footprints These datasets provide a comprehensive look at client demographics, their interactions with the digital interfaces, and the outcomes of these interactions.

**Acknowledgements**
The datasets used in this project are sourced from internal data provided by Vanguard, available on this link: https://github.com/data-bootcamp-v4/lessons/tree/main/5_6_eda_inf_stats_tableau/project/files_for_project

**Inspiration**
The insights derived from this data can help in improving user experience, optimizing interfaces, and enhancing client satisfaction. It can also aid in better understanding the demographic distribution and behavior patterns of the clients.

**Data Description**
Client Profiles

client_id: Unique identifier for each client.
gendr: Gender of the client.
clnt_age: Age of the client.
clnt_tenure_yr: Number of years the client has been with the company.
num_accts: Number of accounts the client holds.
bal: Account balance of the client.
calls_6_mnth: Number of calls made by the client in the last six months.
logons_6_mnth: Number of logons by the client in the last six months.
Digital Footprints

client_id: Unique identifier for each client.
date_time: Timestamp of the interaction.
process_step: The step in the process the client is in.
Variation: Indicates whether the client is in the test or control group.
Experiment Roster
client_id: Unique identifier for each client involved in the experiment.
Experiment Roster

client_id: Unique identifier for each client
variation: Indicates if a client was part of the experiment.

**Analysis and Insights**

**Univariate Analysis**
Age Distribution: Analyzing the distribution of client ages to understand the age demographics. Tenure Analysis: Examining how long clients have been with the company Balance Analysis: Investigating the distribution of account balances Gender Distribution: Understanding the gender breakdown of the clients

**Bivariate Analysis**
Interface Analysis Completion Rates: Comparing the completion rates of different interfaces (Test vs. Control). Time Spent Analysis: Analyzing the average time spent at each step in the process for both interfaces. Error Rates: Examining the error rates per interface and process step.

**Hypothesis Testing**
Completion Rate Comparison: conducting statistical tests to determine if the difference in completion rates between the test and control groups is significant. Time Spent Comparison: testing if there is a significant difference in the total time spent between the test and control groups. Client Distribution: checking if clients are randomly and evenly distributed between the old and new models.

**Instructions for Running the Analysis**
Upload the Files Import the necessary libraries and datasets. Data Cleaning Handle missing values and standardize categorical variables. Merge datasets as needed for comprehensive analysis. Data Analysis Perform univariate and bivariate analyses on client profiles. Conduct interface analysis to compare different groups. Run hypothesis tests to draw significant conclusions. Use Tableau, Matplotlib and Seaborn for visualizing the distributions, comparisons, and test results.

Conclusion This project provides valuable insights into client behaviors and demographics, helping to optimize user interfaces and enhance client engagement. By following the steps outlined, you can replicate the analysis and derive meaningful conclusions from the data.

Happy analyzing! 🎉
