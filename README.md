Hospital Data Analysis Dashboard using Power BI

Objective / Purpose
The main objective of this project is to analyze and visualize hospital-related data to gain meaningful insights into patient care, doctor performance, hospital operations, and financial performance.
The dashboard helps hospital administrators make data-driven decisions to improve efficiency, optimize resources, and enhance patient services.

Data Description


Source: Excel dataset (imported into Power BI)


Structure: Multiple tables — Patients, Doctors, Appointments, Finance, and Hospital Details


Size: Around a few thousand records across various departments


Type of Data:


Patients Table: Patient_ID, Name, Age, Gender, Disease, Admission_Date, Discharge_Date


Doctors Table: Doctor_ID, Name, Department, Salary, Total_Appointments


Appointments Table: Appointment_ID, Date, Patient_ID, Doctor_ID, Status


Finance Table: Expenses, Revenue, Profit, Month, Year


Hospital Table: Total Beds, Departments, Locations, Staff Count





Data Cleaning & Transformation
Performed data cleaning and modeling using Power Query Editor in Power BI:


Removed duplicates and null values


Standardized date and text formats


Created relationships between fact and dimension tables


Derived new columns (e.g., Stay Duration, Profit Margin)


Added DAX measures for KPIs like Total Revenue, Total Patients, Average Stay Duration, Average Doctor Salary, etc.



Dashboard Design
The Power BI dashboard is divided into multiple pages for better understanding:


Home Page – Overview and navigation buttons to other reports


Overview Page – Key performance indicators (KPIs) such as

Total Patients
Total Doctors
Total Appointments
Total Revenue and Profit

Patient Analysis Page – Visuals for:
Patient distribution by gender, age group, and disease type
Admission vs. discharge trends over time
Doctor Analysis Page – Insights into:
Doctor-wise appointments and performance
Salary distribution
Department-wise doctor count

Finance Page – Charts showing:
Monthly revenue and expense trends
Profit analysis
Cost optimization insights
Hospital Details Page – Summary of:
Total staff, bed occupancy rate, departments, and service utilization

Key Insights :
Identified departments with the highest number of patient admissions.
Found correlations between patient stay duration and specific diseases.
Analyzed doctor workload and department efficiency.
Highlighted months with peak hospital revenue and high expenses.
Helped hospital management identify resource optimization areas.

Tools & Technologies Used :
Power BI Desktop – For visualization and reporting
Power Query Editor – For data cleaning and transformation
DAX (Data Analysis Expressions) – For KPI calculations
Excel – As the primary data source

Outcome :
This dashboard provides a centralized and interactive view of hospital data, enabling quick decision-making.
It helps stakeholders monitor performance metrics, improve patient management, and increase overall operational efficiency.
<img width="676" height="384" alt="Screenshot 2025-09-23 200149" src="" />

