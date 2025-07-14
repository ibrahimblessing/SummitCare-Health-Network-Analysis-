# SummitCare Health Network-Analysis

## Project Background
SummitCare Health Network is a growing chain of hospitals and clinics committed to providing top-quality, patient-centered care. As part of their efforts to modernize operations, the organization recently centralized its data, bringing together patient records, treatments, admissions, and financial details into one digital system.

While this was a big step forward, the leadership team quickly realized that having access to more data did not automatically lead to better decisions. They were overwhelmed by the volume of information and needed help turning it into something useful.

That is where I came in. As a Data Analyst, my role was to look  into the hospital’s dataset, clean and organize the information, and use Power BI to uncover insights that could guide better decisions. From understanding patient demographics and medical conditions to analyzing doctor performance and hospital finances, my goal was to help the SummitCare team see the story behind the numbers and use it to improve care and operations.

## Objectives
- Analyze patient demographics (age, gender, blood type)
- Explore common medical conditions and medication.
- Monitor doctor performance
- Track types of hospital admissions
- Analyze insurance coverage
- Evaluate financial performance and revenue trends
- Understand health test outcomes

## Dashboard and Visuals
Patient Demographics and Medical Condition analysis
<img width="1107" height="640" alt="Screenshot 2025-07-11 210152" src="https://github.com/user-attachments/assets/afb3ee07-fb86-4b9c-833a-e5afb38df1e5" />

Billing Trend and Insurance Provider Analysis 
<img width="1108" height="639" alt="Screenshot 2025-07-11 210242" src="https://github.com/user-attachments/assets/35a032ca-fa86-438f-964a-ceb452f7602a" />

Interact with report [here](https://app.powerbi.com/view?r=eyJrIjoiMzkxOTY0ZTEtMDRkNC00N2FhLWE0MDctYjE3MzlkNzUwOTc5IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9/)

## Exploratory Analysis
### Demographic Analysis
- Q1: What is the distribution of patients by age and gender?
         Over the 6-year period (2019–2024), the majority of admitted patients fall within the age ranges of:
25–34, 35–44, 45–54, 55–64, 65–74, 75–89.
Very few patients were aged 13–15, while the 74–85 age group recorded the highest concentration of admissions.

There is also a slightly higher number of female patients compared to males across all years, although the difference is minimal.


- Q2: What are the most common blood types among patients?
      The most common blood type among patients is A+, indicating a potential consideration for blood supply and donor matching in future planning.

<img width="748" height="485" alt="Screenshot 2025-07-11 220448" src="https://github.com/user-attachments/assets/32d59f40-1ce4-4e8d-8eb2-9a1d695d00a1" />

### Medical Condition Analysis
- Q1: What is the frequency of each medical condition?
-- 2019 & 2021: Diabetes was the most prevalent condition, followed by Hypertension.
-- 2020, 2022 & 2023: Hypertension became the leading condition.
-- 2024: Diabetes led again, followed by Obesity and Hypertension. A majority of these cases were reported among female patients.
-- Across all years, Asthma consistently had the lowest occurrence among medical conditions.

- Q2: Which medications were commonly used, and how many patients received each?
Most medications have been consistently used throughout the years, with only slight variations in the number of patients treated with each drug.
<img width="742" height="485" alt="Screenshot 2025-07-11 214752" src="https://github.com/user-attachments/assets/406ed77a-f677-476e-a570-49d990f8557c" />

### Admission Analysis
- Q1: What is the distribution of admission types (Emergency, Elective, Urgent)?
Admission patterns across the years were relatively balanced:
-- Elective Admissions: 33.61%
-- Urgent Admissions: 33.47%
-- Emergency Admissions: 32.92%

This distribution shows that healthcare services are catering almost equally to planned and unplanned cases.

<img width="360" height="253" alt="Screenshot 2025-07-11 214908" src="https://github.com/user-attachments/assets/d694d52e-83e6-4f49-8409-aa63cfdad4d8" />


### Doctor Performance Analysis
-  Q1: Who are the top-performing doctors based on the number of patients treated?
The following doctors treated the highest number of patients:
-- Dr. Michael Smith
-- Dr. John Smith
-- Dr. Robert Smith
-- Dr. James Smith
-- Dr. Michael Johnson
Their consistent performance can be considered for benchmarking and mentoring purposes.


### Insurance Provider Analysis
- Q1: What is the distribution of patients by insurance provider?
Medicare had the highest number of patients at both Houston Methodist Hospital and Johns Hopkins.
UnitedHealthcare followed closely, indicating strong coverage and preference across these institutions.


### Health Outcomes Analysis
-  Q1: What is the distribution of test results across different medical conditions?

<img width="1259" height="687" alt="Screenshot 2025-07-11 215130" src="https://github.com/user-attachments/assets/9a40fa2a-da39-4669-a4af-62ee29dc260a" />

### Financial Analysis
- Q1: What is the total revenue generated by the hospital?
Over $1.42Bn was generated over the years.
- Q2: What are the billing trends over time?

 <img width="740" height="575" alt="Screenshot 2025-07-11 215238" src="https://github.com/user-attachments/assets/1eaa94f1-50b7-4c65-8f1f-bf5a108272d9" />

## Tool Used
- Power BI (Data modeling, DAX, Relationships, Slicers, Visuals)
- Power point for report framework.

## Data Source
HealthCare Excel file Containing 
- Patients IDs
- Age: The age of the patient at the time of admission, expressed in years.
- Gender: Indicates the gender of the patient, either "Male" or "Female." 
- Blood Type: The patient's blood type, which can be one of the common blood types (e.g., "A+", "O-", etc.). 
- Medical Condition: This column specifies the primary medical condition or diagnosis associated with the patient, such as "Diabetes," "Hypertension," "Asthma," and more. 
- Date of Admission: The date on which the patient was admitted to the healthcare facility.
- Doctor: The name of the doctor responsible for the patient's care during their admission.
- Insurance Provider: This column indicates the patient's insurance provider, which can be one of several options, including "Aetna,"Cigna," "UnitedHealthcare," and "Medicare.
 - Billing Amount: The amount of money billed for the patient's healthcare services during their admission. This is expressed as a floating-point number.
- Room Number: The room number where the patient was accommodated during their admission. 
- Admission Type: Specifies the type of admission, which can be "Emergency," "Elective," or "Urgent," reflecting the circumstances of the admission.

## Data Preparation
- Data loading and inspection.
- Data cleaning: Formatting all cases of columns with string to sentence cases.
- Normalize data to get a dim table for medical conditions, added a new column for description and images.
- Added a date table for trend analysis.
- 
## Reference
Wikipedia for Medical condition images and descriptions.

