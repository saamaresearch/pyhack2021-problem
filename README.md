# pyhack2021-problem 

Clinical Trials data are captured in Forms, there are two such forms Adverse Event (AE) and Concomitant Medication (CM). Adverse Event data is captured when the Subject aka Patient is enrolled in a Clinical Trial faces a side effect. To treat the Adverse Event a medication is given, that is Concommitant Medication(CM). Adverse Events and Concommitant Medications have to be linked together. Two Datasets AE and CM are provided, see CSV files for sample data. To pull the entire data refer to the API guide. Goal of this Hackathon is to find issues with this data. 

## Datasets

AE (add link)
AE Data Dictionary (add link)
CM (add link)
CM Data Dictionary (add link)
...

## Problems

Common Problems seen in this dataset are 

### TYPE1
Patients and rows for which Concomitant Medication starts prior to the Adverse Event.

### TYPE2
Patients and rows for which Concomitant Medication days Adverse Event days dont match 

### TYPE3
Duplicate Adverse events are entered or Adverse Events overlaps 

### TYPE4
Patients and rows which have Concomitant medication overlaps

### TYPE5
Patients for which Adverse event duration is not appropriate for corresponding concomitant medication 


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
