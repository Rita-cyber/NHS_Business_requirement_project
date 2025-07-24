# Hospital_Business_requirement_project_School Project

AnyHospital, a leading healthcare institution, is dedicated to thecontinual enhancement of patient care through innovative approaches.Acknowledging the transformative potential of data-driven insights, the hospital has embarked on a strategic initiative to harness the power of its extensive medical records. The Hospital plans to leverage cloud technologies to propel healthcare research, with a primary focus on disease prediction, prevention, and better patient care/experience.Clinicians, IT personnel, management, and patients are the stakeholders


In pursuit of this mission, the Hospital recognizes the need to adopt cutting-edge solutions to effectively analyze and extract meaningful insights from vast and diverse medical datasets they collect.The objective is to harness their data assets for making informed decisions and accomplishing their business objectives by navigating the intricacies of data management, analytics, and strategy by offering knowledge, direction, and advice.Relevance: - Facilitate data-driven choices to improve patient outcomes and healthcare delivery. To address this challenge, the hospital is implementing a data analytics solution on Azure, to enable seamless and efficient querying and analysis of medical data.

- A daily report of admitted Patients and discharged Patients- How long between admitted and discharged Patients- A daily report of diagnosis and treatment of patients- A daily report of scans and tests done- A daily report with the gender and age of patients.


##ERD Diagram

![image](https://github.com/user-attachments/assets/c740d662-816f-47ee-81a7-085dbe11bf78)

## Solution Architecture

![image](https://github.com/user-attachments/assets/416a09b8-9677-4e17-a34b-1caad72443fa)

Data Solution(ETL Process):- Ingest data frequently from on-prem sql database to  azure sql database.- Transform data into the star schema model for seamless extraction of business reports.- Load data into production Datawarehouse for analysis and visualization.

Project Challenges:1.Avoid Extraction of Duplicate record 2.Efficient Incremental data process3.Different schemas4.Different keys

<img width="940" alt="image" src="https://github.com/user-attachments/assets/310062bc-e980-4618-b46b-95ab67802117">

## Azure Logic App Settings

Click on use sample payload to generate schema and paste the below json in it

{"pipelineName": "",
  "RunId":"",
  "ErrorMessage" :""
    }

<img width="476" alt="image" src="https://github.com/user-attachments/assets/ce75e2a0-caae-49df-be27-4bc408a6be0c">

## Error Handling Setting

<img width="382" alt="image" src="https://github.com/user-attachments/assets/f938d8a3-f40d-49e9-9367-70032798bbef">


<img width="918" alt="image" src="https://github.com/user-attachments/assets/bfb81d87-31a9-42fd-8a76-499db64e7d2c">


