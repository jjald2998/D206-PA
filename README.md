# D206 Performance Assessment
  - Jose Aldana
  - Dr. Keiona Middleton

## Part 1

### A:

My research question is “Is there a higher chance of readmission if the patient has anxiety?”. Anxiety itself is experienced by most if not all the population, and it can cause a multitude of other ailments. Seeing how correlated these fields would be worthwhile, since it would show if more attention is needed towards treating anxiety so that it may not be as debilitating in the future for the patient.

### B:

I will be using the Medical Data set, and these are the variables associated with that data:
- CaseOrder
  - Data Type: Qualitative
  - Description: A unique number that is used to find each case.
  - Example: 1
- Customer_id	
  - Data Type: Qualitative
  - Description: A unique number that is used to identify each individual customer.
  - Example: Z919181
- Interaction
  - Data Type: Qualitative
  - Description: Another unique ID used to track each distinct interaction with the hospital.
  - Example: a2057123-abf5-4a2c-abad-8ffe33512562
- UID
  - Data Type: Qualitative
  - Description: Like Interaction, used as a unique identifier for each unique interaction.
  - Example: e8e016144bfbe14974752d834f530e26
- City
  - Data Type: Qualitative
  - Description: The city of residence for the patient.
  - Example: Thompson
- State
  - Data Type: Qualitative
  - Description: The abbreviated state of residence for the patient.
  - Example: NY
- County
  - Data Type: Qualitative
  - Description: The County of residence for the patient.
  - Example: Jackson
- Zip
  - Data Type: Qualitative
  - Description: The Zip code of for each patient.
  - Example: 72760
- Lat
  - Data Type: Quantitative
  - Description: The GPS Coordinates for the patient.
  - Example: 43.54321
- Lng
  - Data Type: Quantitative
  - Description: The GPS Coordinates for the patient.
  - Example: -96.63772
- Population
  - Data Type: Quantitative
  - Description: The population within one mile of the patient.
  - Example: 2951
- Area
  - Data Type: Qualitative
  - Description: The type of area the patient lives in.
  - Example: Suburban
- Timezone	
  - Data Type: Qualitative
  - Description: The time zone of residence for the patient.
  - Example: America/Detroit
- Job
  - Data Type: Qualitative
  - Description: The patient's employment.
  - Example: Actuary
- Children
  - Data Type: Quantitative
  - Description: How many children in the patient’s household.
  - Example: 1
- Age
  - Data Type: Quantitative
  - Description: The patient's age.
  - Example: 50
- Education
  - Data Type: Qualitative
  - Description: Level of education completed by the patient.
  - Example: Some College
- Employment
  - Data Type: Qualitative
  - Description: Type of employment the patient has.
  - Example: Part Time
- Income
  - Data Type: Quantitative
  - Description: The yearly income for the patient or the primary insurance holder.
  - Example: 401.86
- Marital
  - Data Type: Qualitative
  - Description: Marital Status of the patient.
  - Example: Single
- Gender
  - Data Type: Qualitative
  - Description: The patient's self-identified gender.
  - Example: Male
- ReAdmis
  - Data Type: Qualitative
  - Description: Whether the patient was readmitted within a month of their hospital visit.
  - Example: Yes
- VitD_levels
  - Data Type: Quantitative
  - Description: The patient's vitamin D levels.
  - Example: 20.425926
- Doc_visits
  - Data Type: Quantitative
  - Description: How many times the primary doctor visited the patient on their initial visit.
  - Example: 4
- Full_meals_eaten
  - Data Type: Quantitative
  - Description: The number of full meals the patient ate on their initial visit.
  - Example: 2
- VitD_supp
  - Data Type: Quantitative
  - Description: The number of times a patient received Vitamin D supplements.
  - Example: 1
- Soft_drink
  - Data Type: Qualitative
  - Description: Whether the patient has three or more soft drinks a day.
  - Example: Yes
- Initial_admin
  - Data Type: Qualitative
  - Description: How was the patient admitted.
  - Example: Emergency Admission
- HighBlood
  - Data Type: Qualitative
  - Description: Whether the patient has high blood pressure.
  - Example: Yes
- Stroke
  - Data Type: Qualitative
  - Description: Has the patient had a stroke in the past.
  - Example: Yes
- Complication_risk
  - Data Type: Qualitative
  - Description: The level of complication that a patient is categorized as.
  - Example: High
- Overweight
  - Data Type: Qualitative
  - Description: Is the patient overweight.
  - Example: Yes
- Arthritis
  - Data Type: Qualitative
  - Description: Does the patient have arthritis.
  - Example: No
- Diabetes
  - Data Type: Qualitative
  - Description: Does the patient have Diabetes.
  - Example: Yes
- Hyperlipidemia
  - Data Type: Qualitative
  - Description: Does the patient have Hyperlipidemia.
  - Example: Yes
- BackPain
  - Data Type: Qualitative
  - Description: Does the patient have chronic back pain.
  - Example: Yes
- Anxiety
  - Data Type: Qualitative
  - Description: Does the patient have chronic Anxiety.
  - Example: Yes
- Allergic_rhinitis
  - Data Type: Qualitative
  - Description: Does the patient have allergic rhinitis.
  - Example: Yes
