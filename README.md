# D206 Performance Assessment
Jose Aldana
Dr. Keiona Middleton

Part 1:
A:
My research question is “Is there a higher chance of readmission if the patient has anxiety?”. Anxiety itself is experienced by most if not all the population, and it can cause a multitude of other ailments. Seeing how correlated these fields would be worthwhile, since it would show if more attention is needed towards treating anxiety so that it may not be as debilitating in the future for the patient.
B:
I will be using the Medical Data set, and these are the variables associated with that data.:
-	CaseOrder
-Data Type: Qualitative
o	Description:A unique number that is used to find each case.
o	Example: 1
•	Customer_id	
o	Data Type: Qualitative
o	Description: A unique number that is used to identify each individual customer
o	Example: Z919181
•	Interaction
o	Data Type: Qualitative
o	Description: Another unique ID used to track each distinct interaction with the hospital.
o	Example: a2057123-abf5-4a2c-abad-8ffe33512562
•	UID
o	Data Type: Qualitative
o	Description: Like Interaction, used as a unique identifier for each unique interaction.
o	Example: e8e016144bfbe14974752d834f530e26
•	City
o	Data Type:  Qualitative
o	Description: The city of residence for the patient.
o	Example: Thompson
•	State
o	Data Type: Qualitative
o	Description: The abbreviated state of residence for the patient.
o	Example: NY
•	County
o	Data Type: Qualitative
o	Description: The County of residence for the patient.
o	Example: Jackson
•	Zip
o	Data Type: Qualitative
o	Description: The Zip code of for each patient.
o	Example: 72760
•	Lat
o	Data Type: Quantitative
o	Description: The GPS Coordinates for the patient.
o	Example: 43.54321
•	Lng
o	Data Type: Quantitative
o	Description: The GPS Coordinates for the patient.
o	Example: -96.63772
•	Population
o	Data Type: Quantitative
o	Description: The population within one mile of the patient.
o	Example: 2951
•	Area
o	Data Type: Qualitative
o	Description: The type of area the patient lives in
o	Example: Suburban
•	Timezone	
o	Data Type: Qualitative
o	Description: The time zone of residence for the patient.
o	Example: America/Detroit
•	Job
o	Data Type: Qualitative
o	Description: The patients employment.
o	Example: Actuary
•	Children
o	Data Type: Quantitative
o	Description: How many children in the patient’s household.
o	Example: 1
•	Age
o	Data Type: Quantitative
o	Description: The patients age.
o	Example: 50
•	Education
o	Data Type: Qualitative
o	Description: Level of education completed by patient
o	Example: Some College	
•	Employment
o	Data Type: Qualitative
o	Description: Type of employment the patient has.
o	Example: Part Time
•	Income
o	Data Type: Quantitative
o	Description: The yearly income for the patient or the primary insurance holder.
o	Example: 401.86
•	Marital
o	Data Type: Qualitative
o	Description: Marital Status of the patient.
o	Example: Single
•	Gender
o	Data Type: Qualitative
o	Description: The patient’s self-identified gender.
o	Example: Male
•	ReAdmis
o	Data Type: Qualitative
o	Description: Whether the patient was readmitted within a month of their hospital visit.
o	Example: Yes
•	VitD_levels
o	Data Type: Quantitative
o	Description: The patients vitamin d levels.
o	Example: 20.425926
•	Doc_visits
o	Data Type: Quantitative
o	Description: How many times the primary doctor visited the patient on their initial visit.
o	Example: 4
•	Full_meals_eaten
o	Data Type: Quantitative
o	Description: The number of full meals the patient ate on their initial visit.
o	Example: 2
•	VitD_supp
o	Data Type: Quantitative
o	Description: The number of times a patient received Vitamin D supplements
o	Example: 1
•	Soft_drink
o	Data Type: Qualitative
o	Description: Whether the patient has three or more soft drinks a day
o	Example: Yes
•	Initial_admin
o	Data Type: Qualitative
o	Description: How was the patient admitted as?
o	Example: Emergency Admission.
•	HighBlood
o	Data Type: Qualitative
o	Description: Whether the patient has high blood pressure
o	Example: Yes
•	Stroke	
o	Data Type: Qualitative
o	Description: Has the patient had a stroke in the past?
o	Example: Yes
•	Complication_risk
o	Data Type: Qualitative
o	Description: The level of complication that a patient is categorized as.
o	Example: High
•	Overweight
o	Data Type: Qualitative
o	Description: Is the patient Overweight?
o	Example: Yes
•	Arthritis
o	Data Type: Qualitative
o	Description: Does the patient have arthritis?
o	Example: No
•	Diabetes
o	Data Type: Qualitative
o	Description: Does the patient have Diabetes?
o	Example: Yes
•	Hyperlipidemia
o	Data Type: Qualitative
o	Description: Does the patient have Hyperlipidemia?
o	Example: Yes
•	BackPain
o	Data Type: Qualitative
o	Description: Does the patient have chronic back pain?
o	Example: Yes
•	Anxiety
o	Data Type: Qualitative
o	Description: Does the patient have chronic Anxiety?
o	Example: Yes
•	Allergic_rhinitis
o	Data Type: Qualitative
o	Description: Does the patient have allergic rhinitis?
o	Example: Yes
•	Reflux_esophagitis
o	Data Type: Qualitative
o	Description: Does the patient have reflux esophagitis?
o	Example: Yes
•	Asthma
o	Data Type: Qualitative
o	Description: Does the patient have asthma?
o	Example: Yes
•	Services
o	Data Type: Qualitative
o	Description: The services that the patient received on their initial visit.
o	Example: Bloodwork
•	Initial_days
o	Data Type: Quantitative
o	Description: The number of days the patient spent in the hospital during the 
o	Example: 7.0750833
•	TotalCharge
o	Data Type: Quantitative
o	Description: The average amount the patient was charged per day during their initial visit.
o	Example: 4214.90535
•	Additional_charges
o	Data Type: Quantitative
o	Description: The average amount charged per day on any additional resources such as medication or sedation.
o	Example: 17505.1925
•	Item1
o	Data Type: Qualitative
o	Description: The satisfaction the patient had in regard to timely admission, on a scale of one to eight.
o	Example: 1
•	Item2
o	Data Type: Qualitative
o	Description: The satisfaction the patient had in regard to timely treatment, on a scale of one to eight.
o	Example: 2
•	Item3
o	Data Type: Qualitative
o	Description: The satisfaction the patient had when it comes to how timely their visit was, on a scale of one to eight.
o	Example: 3
•	Item4
o	Data Type: Qualitative
o	Description: How reliable the patient felt they felt with their physician, on a scale of one to eight.
o	Example: 4
•	Item5
o	Data Type: Qualitative
o	Description: How satisfied the patient was with the care options they were provided, on a scale of one to eight.
o	Example: 5
•	Item6
o	Data Type: Qualitative
o	Description: How satisfied the patient was with their hours of treatment, on a scale of one to eight.
o	Example: 6
•	Item7
o	Data Type: Qualitative
o	Description: How courteous the staff was to the patient, on a scale of one to eight.
o	Example: 7
•	Item8
o	Data Type: Qualitative
o	Description: How satisfied the patient was with how actively the doctor listened to their issues, on a scale of one to eight.
o	Example: 8

