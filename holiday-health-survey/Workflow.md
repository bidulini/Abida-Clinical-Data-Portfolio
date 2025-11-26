# Workflow: Health Behaviors During Traditional Holidays

This REDCap project was created to simulate a small health survey that collects behavioral information 
during traditional holiday periods.

## Step-by-Step Workflow

### 1. Project Setup
- Created a new REDCap project with one instrument named **Holiday Health Survey**.
- Enabled "Auto-numbering" for Record ID.

### 2. Fields Added
1. **country** (required) – Dropdown  
2. **age_group** (required) – Radio (18–29, 30–44, 45–59, 60+)  
3. **holidays** (required) – Radio (Eid, Christmas, Other)  
4. **other_holidays** – Text field  
   - *Branching logic*: Show only if `[holidays] = '3'`  
5. **how_many_meals** – Numeric  
6. **eat_more** – Yes/No  
7. **sugar_fat_food** – Radio (sugary vs fatty foods)  
   - *Branching logic*: Show only if `[eat_more] = '1'`  
8. **sleep** – Radio (sleep more or less)  
9. **hours_of_sleep** – Dropdown (≤5, 5–7, ≥7)

### 3. Validation & Logic
- Required fields applied to country, age_group, holidays.
- Branching logic tested and verified.
- Ensured no missing branching logic values.

### 4. Data Entry
- Entered 6 dummy sample participants to simulate realistic survey responses.

### 5. Data Export
- Exported dataset as **CSV**.
- Verified structure, variable names, and branching logic triggers.

### 6. Files Prepared for Portfolio
- Screenshot of full instrument.
- CSV file with 6 sample rows.
- This workflow description.

## Purpose
This project demonstrates practical REDCap skills:
- Form design  
- Field validation  
- Branching logic  
- Data structuring  
- Clean dataset export  

It serves as a practical example of foundational Clinical Data Management tasks.
