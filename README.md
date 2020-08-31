# Monkeys_database

I worked in this project during Ironhack bootcamp (week 5).

##### Dataset
The initial datasets are from Zenodo (https://zenodo.org/record/3839032#.X00Wii1Pjq1).There are 7 datasets, each one describing one specific information (diet, locomotion...).It was a huge work of assembling and cleaning datasets about monkeys. 

Steps :
- deleting non relevant (or too detailed) columns
- assembling the datasets by names & species
- handling weird values
- handling missing values

To handle the missing values, I tried as much as possible to get the right information and to add it into the dataframe.

##### Objective
The objective here is to understand which factors (biological, physical, or behavioural) influence the lenghth of the homerange. 

To answer this question, I build an OLS model (R2=0.635) highlighting that the weight of the monkeys, their diet, and their means of locomotion have a great influence. 
