# NHS_Business_requirement_project_School Project

AnyHospital, a leading healthcare institution, is dedicated to thecontinual enhancement of patient care through innovative approaches.Acknowledging the transformative potential of data-driven insights, the hospital has embarked on a strategic initiative to harness the power of its extensive medical records. The Hospital plans to leverage cloud technologies to propel healthcare research, with a primary focus on disease prediction, prevention, and better patient care/experience.Clinicians, IT personnel, management, and patients are the stakeholders

![image](https://github.com/user-attachments/assets/fc016f89-bab0-432c-94e6-3980c6fc811f)

In pursuit of this mission, the Hospital recognizes the need to adopt cutting-edge solutions to effectively analyze and extract meaningful insights from vast and diverse medical datasets they collect.The objective is to harness their data assets for making informed decisions and accomplishing their business objectives by navigating the intricacies of data management, analytics, and strategy by offering knowledge, direction, and advice.Relevance: - Facilitate data-driven choices to improve patient outcomes and healthcare delivery. To address this challenge, the hospital is implementing a data analytics solution on Azure, to enable seamless and efficient querying and analysis of medical data.![image](https://github.com/user-attachments/assets/f3253278-27f7-43b8-afb0-5d214702d59f)

- A daily report of admitted Patients and discharged Patients- How long between admitted and discharged Patients- A daily report of diagnosis and treatment of patients- A daily report of scans and tests done- A daily report with the gender and age of patients![image](https://github.com/user-attachments/assets/b99fbeca-80d3-477b-981d-737e57a3b445)


##ERD Diagram

![image](https://github.com/user-attachments/assets/c740d662-816f-47ee-81a7-085dbe11bf78)

## Solution Architecture

![image](https://github.com/user-attachments/assets/416a09b8-9677-4e17-a34b-1caad72443fa)

Data Solution(ETL Process):- Ingest data frequently from on-prem sql database to  azure sql database.- Transform data into the star schema model for seamless extraction of business reports.- Load data into production Datawarehouse for analysis and visualization.![image](https://github.com/user-attachments/assets/b267e8ba-72f7-4342-b93f-32d4e207b9c3)

Project Challenges:1.Avoid Extraction of Duplicate record 2.Efficient Incremental data process3.Different schemas4.Different keys![image](https://github.com/user-attachments/assets/de4aa87f-feee-41a4-9e3f-cb0997c2ba69)

<img width="940" alt="image" src="https://github.com/user-attachments/assets/310062bc-e980-4618-b46b-95ab67802117">


<img width="940" alt="image" src="https://github.com/user-attachments/assets/dee21f19-b715-4641-93c6-8f5210738cea">
