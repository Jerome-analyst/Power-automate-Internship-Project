# Power-automate-Internship-Project
# Overview
During my internship as a Data Analyst Intern at the MIS (Management Information Systems) Office, I was assigned a task to help improve the efficiency of the office’s data validation process.

The MIS office regularly processes a large volume of data submissions from students and staff. These records are typically submitted in spreadsheet format and must be validated before being entered into the university’s internal tracer system.

The existing process relied heavily on manual data validation, which required staff to review records from spreadsheet files and manually verify them through the web-based tracer system. This workflow was time-consuming and increased the risk of human errors and delays in processing records.

To address this issue, I explored ways to improve the workflow by introducing data validation and automation techniques.

# Objective
The objective of this project was to design a more efficient workflow for validating and preparing submitted data before it is entered into the university’s tracer system.

The automation aimed to:

-Reduce the time spent on manual data validation

-Improve the accuracy and consistency of submitted data

-Streamline the data preparation workflow

-Support MIS staff by reducing repetitive tasks
# Workflow Overview
<p align = "center">
   <img src= "/Work Flow.png">
</p>

#  Process Description 
1. Excel Data Set
The process starts with a structured Excel file containing student or staff records that need validation.

2. Power Automate Reads the Records
The automation workflow, built using Microsoft Power Automate, reads each row of data from the Excel dataset.

3. Data is Entered into the Tracer Website
Power Automate automatically inputs the relevant information from each record into the university’s web-based tracer system for validation.

4. Check Validation Result
The workflow verifies the response from the tracer system:

   -If the record is valid, the process continues to retrieve the validated data.

   -If the record is invalid or not found, it is marked as “Not Found” directly in the Excel file for further review.

5. Retrieve Validated Data
For valid records, the automation collects the confirmed information from the tracer system.

6. Save Processed Records
All validated data is saved into a new Excel file with a clean, structured format, making it easier for the MIS office to review, report, and archive.
# Demonstration

# Expected Impact
-The improved workflow helps the MIS office:

-Reduce manual validation workload

-Improve data accuracy and consistency

-Process records more efficiently

-Minimize potential human errors
# Tools I used
Microsoft Excel — For data cleaning, organization, and validation of submitted datasets.

Power Automate — To automate the process of reading data, entering it into the tracer system, and recording results.

Google Chrome — Used to access and interact with the university’s web-based tracer system.

