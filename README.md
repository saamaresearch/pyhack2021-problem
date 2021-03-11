# pyhack2021-problem 

Data from Clinical Trials are collected by the means of various Forms. For example, in this Hackathon, we have the Adverse Event (AE) and Concomitant Medication (CM) Forms and their respective information collected. The Adverse Event (AE) Form captures all the adverse side effects the Patient or Subject may face during a Clinical Trial after enrollment. These effects can then be treated by a medication, called Concomitant Medication and the related data is again captured as a Concomitant Medication (CM) Form. Hence we can see that both Adverse Effects (AE) and Concomitant Medications (CM) are interrelated. Here, we will provide two datasets, each of AE and CM Forms respectively as CSV files. Using this sample data, APIs must be called after referring to the API guide and the goal of this Hackathon is to find specific issues with this data.


## Datasets

AE (add link)
AE Data Dictionary (add link)
CM (add link)
CM Data Dictionary (add link)
...

## Problems

Common Problems seen in this dataset are 

### TYPE1
Patients and rows for which Medication are given prior to the Adverse Events.

### TYPE2
Patients and rows for which days Medications are given and Adverse Event occur don't match. 

### TYPE3
Duplicate Adverse events are entered or Adverse Events overlap.

### TYPE4
Patients and rows which have overlapping of Concomitant medications.

### TYPE5
Patients for which the duration of Adverse Events is not adding up to corresponding concomitant medication. 


...

## Solution 

Expected solution will do the below 

## Solution steps
### 1. Get a list subjects for study id + domain id
### 2. Get data for for study id + domain id + subject id
### 3. Process data
### 4. Get a list subjects for given study id and domain id

## APIs

### 1. Get a list subjects for study id + domain id
### 2. Get data for for study id + domain id + subject id
### 3. Get a list subjects for given study id and domain id

API Host: https://pyhack-dot-pharmanlp-177020.uc.r.appspot.com

API Docs: https://pyhack-dot-pharmanlp-177020.uc.r.appspot.com/apidocs
