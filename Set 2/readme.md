**Q1-** Show unique birth years from patients and order them by ascending.

<img width="514" alt="1" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/84477578-87eb-4f7d-820b-848a792c7e9c">

**Q2-** Show unique first names from the patients table which only occurs once in the list.
For example, if two or more people are named 'John' in the first_name column then don't include their name in the output list. If only 1 person is named 'Leo' then include them in the output.

<img width="513" alt="2" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/6a1d45a0-bb90-4af8-9fca-626d7cad3378">

**Q3-** Show patient_id and first_name from patients where their first_name start and ends with ’s’ and is at least 6 characters long.

<img width="513" alt="3" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/0c1ff635-3a4c-4960-9d9b-1093c4c2c077">

**Q4-** Show patient_id, first_name, last_name from patients whos diagnosis is 'Dementia'.
Primary diagnosis is stored in the admissions table.

<img width="517" alt="4" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/af70c960-ae27-442a-958d-a0d92f615157">

**Q5-** Display every patient's first_name.
Order the list by the length of each name and then by alphabetically.

<img width="513" alt="5" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/5764a736-d309-4c28-ae16-068745277c39">

**Q6-** Show the total amount of male patients and the total amount of female patients in the patients table. Display the two results in the same row.

<img width="517" alt="6" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/dada9e52-0c68-45e5-8c98-b4b0aed19981">

**Q7-** Show first and last name, allergies from patients which have allergies to either 'Penicillin' or 'Morphine'. Show results ordered ascending by allergies then by first_name then by last_name.

<img width="515" alt="7" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/e0b0af25-c251-4e53-943e-9ca0c171ebce">

**Q8-** Show patient_id, diagnosis from admissions. Find patients admitted multiple times for the same diagnosis.

<img width="512" alt="8" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/b0dd349c-d0b8-4ad7-9011-5380030d471a">

**Q9-** Show the city and the total number of patients in the city. Order from most to least patients and then by city name ascending.

<img width="513" alt="9" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/6999af7d-4e1b-4823-b649-2b454ce692cd">

**Q10-** Show first name, last name and role of every person that is either patient or doctor.
The roles are either "Patient" or "Doctor"

<img width="515" alt="10" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/fce150cd-ac2f-4d99-872a-d25091be84a7">

**Q11-** Show all allergies ordered by popularity. Remove NULL values from query.

<img width="513" alt="11" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/1b27e5a1-c615-4220-a607-9e6d5a4e6a30">

**Q12-** Show all patient's first_name, last_name, and birth_date who were born in the 1970s decade. Sort the list starting from the earliest birth_date.

<img width="512" alt="12" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/176dd61a-57d2-4108-8ddb-c4935f917314">

**Q13-** We want to display each patient's full name in a single column. Their last_name in all upper letters must appear first, then first_name in all lower case letters. Separate the last_name and first_name with a comma. Order the list by the first_name in decending order
EX: SMITH,jane

<img width="512" alt="13" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/3a7b3a5f-2d09-4e4b-bf13-83cac74cf935">

**Q14-** Show the province_id(s), sum of height; where the total sum of its patient's height is greater than or equal to 7,000.

<img width="516" alt="14" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/6c98d45f-5a5e-42b4-9640-dd068114c2eb">

**Q15-** Show the difference between the largest weight and smallest weight for patients with the last name 'Maroni'

<img width="515" alt="15" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/8fb69ae6-9a9a-4780-aa07-628d1c016d8a">

**Q16-** Show all of the days of the month (1-31) and how many admission_dates occurred on that day. Sort by the day with most admissions to least admissions.

<img width="511" alt="16" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/30052118-87cc-4eb1-bea2-813eae86e82b">

**Q17-** Show all columns for patient_id 542's most recent admission_date.

<img width="516" alt="17" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/554ef5a2-f6ae-4498-91ee-60cae4febdf7">

**Q18-** Show patient_id, attending_doctor_id, and diagnosis for admissions that match one of the two criteria:
1. patient_id is an odd number and attending_doctor_id is either 1, 5, or 19.
2. attending_doctor_id contains a 2 and the length of patient_id is 3 characters.

<img width="514" alt="18" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/44f76f36-bb0e-4e02-9ae5-1e538de0471b">

**Q19-** Show first_name, last_name, and the total number of admissions attended for each doctor. Every admission has been attended by a doctor.

<img width="512" alt="19" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/e2d23c1d-3cc9-4e6b-b3de-0333416fbe25">

**Q20-** For each doctor, display their id, full name, and the first and last admission date they attended.

<img width="511" alt="20" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/46ac6c65-abf6-4294-809c-bf66ec59bf45">

**Q21-** Display the total amount of patients for each province. Order by descending.

<img width="514" alt="21" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/a02485db-704f-43be-90c7-90cfd5922ee0">

**Q22-** For every admission, display the patient's full name, their admission diagnosis, and their doctor's full name who diagnosed their problem.

<img width="511" alt="22" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/92c11808-e06c-4aa0-807d-a2fdc95a42d2">

**Q23-** Display the first name, last name and number of duplicate patients based on their first name and last name.
Ex: A patient with an identical name can be considered a duplicate.

<img width="515" alt="23" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/273d0c31-a30d-418e-9dd1-1fb85a13c2d3">

**Q24-** Display patient's full name, height in the units feet rounded to 1 decimal, weight in the unit pounds rounded to 0 decimals, birth_date, gender non abbreviated.
- Convert CM to feet by dividing by 30.48.
- Convert KG to pounds by multiplying by 2.205.

<img width="579" alt="24" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/d72a5e26-6ebb-47d0-a2d5-83c56bf22137">

**Q25-** Show patient_id, first_name, last_name from patients whose does not have any records in the admissions table. (Their patient_id does not exist in any admissions.patient_id rows.)

<img width="532" alt="25" src="https://github.com/gagansaleria/Healthcare_Database_Project---SQL-practice.com/assets/150334606/5339c127-4153-492f-a14f-ab1f7f330c7a">