C
1.	Methods for dealing with data quality issues: Firstly, importing the CSV file and installing the pandas library using ‘import pandas as pd” will allow me to use the correct methods for data quality issues:
a.	Using the data dictionary, as well as a general view of the data using the .info() , I am able to find any variables that may stand out. Such as misspellings or obviously incorrect inputs.
b.	I will be using the isnull(), coupled with the sum() function, in order to count the number of null or blank entries.
c.	In order to find and remove duplicates, I will be using the .duplicated(), value_counts() and drop_duplicates functions in conjunction in order to find, count and remove any duplicates that would skew the results.
d.	Using tools such as histograms and box plots, I can find any outliers that might significantly alter the results of the data.
e.	Using the mean, median and mode of the field, I can impute any missing data, or if the data is not needed, I am able to remove it altogether.
f.	In order to re-express categorical variables, I will use the vslue_counts() function, as well as the replace() function in order to replace the current values with a more appropriate term or value.
2.	Why I use those Methods:
a.	Using the .info() function will give me a general understanding of the data, as well as the data types for each field.  This can show me any blank data, as well as any data types that may not be the most effective for that field, such as an object data type, when it should be an integer.
b.	Counting the blank/ null entries will allow me to impute the data so that it may be more usable for any visualizations or PCA analysis.
c.	Using the the duplicated(), value_counts() and drop_duplicates functions lets me view the exact number of duplicates, and allows me to remove them immediately.
d.	Using visualization tools will allow me to immediately notice any outliers that need further investigation.
e.	While not completely accurate, using the mean, median or mode in order to impute allows me to use an approximate but useful dataset.  If I feel that too many fields are being imputed, I can also elect to leave the data as it is or impute a default value.
f.	I chose to use the value_counts() function to look for any categorial values that might need re-expression since it allows me to view if there are any incorrectly input entries while displaying the data type.  I can then use the replace() function to create a dictionary that will more accurately allow me to categorize a field, such as giving a value to a term in order to calculate any outliers.
3.	Programming Language Used:
a.	I elected to use the python programming language, since I have had some experience with the language in previous projects/ classes.  Python is also home to many libraries that can be used for different
