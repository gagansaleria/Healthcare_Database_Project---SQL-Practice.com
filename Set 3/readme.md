**Q1-** Show all of the patients grouped into weight groups.
Show the total amount of patients in each weight group.
Order the list by the weight group decending.

For example, if they weight 100 to 109 they are placed in the 100 weight group, 110-119 = 110 weight group, etc.

<img width="511" alt="1" src="https://github.com/user-attachments/assets/5a981039-8552-4575-9d35-82b8dab1f464">

**Q2-** Show patient_id, weight, height, isObese from the patients table.

Display isObese as a boolean 0 or 1.

Obese is defined as weight(kg)/(height(m)2) >= 30.

weight is in units kg.

height is in units cm.

<img width="515" alt="2" src="https://github.com/user-attachments/assets/eafb7579-b048-44b7-91e1-6a42bb6371fb">

**Q3-** Show patient_id, first_name, last_name, and attending doctor's specialty.
Show only the patients who has a diagnosis as 'Epilepsy' and the doctor's first name is 'Lisa'

Check patients, admissions, and doctors tables for required information.

<img width="465" alt="3" src="https://github.com/user-attachments/assets/571c0a55-8f32-4ffd-823b-f441fd3238aa">

**Q4-** All patients who have gone through admissions, can see their medical documents on our site. Those patients are given a temporary password after their first admission. Show the patient_id and temp_password.

The password must be the following, in order:
1. patient_id
2. the numerical length of patient's last_name
3. year of patient's birth_date

<img width="542" alt="4" src="https://github.com/user-attachments/assets/d085866f-154e-4e7e-91c5-f1bef2fc05d2">

**Q5-** Each admission costs $50 for patients without insurance, and $10 for patients with insurance. All patients with an even patient_id have insurance.

Give each patient a 'Yes' if they have insurance, and a 'No' if they don't have insurance. Add up the admission_total cost for each has_insurance group.

<img width="517" alt="5" src="https://github.com/user-attachments/assets/49b520a5-07f0-4754-ac7e-b5d60b114e9c">

**Q6-** Show the provinces that has more patients identified as 'M' than 'F'. Must only show full province_name

<img width="510" alt="6" src="https://github.com/user-attachments/assets/10296f56-2ef0-4bae-996a-e9d604a1c324">

**Q7-** We are looking for a specific patient. Pull all columns for the patient who matches the following criteria:
- First_name contains an 'r' after the first two letters.
- Identifies their gender as 'F'
- Born in February, May, or December
- Their weight would be between 60kg and 80kg
- Their patient_id is an odd number
- They are from the city 'Kingston'

<img width="514" alt="7" src="https://github.com/user-attachments/assets/b3544b23-3c91-4c58-b7ba-c96a16bc23c7">

**Q8-** Show the percent of patients that have 'M' as their gender. Round the answer to the nearest hundreth number and in percent form.

<img width="515" alt="8" src="https://github.com/user-attachments/assets/d7fd946e-939f-411b-bbaf-3c8f8d6cb4ba">

**Q9-** For each day display the total amount of admissions on that day. Display the amount changed from the previous date.

<img width="511" alt="9" src="https://github.com/user-attachments/assets/193c1568-07c0-4b09-b156-326ad4396b9b">

**Q10-** Sort the province names in ascending order in such a way that the province 'Ontario' is always on top.

<img width="511" alt="10" src="https://github.com/user-attachments/assets/313d457d-d115-4227-8001-6e7004736aec">

**Q11-** We need a breakdown for the total amount of admissions each doctor has started each year. Show the doctor_id, doctor_full_name, specialty, year, total_admissions for that year.

<img width="510" alt="11" src="https://github.com/user-attachments/assets/1935604c-c57e-497a-a9b3-4abc5df2c36f">
