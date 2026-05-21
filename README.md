# Employee Data Cleaning Project (Python)

This project focuses on cleaning a messy employee dataset using Python and Pandas.

## Dataset Columns

- Respondent_ID
- Full Name
- Age
- Gender
- City
- Monthly Salary
- Satisfaction Score
- Join Date
- Remote Worker?
- Email Address

## Project Goal

The goal of this project was to clean and standardize raw employee data to improve data quality and usability.

## Cleaning Tasks Performed

- Removed duplicate records
- Handled missing values
- Standardized text formatting
- Cleaned salary values
- Formatted dates correctly
- Corrected inconsistent gender entries
- Standardized email addresses
- Fixed inconsistent city names

## Tools Used

- Python
- Pandas
- Google Colab

## Skills Demonstrated

- Data Cleaning
- Data Transformation
- Pandas
- Handling Missing Data
- Data Formatting
- Duplicate Removal

## Example

### Before Cleaning

| Respondent ID | Full Name |	Age	| Gender |	City |	Monthly Salary	| Satisfaction Score |	Join Date |	Remote Worker? |	Email Address |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Debbie Knight |	 |	Male |	TORONTO |	55000	| Poor |	15-08-2022 |	Yes |	
| 2 | Daniel Mcgee |	25 |	F |	Toronto |	N/A |	1 |	03/15/2023 |	No |	PMASSEY@JOHNSON-SINGH.COM |
| 134 | Michael Cuevas |	45 years |	F |	Calgary |	 |	2 |	03/15/2023 |	N |	RODRIGUEZDANIELLE@DAVIDSON.INFO |


### After Cleaning
| Respondent ID | Full Name |	Age	| Gender |	City |	Monthly Salary	| Satisfaction Score |	Join Date |	Remote Worker? |	Email Address |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Debbie Knight | Unknown | Male | Toronto  | 55000 | Poor | 44788 | Yes | Unknown |
| 2 | Daniel Mcgee | 25 | Female | Toronto | Unknown | Very Poor | 45000 | No | pmassey@johnson-singh.com |
| 4 | Mrs. Brittany Hill | 34 | Female | Montreal | Unknown | Poor | 44788 | No | Unknown |


## Outcome

The final dataset was cleaned and standardized, making it ready for future analysis or reporting.
