+++
date = "2015-09-01T19:34:46-04:00"
title = "PROCEDUREEVENTS_MV"
linktitle = "PROCEDUREEVENTS_MV"
weight = 32
toc = "true"

[menu]
  [menu.main]
    parent = "Tables in MIMIC"

+++


# Overview

**Table source:** Metavision ICU database.

**Table purpose:** Contains procedures for patients

**Number of rows:** TBC

Details to follow.

<!--

**Links to:**

* PATIENTS on `SUBJECT_ID`
* ADMISSIONS on `HADM_ID`
* D\_ICD\_PROCEDURES on `ICD9_CODE`

# Table columns

Name | Postgres data type 
---- | ---- 
SUBJECT\_ID | INT
HADM\_ID | INT
PROC\_SEQ\_NUM | INT
ICD9\_CODE | VARCHAR(20)
	
# Detailed Description

## `SUBJECT_ID`, `HADM_ID`

Identifiers which specify the patient: `SUBJECT_ID` is unique to a patient and `HADM_ID` is unique to a patient hospital stay.

## `PROC_SEQ_NUM`

`PROC_SEQ_NUM` provides the order in which the procedures were performed.

## `ICD9_CODE`

`CODE` provides the code for the given procedure. 

# Important considerations

* In MIMIC-III v1.0, only ICD-9 codes are used for recording procedures.

-->
