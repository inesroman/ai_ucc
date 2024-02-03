# CS4618 Assignment, 2023

## Dataset
dataset_reoffending.csv. is a CSV file, containing about 26,000 rows. Each row contains one person's details. It is a quite clean dataset. 

## Task
In the Jupyter Notebook called ai1.ipynb, I explore the dataset and construct and evaluate classifiers. These will predict whether the person will reoffend within 3 years, or not.

## Appendix
### General features
id 				unique person identifier
gender 				M or F
race 				black or white
age 				age at time of release from prison
address 			a code (1-25) that designates the part of the US state that the person gives as their address at time of release
gang_affiliated 		whether affiliated to a gang
risk_score 			risk of reoffending (1-10, where 1=lowest risk)
supervision_level 		level of supervision assigned for the parole period
education_level 		education level at time of entry to prison
dependents 			number of dependents at time of entry to prison
offence 			primary offence that resulted in incarceration
years_in_prison 		years in prison prior to release

### Criminal history features
felony_arrests 	
misdemeanor_arrests 	
violence_arrests 	
property_arrests 	
drug_arrests 	
parole_violation_arrests 	
domestic_violence_arrests 	
gun_arrests 	
felony_convictions 	
misdemeanor_convictions 	
violence_convictions 	
property_convictions 	
drug_convictions 	
parole_violation_convictions 	
domestic_violence_convictions 	
gun_convictions 	
parole_revocations 	
probation_revocations 	

### Parole conditions and violations of conditions while on parole
mh_sa_programme 		enrolment on a mental health or substance abuse programme
cs_programme 			enrolment on a cognitive skills programme
other_condition 		other, including no electronic monitoring, enrolment on a sex offender programme or no victim contact
electronic_monitoring_violations 	
instruction_following_violations 	
failure_to_report_violations 	
moving_without_permission_violations 	
num_delinquency_reports 	
num_program_attendances 	
num_unexcused_absences 	
num_residence_changes 	
days_between_drug_tests 	average number of days between drug tests while on parole
marijuana_positive_tests 	proportion of drug tests positive for marijuana
cocaine_positive_tests 		proportion of drug tests positive for cocaine
meth_positive_tests 		proportion of drug tests positive for methamphetamine
other_positive_tests 		proportion of drug tests positive for other drugs
days_employed 			proportion of days employed while on parole
jobs_per_year 			average number of jobs per year while on parole
employment_exempt 		employment is not required

## Reoffending (different target values)
reoffended_within_3_years 	whether the person reoffended within 3 years of the start of parole
reoffended_in_year_1 		whether the person reoffended in year 1
reoffended_in_year_2 		whether the person reoffended in year 2
reoffended_in_year_3 		whether the person reoffended in year 3
