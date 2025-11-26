# Branching Logic – Holiday Health Behavior Survey

This document lists all conditional display rules used in the REDCap instrument
“Holiday Health Behavior Survey”.

---

## 1. Field: other_holidays
**Condition:**  
[holidays] = '3'

**Explanation:**  
This field is shown only when the participant selects **"Other"** as the type
of holiday they celebrate.

---

## 2. Field: sugar_fat_food
**Condition:**  
[eat_more] = '1'

**Explanation:**  
This field is shown only when the participant answers **"Yes"** to the
question “Do you eat more during the holidays?”

---

## Summary
These two rules demonstrate the use of REDCap branching logic to create
adaptive and participant-friendly surveys. Conditional questions ensure that
participants only see fields relevant to their previous answers, improving data
quality and reducing unnecessary inputs.
