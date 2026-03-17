## Overview
During my internship as a **Data Analyst Intern** at the MIS (Management Information Systems) Office, I was assigned a task to help improve the efficiency of the office’s data validation process.

The MIS office regularly processes a large volume of data submissions from students and staff. These records are typically submitted in spreadsheet format and must be validated before being entered into the university’s internal tracer system.

The existing workflow relied heavily on manual validation. Staff members needed to review records from spreadsheet files and manually verify each entry through the web-based tracer system. This process was time-consuming and increased the risk of human error and delays in processing records.

To address this issue, I explored ways to improve the workflow by implementing **data validation and automation techniques** using Microsoft Power Automate Desktop.

---

## Objective
The objective of this project was to design a more efficient workflow for validating and preparing submitted data before it is entered into the university’s tracer system.

The automation aimed to:

- Reduce the time spent on manual data validation
- Improve the accuracy and consistency of submitted data
- Streamline the data preparation workflow
- Support MIS staff by reducing repetitive manual tasks

---

## Workflow Overview

<p align="center">
  <img src="/Work Flow.png" width="200">
</p>

This diagram illustrates the overall workflow of the automated data validation process.

---

## Process Description

### 1. Excel Dataset
The process begins with a structured **Microsoft Excel** file containing records submitted by students or staff.

These records contain the information that needs to be validated through the tracer system.

---

### 2. Reading the Dataset
The automation workflow built using **Microsoft Power Automate Desktop** reads each row from the Excel dataset.

The records are stored in variables so they can be processed automatically.

---

### 3. Automated Web Form Input
Using **Google Chrome**, the automation enters the relevant information from each Excel record into the university’s web-based tracer system.

This replaces the manual process of typing the data into the website.

---

### 4. Validation Check
After submitting the information to the tracer system, the automation checks the response returned by the system.

- If the record is **valid**, the automation retrieves the confirmed data.
- If the record is **invalid or not found**, it is marked as **"Not Found"** in the Excel file for further review.

---

### 5. Data Extraction
For valid records, the automation extracts the confirmed information displayed on the tracer system webpage.

The extracted data is stored temporarily for processing.

---

### 6. Saving Processed Records
The validated information is written into a new Excel file in a structured format.

This allows the MIS office to easily:

- Review validated records
- Generate reports
- Maintain organized data archives

---

## Power Automate Desktop Workflow

<p align="center">
  <img src="https://github.com/Jerome-analyst/Power-automate-Internship-Project/blob/main/Main%20Automation%20%20Workflow.png" width="700">
</p>

<br>

<p align="center">
  <img src="/Main Automation Workflow(2).png" width="700">
</p>

The screenshots above show the automation workflow created in **Microsoft Power Automate Desktop**.  

The automation performs the following tasks:

1. Reads records from Excel  
2. Inputs the data into the tracer system  
3. Validates the results  
4. Extracts information from the webpage  
5. Saves the validated data back into Excel

---

## Expected Impact

The improved workflow helps the MIS office:

- Reduce manual validation workload
- Improve data accuracy and consistency
- Process records more efficiently
- Minimize potential human errors

---

## Tools Used

**Microsoft Excel**  
Used for organizing and storing the dataset that needs validation.

**Microsoft Power Automate Desktop**  
Used to automate the workflow including reading data, interacting with the tracer system, and recording results.

**Google Chrome**  
Used to access and interact with the university’s web-based tracer system.

---

## Skills Demonstrated

- Robotic Process Automation (RPA)
- Workflow Automation
- Data Validation
- Web Data Extraction
- Process Optimization

---

## Role

**Data Analyst Intern – MIS Office**
