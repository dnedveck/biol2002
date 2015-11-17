---
layout: page
title: Datasets
permalink: /datasets/
---

There's going to be more information on the datasets eventually ...

These datasets can be found in `???/shared/???`

They are all 16S data, so you will only be able to answer questions based on measures of species diversity. 

### JMMP -- Japanese Macaque gut microbiota

- Season
- anthelmintic treatment
- age
- rank
- weight

Here's the variables in the mapping file:

	 [1] "#SampleID"       "Collection_Date" "Year"            "Season"         
	 [5] "Individual"      "Weight"          "Treatment"       "Period"         
	 [9] "Matriline"       "DomRank"         "DomClass3"       "DomClass2"      
	[13] "Age"             "lbm"             "hbm"             "abm"            
	[17] "treated_start"   "drug"            "reproductive"    "repr_state"     
	[21] "oes"             "strep"           "strong"          "trich"  


### Forensic -- skin and keyboard microbiome

Here's the variables in the mapping file:

	[1] "#SampleID"             "BarcodeSequence"       "LinkerPrimerSequence" 
	[4] "COLLECTION_DATE"       "COMMON_NAME"           "Description_duplicate"
	[7] "host_subject_id"       "side_of_body"          "Description"

### Cancer

- bacteria directly adjacent to the tumor and then a sample from the healthy spot in the same individual
- all 16S data

Here's the variables in the mapping file: 

	 [1] "#SampleID"            "BarcodeSequence"      "LinkerPrimerSequence"
	 [4] "Description"          "Patient_Blind_ID"     "Age"                 
	 [7] "Sex"                  "Ethnicity"            "Site"                
	[10] "MSI_status"           "Stage"                "Height_cm"           
	[13] "Weight_kg"            "BMI" 

-------------------------------------------


### AMP -- Rural African Human Gut Microbiota

Different categories are:

- sex
- age
- BMI
- location
- diet
- ancestry
- parasitism level

### UGHP -- gut microbiota from HIV infected individuals

- parasitism
- CD4 level
- ARV therapy (antiviral therapy duration)

### Yatsunenko -- human gut microbiota

[we read a paper on this](http://www.nature.com/nature/journal/v486/n7402/abs/nature11053.html)

- country
- age
- sex
- family

