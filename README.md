# Healthtail-Company
BigQuery insights with Looker Studio


## TABLE OF CONTENT
1. [Project Overview](#project_overview).
2. [Requirements Of The Project](#requirements_of_the_project).
3. [Challenges Faced By Healthtail](#challenges_faced_by_healthtail).
4. [Developing A Plan For ETL And Loading Data](#developing_a_plan_for_etl_and_loading_data).
5. [Dashboard](#dashboard).
6. [Insights](#insights).
7. [Recommendations](#recommendations).


## **PROJECT OVERVIEW.**

Healthtail a veterinary hospital and they approached Clinipet seeking to automate their manual auditing process for medications.


## **REQUIREMENTS OF THE PROJECT.**

To successfully complete the project, it's broken down into 3 manageable steps:

1. Cleaning the data & creating aggregated tables using SQL.
2. Answering research questions using SQL.
3. Creating interactive report in Looker Studio.


## **CHALLENGES FACED BY HEALTHTAIL.**

1. Auditing medication purchases and expenses.
2. Monitoring diagnoses and disease trends.

## **DEVELOPING A PLAN FOR ETL AND LOADING DATA.**

This process is divided into 3 steps:

Plan for ETL Step 1:
Cleaning the data using queries (in BigQuery) to fix the problem in the columns in healthtail_reg_cards table, in particular:
- apply standardisation on column patient_name.
- remove non-numeric data from column owner_phone.
- replace missing values in column breed with "Unknown".

Creating a table med_audit 
- using SQL that aggregate the medications received monthly.
- Second query that aggregate the medications spent monthly.
- Apply UNION to combine both subqueries (use of CTEs).
  
  This stage helps to track the monthly movement of medications, including purchases and usage during visits or procedures.

  Plan for ETL Step 2:
  Answering the research questions using SQL which you can find the queries in the SQL BigQuery folder above and by using the med_audit table created in BigQuery console.

![Screenshot 2025-05-15 at 11 02 22](https://github.com/user-attachments/assets/2bbb4cc1-8443-459f-9afe-c75e898fc683)


Plan for ETL Step 3:

Required a tool to monitor the most common diagnose, track the prevalence of diseases across different breeds, and analyze spending on specific medications related to these conditions.

![Screenshot 2025-05-15 at 09 21 07](https://github.com/user-attachments/assets/9754f2b7-44d1-425e-8f4b-24dded1327fa)


## **DASHBOARD.**






**Looker Studio Link**



## **INSIGHTS.**




## **RECOMMENDATIONS.**































  
