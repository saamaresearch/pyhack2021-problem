# pyhack2021

## Context
At Saama we work with pharmaceutical compaines to speed up their clinical Trials.
Clinical Trials - For a drug/medicine to get to the market it has to go through certain phases of testing on humans. These trials are done in hospitals(sites) and medicines are administered to selected patients(subjects) by the doctors.

During the trial there can be [Adverse events](https://en.wikipedia.org/wiki/Adverse_event) (a situation when the subject has side effects because of the drug under investigation).

Concomitant medications (CM) are other prescription medications study participant takes because of an Adverse Event.

For Example: Loperamide (Medication) taken for Diarrhea (Adverse event). As it happens usually, The Medication is typically taken only during the Adverse event 

## Problem summary


Data from Clinical Trials are collected by the means of various Forms. For example, in this Hackathon, we have the Adverse Event (AE) and Concomitant Medication (CM) Forms and their respective information collected. The Adverse Event (AE) Form captures all the adverse side effects the Patient or Subject may face during a Clinical Trial after enrollment. These effects can then be treated by a medication, called Concomitant Medication and the related data is again captured as a Concomitant Medication (CM) Form. Hence we can see that both Adverse Events (AE) and Concomitant Medications (CM) are interrelated. Here, we will provide two  datasets, each of AE and CM Forms samples as CSV files, to access full dataset use the APIs. APIs must be called after referring to the API guide and the goal of this Hackathon is to find specific issues with this data.


## Datasets

#### [Sample AE](https://www.dropbox.com/s/wg3xi7f9kxr5o4w/AE_data_sample.xlsx?dl=0)
#### [Sample CM](https://www.dropbox.com/s/uar0h8pkfxtt2ij/cm_data_sample.xlsx?dl=0)

#### [Data Dictionary](https://www.dropbox.com/s/5s83sveiovzolsh/Hackathon%20Data%20Dictionary.xlsx?dl=0)
...

## Problems

Common Problems(discrepancies) seen in this dataset are 

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

### API Host

https://pyhack-dot-pharmanlp-177020.uc.r.appspot.com

### API Docs: https://pyhack-dot-pharmanlp-177020.uc.r.appspot.com/apidocs

## Solution 

Use the API's provided in the API docs to perform the following 

## Solution steps
### 1. Get a list subjects for the given study id + domain id
### 2. Get subject data for study id + domain id + subject id
### 3. Process data and find discrepancy
### 4. Send discrepancy data to submit query API. ( use your email address to submit the discrepancies)

## Bonus Points

### Well written Test Harness for testing your code


