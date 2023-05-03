# Individualized-Student-Instruction-Principal-Component-and-Regression-Analyses

This repository contains the code from a study analyzing data from the Individualized Student Instruction intervention. Specifically, the coded uploaded to this repository is for a principal componenet analysis and subsequent regression analysis using a machine learning model. 

R code for the PCA/Regression analyses of ISI Data (ISI_data_reducted.csv)is found in ISI_PCA_ML_code.Rmd. An html file containing all output is found in ISI_PCA_ML_code.html. These files can be downloaded by visiting the links above and clicking "download raw data".

Variables (ISI_data_reducted.csv) explained: 
* WJ_AK_Total_w1: Outcome Variable. Continuous variable of WJ III Academic Knowledge (measures science, social studies, humanities knowledge)
* WJ_PC_Total_w1: Continuous variable of WJ III Passage Comprehension scores (measures print comprehension)
* WJ_PV_Total_w1: Continuous variable of WJ III Picture Vocabulary scores (measures student word knowledge)
* WJ_LW_Total_w1: Continuous variable of WJ III Letter Word Identification scores (measures reading decoding)
* WJ_WA_Total_w1: Continuous variable of WJ III Word Attack Scores (measures decoding and phonetic coding)
* KBIT_Total_Matrices: Continuous variable of KBIT Matrices scores (measures nonverbal intelligence like problem solving)
* KBIT_Total_Riddles: Continuous variable of KBIT riddles scores (measures comprehension and reasoning)
* KBIT_Total_Verbal: Continuous variable of KBIT verbal scores (measures verbal intellectual abilities)
* CTOPP Blend: Continuous variable of CTOPP Blend (measures the ability to synthesize sounds to form words)
* CTOPP EL: Continuous variable of CTOPP Elision (measures the ability to remove phonological segments from spoken words to form other words)
* Race: Categorical variable indicating race (1 = American Indian/Alaskan Native, 2 = Asian, 3 = AA/Black, 4 = Hawaiian/Pacific Islander, 5 = Caucasian/White, 6 = Multiracial, 7 = Other).
* Ethnicity: Dichotomous variable indicating gender(0= not hispanic, 1=hispanic).
* Gender: Dichotomous variable indicating gender (0=female, 1=male).
* FARL: Dichotomous variable indicating free and reduced price (0= no, 1= FARL).
* LEP: Dichotomous variable indicating Limited english proficiency (0= no, 1= LEP).
* Treatment: treatment group (0=control, 1=treatment).
* sID: school ID

The data used in the present analysis is apart of a larger dataset composed of 9 RCTS all measuring Individualized Student Instruction. The full dataset and metadata can be found on LDBASE (https://ldbase.org/projects/8d19cbff-baf2-443a-b4ab-c16f7f2f40a4). Additionally, I've linked a manuscript that synthesizes information on all datasets/projects apart of Project KIDS  (https://openpsychologydata.metajnl.com/articles/10.5334/jopd.58). 
