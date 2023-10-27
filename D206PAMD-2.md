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

## 4. Detection Code:
  - Here is the detection code, please see code attached to this submission for the journal:

```python
# Import Necessary Libraries
import numpy as np
import pandas as pd
from sklearn.preprocessing import scale 
from sklearn.decomposition import PCA
import seaborn as sns
import matplotlib.pyplot as plt
```


```python
#import csv file as df
df = pd.read_csv('/Users/josealdana/Desktop/D206_files/medical_csv/medical_raw_data.csv')
```

```python
#view of the dataframe
df
```



```python
# Import Necessary Libraries
import numpy as np
import pandas as pd
from sklearn.preprocessing import scale 
from sklearn.decomposition import PCA
import seaborn as sns
import matplotlib.pyplot as plt
```


```python
#import csv file as df
df = pd.read_csv('/Users/josealdana/Desktop/D206_files/medical_csv/medical_raw_data.csv')
```


```python
#view of the dataframe
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Unnamed: 0</th>
      <th>CaseOrder</th>
      <th>Customer_id</th>
      <th>Interaction</th>
      <th>UID</th>
      <th>City</th>
      <th>State</th>
      <th>County</th>
      <th>Zip</th>
      <th>Lat</th>
      <th>...</th>
      <th>TotalCharge</th>
      <th>Additional_charges</th>
      <th>Item1</th>
      <th>Item2</th>
      <th>Item3</th>
      <th>Item4</th>
      <th>Item5</th>
      <th>Item6</th>
      <th>Item7</th>
      <th>Item8</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>1</td>
      <td>C412403</td>
      <td>8cd49b13-f45a-4b47-a2bd-173ffa932c2f</td>
      <td>3a83ddb66e2ae73798bdf1d705dc0932</td>
      <td>Eva</td>
      <td>AL</td>
      <td>Morgan</td>
      <td>35621</td>
      <td>34.34960</td>
      <td>...</td>
      <td>3191.048774</td>
      <td>17939.403420</td>
      <td>3</td>
      <td>3</td>
      <td>2</td>
      <td>2</td>
      <td>4</td>
      <td>3</td>
      <td>3</td>
      <td>4</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2</td>
      <td>2</td>
      <td>Z919181</td>
      <td>d2450b70-0337-4406-bdbb-bc1037f1734c</td>
      <td>176354c5eef714957d486009feabf195</td>
      <td>Marianna</td>
      <td>FL</td>
      <td>Jackson</td>
      <td>32446</td>
      <td>30.84513</td>
      <td>...</td>
      <td>4214.905346</td>
      <td>17612.998120</td>
      <td>3</td>
      <td>4</td>
      <td>3</td>
      <td>4</td>
      <td>4</td>
      <td>4</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <th>2</th>
      <td>3</td>
      <td>3</td>
      <td>F995323</td>
      <td>a2057123-abf5-4a2c-abad-8ffe33512562</td>
      <td>e19a0fa00aeda885b8a436757e889bc9</td>
      <td>Sioux Falls</td>
      <td>SD</td>
      <td>Minnehaha</td>
      <td>57110</td>
      <td>43.54321</td>
      <td>...</td>
      <td>2177.586768</td>
      <td>17505.192460</td>
      <td>2</td>
      <td>4</td>
      <td>4</td>
      <td>4</td>
      <td>3</td>
      <td>4</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4</td>
      <td>4</td>
      <td>A879973</td>
      <td>1dec528d-eb34-4079-adce-0d7a40e82205</td>
      <td>cd17d7b6d152cb6f23957346d11c3f07</td>
      <td>New Richland</td>
      <td>MN</td>
      <td>Waseca</td>
      <td>56072</td>
      <td>43.89744</td>
      <td>...</td>
      <td>2465.118965</td>
      <td>12993.437350</td>
      <td>3</td>
      <td>5</td>
      <td>5</td>
      <td>3</td>
      <td>4</td>
      <td>5</td>
      <td>5</td>
      <td>5</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5</td>
      <td>5</td>
      <td>C544523</td>
      <td>5885f56b-d6da-43a3-8760-83583af94266</td>
      <td>d2f0425877b10ed6bb381f3e2579424a</td>
      <td>West Point</td>
      <td>VA</td>
      <td>King William</td>
      <td>23181</td>
      <td>37.59894</td>
      <td>...</td>
      <td>1885.655137</td>
      <td>3716.525786</td>
      <td>2</td>
      <td>1</td>
      <td>3</td>
      <td>3</td>
      <td>5</td>
      <td>3</td>
      <td>4</td>
      <td>3</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>9995</th>
      <td>9996</td>
      <td>9996</td>
      <td>B863060</td>
      <td>a25b594d-0328-486f-a9b9-0567eb0f9723</td>
      <td>39184dc28cc038871912ccc4500049e5</td>
      <td>Norlina</td>
      <td>NC</td>
      <td>Warren</td>
      <td>27563</td>
      <td>36.42886</td>
      <td>...</td>
      <td>6651.241294</td>
      <td>8927.642189</td>
      <td>3</td>
      <td>2</td>
      <td>2</td>
      <td>3</td>
      <td>4</td>
      <td>3</td>
      <td>4</td>
      <td>2</td>
    </tr>
    <tr>
      <th>9996</th>
      <td>9997</td>
      <td>9997</td>
      <td>P712040</td>
      <td>70711574-f7b1-4a17-b15f-48c54564b70f</td>
      <td>3cd124ccd43147404292e883bf9ec55c</td>
      <td>Milmay</td>
      <td>NJ</td>
      <td>Atlantic</td>
      <td>8340</td>
      <td>39.43609</td>
      <td>...</td>
      <td>7851.522660</td>
      <td>28507.147340</td>
      <td>3</td>
      <td>3</td>
      <td>4</td>
      <td>2</td>
      <td>5</td>
      <td>3</td>
      <td>4</td>
      <td>4</td>
    </tr>
    <tr>
      <th>9997</th>
      <td>9998</td>
      <td>9998</td>
      <td>R778890</td>
      <td>1d79569d-8e0f-4180-a207-d67ee4527d26</td>
      <td>41b770aeee97a5b9e7f69c906a8119d7</td>
      <td>Southside</td>
      <td>TN</td>
      <td>Montgomery</td>
      <td>37171</td>
      <td>36.36655</td>
      <td>...</td>
      <td>7725.953391</td>
      <td>15281.214660</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>4</td>
      <td>4</td>
      <td>2</td>
      <td>3</td>
      <td>2</td>
    </tr>
    <tr>
      <th>9998</th>
      <td>9999</td>
      <td>9999</td>
      <td>E344109</td>
      <td>f5a68e69-2a60-409b-a92f-ac0847b27db0</td>
      <td>2bb491ef5b1beb1fed758cc6885c167a</td>
      <td>Quinn</td>
      <td>SD</td>
      <td>Pennington</td>
      <td>57775</td>
      <td>44.10354</td>
      <td>...</td>
      <td>8462.831883</td>
      <td>7781.678412</td>
      <td>5</td>
      <td>5</td>
      <td>3</td>
      <td>4</td>
      <td>4</td>
      <td>3</td>
      <td>4</td>
      <td>3</td>
    </tr>
    <tr>
      <th>9999</th>
      <td>10000</td>
      <td>10000</td>
      <td>I569847</td>
      <td>bc482c02-f8c9-4423-99de-3db5e62a18d5</td>
      <td>95663a202338000abdf7e09311c2a8a1</td>
      <td>Coraopolis</td>
      <td>PA</td>
      <td>Allegheny</td>
      <td>15108</td>
      <td>40.49998</td>
      <td>...</td>
      <td>8700.856021</td>
      <td>11643.189930</td>
      <td>4</td>
      <td>3</td>
      <td>3</td>
      <td>2</td>
      <td>3</td>
      <td>6</td>
      <td>4</td>
      <td>3</td>
    </tr>
  </tbody>
</table>
<p>10000 rows × 53 columns</p>
</div>


