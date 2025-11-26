# Health Behaviors During Traditional Holidays

This project is a simple REDCap survey examining changes in health habits during traditional holidays. 
It demonstrates branching logic, required fields, different field types, and basic data validation.

## Fields Included
1. **Record ID**
2. **Country** – required
3. **Age Group** – required (18–29, 30–44, 45–59, 60+)
4. **Holidays Celebrated** – required (Eid, Christmas, Other)
5. **Other Holidays** – branching logic: shown only if Holidays = "Other"
6. **Number of Holiday Meals per Day**
7. **Do You Eat More During Holidays?** – Yes/No
8. **Sugary or Fatty Foods** – branching logic: shown only if Eat More = "Yes"
9. **Sleep Pattern During Holidays**
10. **Hours of Sleep**

## Features Demonstrated
- Required fields  
- Branching logic  
- Conditional questions  
- Mixed field types  
- Validation for age group and conditional text fields  
- Exported CSV sample  
- Dummy dataset (5–10 entries)  

## Files Included
- `FormScreenshot.png`
- `CSV_sample.csv`
- `Workflow.md`

## Purpose
This project shows the ability to design a clean REDCap survey, apply logic and structure to data entry, 
and prepare exported datasets for further analysis or reporting.