- Reflux_esophagitis
  - Data Type: Qualitative
  - Description: Does the patient have reflux esophagitis.
  - Example: Yes
- Asthma
  - Data Type: Qualitative
  - Description: Does the patient have asthma.
  - Example: Yes
- Services
  - Data Type: Qualitative
  - Description: The services that the patient received on their initial visit.
  - Example: Bloodwork
- Initial_days
  - Data Type: Quantitative
  - Description: The number of days the patient spent in the hospital during the 
  - Example: 7.0750833
- TotalCharge
  - Data Type: Quantitative
  - Description: The average amount the patient was charged per day during their initial visit.
  - Example: 4214.90535
- Additional_charges
  - Data Type: Quantitative
  - Description: The average amount charged per day on any additional resources such as medication or sedation.
  - Example: 17505.1925
- Item1
  - Data Type: Qualitative
  - Description: The satisfaction the patient had in regard to timely admission, on a scale of one to eight.
  - Example: 1
- Item2
  - Data Type: Qualitative
  - Description: The satisfaction the patient had in regard to timely treatment, on a scale of one to eight.
  - Example: 2
- Item3
  - Data Type: Qualitative
  - Description: The satisfaction the patient had when it comes to how timely their visit was, on a scale of one to eight.
  - Example: 3
- Item4
  - Data Type: Qualitative
  - Description: How reliable the patient felt they felt with their physician, on a scale of one to eight.
  - Example: 4
- Item5
  - Data Type: Qualitative
  - Description: How satisfied the patient was with the care options they were provided, on a scale of one to eight.
  - Example: 5
- Item6
  - Data Type: Qualitative
  - Description: How satisfied the patient was with their hours of treatment, on a scale of one to eight.
  - Example: 6
- Item7
  - Data Type: Qualitative
  - Description: How courteous the staff was to the patient, on a scale of one to eight.
  - Example: 7
- Item8
  - Data Type: Qualitative
  - Description: How satisfied the patient was with how actively the doctor listened to their issues, on a scale of one to eight.
  - Example: 8


# C:

## 1. Methods for Dealing with Data Quality Issues
   - Firstly, importing the CSV file and installing the pandas library using `import pandas as pd` will allow me to use the correct methods for data quality issues.
     - Using the data dictionary, as well as a general view of the data using the `.info()` function, I am able to find any variables that may stand out, such as misspellings or obviously incorrect inputs.
     - I will be using the `isnull()`, coupled with the `sum()` function, in order to count the number of null or blank entries.
     - In order to find and remove duplicates, I will be using the `.duplicated()`, `value_counts()`, and `drop_duplicates` functions in conjunction in order to find, count, and remove any duplicates that would skew the results.
     - Using tools such as histograms and box plots, I can find any outliers that might significantly alter the results of the data.
     - Using the mean, median, and mode of the field, I can impute any missing data, or if the data is not needed, I am able to remove it altogether.
     - In order to re-express categorical variables, I will use the `value_counts()` function, as well as the `replace()` function in order to replace the current values with a more appropriate term or value.

## 2. Why I Use Those Methods
   - Using the `.info()` function will give me a general understanding of the data, as well as the data types for each field. This can show me any blank data, as well as any data types that may not be the most effective for that field, such as an object data type, when it should be an integer.
   - Counting the blank/null entries will allow me to impute the data so that it may be more usable for any visualizations or PCA analysis.
   - Using the `.duplicated()`, `value_counts()`, and `drop_duplicates` functions lets me view the exact number of duplicates and allows me to remove them immediately.
   - Using visualization tools will allow me to immediately notice any outliers that need further investigation.
   - While not completely accurate, using the mean, median, or mode in order to impute allows me to use an approximate but useful dataset. If I feel that too many fields are being imputed, I can also elect to leave the data as it is or impute a default value.
   - I chose to use the `value_counts()` function to look for any categorical values that might need re-expression since it allows me to view if there are any incorrectly input entries while displaying the data type. I can then use the `replace()` function to create a dictionary that will more accurately allow me to categorize a field, such as giving a value to a term in order to calculate any outliers.

## 3. Programming Language Used
  -	I elected to use the python programming language, since I have had some experience with the language in previous projects/ classes.  Python is also home to many libraries that can be used for different scenarios even outside of data analysis.  It’s easy to understand syntax also makes python my choice for this performance assessment.  in this process, I mainly used two core packages: NumPy and Pandas. NumPy supplies essential mathematical functions required for data transformation, while Pandas allows me to use a data frame, which is a spreadsheet format within python,  With built-in capabilities to manipulate and standardize data. Once the data is refined, we employ Principal Component Analysis (PCA) with Scikit-Learn's PCA module to delve into the principal components. Additionally, Seaborn assists in generating scree plots as part of the PCA analysis. Matplotlib also allows me to visualize useful data, such as using a histogram in order to find outliers.

## 4. 4.	Detection Code:
  - Here is the detection code, please see code attached to this submission for the journal:

```
#import necessary libraries
import numpy as np
import pandas as pd
from sklearn.preprocessing import scale 
from sklearn.decomposition import PCA
import seaborn as sns
import matplotlib.pyplot as plt
