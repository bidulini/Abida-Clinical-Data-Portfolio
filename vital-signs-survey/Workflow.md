# REDCap Project Workflow: Health Data Collection

## Overview
This document describes the workflow for data entry and management in the Health Data Collection project.

## Workflow Steps

1. **Record Creation**
   - A new record is automatically assigned a `record_id`.
   - Record ID cannot be edited or deleted.

2. **Data Entry**
   - All fields in **Form 1** are required:
     - `age`
     - `gender`
     - `weight`
     - `height`
     - `blood_pressure_systolic`
     - `blood_pressure_diastolic`
     - `resting_heart_rate`
     - `smoker`
   - Data can be entered manually by the study team or via participant surveys if enabled.

3. **Data Validation**
   - REDCap ensures all required fields are completed before the record can be saved.
   - Any missing or invalid entries must be corrected immediately.

4. **Data Storage**
   - Completed records are securely stored in REDCap.
   - Only authorized users can access and export the data.

5. **Data Analysis**
   - Once data collection is complete, records can be exported for analysis.
   - Data integrity is maintained through required fields and automatic record ID assignment.

## Notes
- All data must be entered accurately to ensure reliable results.
- `record_id` serves as the primary key for all records.
