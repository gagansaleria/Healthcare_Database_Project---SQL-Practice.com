# Healthcare Database Project

This project involves analyzing data from a healthcare database. The data is organized into 4 tables, and various SQL queries were used to extract meaningful insights. The queries were written using PostgreSQL. Below is an overview of the database schema, followed by the specific questions addressed in the project.

## Database Schema

The database schema consists of the following tables:

**1. Patients-** patient_id, first_name, last_name, gender, birth_date, city, province_id, allergies, height, weight
**2. Admissions-** patient_id, admission_date, discharge_date, diagnosis, attending_doctor_id
**3. Doctors-** doctor_id, first_name, last_name, specialty
**4. Province Names-** province_id, province_name

## Question Set - Easy

**Q1**: Show first name, last name, and gender of patients whose gender is 'M'.
**Q2**: Show first name and last name of patients who do not have allergies (NULL).
**Q3**: Show the first name of patients that start with the letter 'C'.
**Q4**: Show the first name and last name of patients whose weight is within the range of 100 to 120 (inclusive).
**Q5**: Update the `patients` table for the allergies column. If the patient's allergies are NULL, replace them with 'NKA'.
**Q6**: Show the first name and last name concatenated into one column to show their full name.
**Q7**: Show the first name, last name, and the full province name of each patient (e.g., 'Ontario' instead of 'ON').
**Q8**: Show how many patients have a birth_date with 2010 as the birth year.
**Q9**: Show the first_name, last_name, and height of the patient with the greatest height.
**Q10**: Show all columns for patients who have one of the following patient_ids: 1, 45, 534, 879, 1000.
**Q11**: Show the total number of admissions.
**Q12**: Show all the columns from admissions where the patient was admitted and discharged on the same day.
**Q13**: Show the patient id and the total number of admissions for patient_id 579.
**Q14**: Based on the cities that our patients live in, show unique cities that are in province_id 'NS'.
**Q15**: Write a query to find the first_name, last_name, and birth_date of patients who have a height greater than 160 and a weight greater than 70.
**Q16**: Write a query to find a list of patients' first_name, last_name, and allergies where allergies are not null and are from the city of 'Hamilton'.
