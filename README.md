# Oncology-Patient-Tracking (Power BI & EXCEL) ![image](https://github.com/user-attachments/assets/9a28568f-58a8-4755-82f7-9fb403917eed)


Cancer treatment requires **continuous monitoring**, **timely interventions**, and **seamless coordination** among healthcare providers.  
The Oncology Patient Tracking is a **data-driven solution** designed to **enhance patient management**, **streamline workflows**, and **improve outcomes** in oncology care.

### Project Report

## 1. Overview
The Oncology Patient Tracking is designed to monitor key clinical metrics for cancer patients. It focuses on patient outcomes, visit types, discharge patterns, and prolonged hospital stays. Insight generated from this analysis will enables healthcare providers and administrators to identify high-risk groups, streamline discharge processes, and enhance care coordination.

## 2. Purpose of the Analysis
To track and analyze oncology patient visits, outcomes, and discharge behaviors to:
- Identify trends in prolonged hospital stays
- Understand mortality and discharge rates
- Assess patient visit types and hospital burden
- Provide actionable insights for hospital operations and patient care

## 3. Key Objectives
- Track total patient volumes and visit types
- Segment patients by age, life status, and discharge method
- Identify patterns in prolonged hospital stays
- Enable hospital-level and patient-type filtering for deeper analysis

## 4. Scope of the Analysis
- **Population**: 444 oncology patients
- **Data Points**: Patient type, age group, discharge method, life status, stay duration
- **Filters**: Hospital, Patient Number
- **Time Frame**: Based on latest clinical admission and discharge records

## 5. Data Cleaning and Preparation using Excel
This project focuses on cleaning three independent data sets and preparing data to ensure it is well-structured and ready for analysis. Below are the steps involved in the data cleaning process:

## Steps Involved:
**Removed Duplicates and Standardized Patient Type Categories**
   - Identified and removed duplicate entries to ensure data integrity.
   - Standardized the patient type categories for consistency across the dataset.
**Categorized Patients into Age Groups**
   - Grouped patients into distinct age categories such as:
     - 65+
     - 51–65
     - Other relevant age groups
**Cleaned Null Values in Discharge Methods and Status**
   - Handled null or missing values in discharge methods and discharge status fields to ensure complete records.
**Calculated Prolonged Stays Based on Admission-Discharge Intervals**
   - Calculated patients' prolonged stays by analyzing the difference between admission and discharge dates.
**Appended Two Cleaned Datasets in Power BI editor**
   - Appended the three datasets that were initially cleaned using Excel and uploaded into Power BI for final integration into the main dataset.

## Tools Used:
- Excel
- Power BI
- Data Cleaning and Preparation Techniques


## 6. Data Sources
- Clinical data from external patient record source.

## 7. Data Dictionary

| Field            | Description                                      |
|------------------|--------------------------------------------------|
| **Patient_ID**    | Unique patient identifier                        |
| **Patient_Type**  | Type of visit (New, Referral, Continuation)      |
| **Age**           | Patient's age (used to generate age groups)      |
| **Life_Status**   | Alive or Deceased                                |
| **Discharge_Method** | How the patient was discharged                  |
| **Prolonged_Stay** | Derived flag for extended hospital stay          |

## 8. Dashboard Overview
The dashboard includes:
- **Total Patients**: 444
- **Total Patient Visits**: 3,000
- **Prolonged Stays**: 1,000+

### Key Visuals:
- **Patient Status**: Pie chart of Alive vs. Deceased
- **Discharge Methods**: Bar chart of outcomes including clinical advice and mortality
- **Prolonged Stay by Age Group**: Younger patients have fewer long stays
- **Visit Types**: New, Continued, and Referred visits tracked over time
- **Dynamic Filters**: By hospital and patient type


  ![ONCOLOGY PATIENT TRACKING](https://github.com/user-attachments/assets/24043706-2d90-4d39-9b16-a26b5429c0b3)


## 9. Project Access

- Use the Power BI Desktop (latest version) to view project [here](https://app.powerbi.com/groups/me/reports/e3d921e5-7fc0-44d5-83ae-83414beb0833?ctid=43b41731-b631-4e1d-9c02-d28ae0282fdc&pbi_source=linkShare)

## 10. Recommendations

| Theme             | Recommendation                                       | Actionable Steps                               |
|-------------------|------------------------------------------------------|------------------------------------------------|
| **Prolonged Stays** | Investigate causes of long stays in elderly patients | Initiate case reviews for 65+ group            |
| **Patient Outcomes** | High mortality and discharge gaps require attention | Implement follow-up for non-discharged patients|
| **Visit Management** | Streamline new vs. referral visit handling          | Develop referral protocols and triage strategies|
| **Dashboard Usage** | Train stakeholders to use filters for insights      | Conduct staff sessions on using Power BI views |

## 11. Author

**Anna Paul**  
*Data Analyst*  
📍 Abuja, Nigeria  
📧 [annapaul668@gmail.com](mailto:annapaul668@gmail.com)  
📞 +234 8142944324
