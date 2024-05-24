Data Transformation: Using the MIMIC-IV FHIR dataset

The aim of this project is to transform the MIMIC-IV FHIR dataset into a structured format suitable for analysis by converting its JSON files containing patient, condition, and encounter data into a CSV file that maps patient IDs to condition timestamps. This involves the following steps:

Extract Data: Read and understand the JSON data structures from the MIMIC-IV FHIR dataset, which includes files for patients, conditions, and encounters.
Process Data: Normalize and process the JSON data to handle nested structures, ensuring that each patient and their associated conditions and encounters are correctly mapped.
Merge Data: Link each condition to its corresponding patient and encounter, assigning accurate timestamps based on encounter data.
Create Structured Output: Generate a CSV file with columns for patient ID (pid) and condition timestamp (time) in Unix format, providing a comprehensive and analyzable dataset for further analysis or machine learning tasks.

Thus, this transformation facilitates easier analysis and utilization of the MIMIC-IV FHIR data for research and clinical insights.

Link to the dataset: https://physionet.org/content/mimic-iv-fhir-demo/2.0/mimic-fhir/

Download it via: https://physionet.org/static/published-projects/mimic-iv-fhir-demo/mimic-iv-clinical-databasedemo-on-fhir-2.0.zip
