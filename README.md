# CS4618 Assignment, 2023

## Dataset
dataset_reoffending.csv. is a CSV file, containing about 26,000 rows. Each row contains one person's details. It is a quite clean dataset. 

## Task
In the Jupyter Notebook called ai1.ipynb, I explore the dataset and construct and evaluate classifiers. These will predict whether the person will reoffend within 3 years, or not.

## Appendix

### General features

| Feature               | Description                                    |
|-----------------------|------------------------------------------------|
| id                    | Unique person identifier                       |
| gender                | M or F                                         |
| race                  | Black or White                                 |
| age                   | Age at time of release from prison              |
| address               | Code (1-25) designating the part of the US state given as address at release |
| gang_affiliated       | Affiliation to a gang                          |
| risk_score            | Risk of reoffending (1-10, where 1=lowest risk) |
| supervision_level     | Level of supervision assigned for the parole period |
| education_level       | Education level at time of entry to prison     |
| dependents            | Number of dependents at time of entry to prison |
| offence               | Primary offence that resulted in incarceration |
| years_in_prison       | Years in prison prior to release               |

### Criminal history features

| Feature                          | Description                                    |
|----------------------------------|------------------------------------------------|
| felony_arrests                   | Number of felony arrests                       |
| misdemeanor_arrests               | Number of misdemeanor arrests                   |
| violence_arrests                  | Number of violence-related arrests              |
| property_arrests                  | Number of property-related arrests              |
| drug_arrests                      | Number of drug-related arrests                  |
| parole_violation_arrests         | Number of parole violation-related arrests     |
| domestic_violence_arrests         | Number of domestic violence-related arrests     |
| gun_arrests                       | Number of gun-related arrests                   |
| felony_convictions                | Number of felony convictions                   |
| misdemeanor_convictions            | Number of misdemeanor convictions               |
| violence_convictions               | Number of violence-related convictions          |
| property_convictions               | Number of property-related convictions          |
| drug_convictions                   | Number of drug-related convictions              |
| parole_violation_convictions      | Number of parole violation-related convictions |
| domestic_violence_convictions      | Number of domestic violence-related convictions |
| gun_convictions                    | Number of gun-related convictions               |
| parole_revocations                | Number of parole revocations                   |
| probation_revocations              | Number of probation revocations                 |

### Parole conditions and violations

| Feature                          | Description                                    |
|----------------------------------|------------------------------------------------|
| mh_sa_programme                  | Enrolment on a mental health or substance abuse programme |
| cs_programme                      | Enrolment on a cognitive skills programme        |
| other_condition                   | Other, including no electronic monitoring, enrolment on a sex offender programme, or no victim contact |
| electronic_monitoring_violations  | Number of electronic monitoring violations      |
| instruction_following_violations  | Number of instruction following violations      |
| failure_to_report_violations      | Number of failure to report violations           |
| moving_without_permission_violations | Number of violations for moving without permission |
| num_delinquency_reports           | Number of delinquency reports                   |
| num_program_attendances           | Number of program attendances                   |
| num_unexcused_absences            | Number of unexcused absences                    |
| num_residence_changes             | Number of residence changes                     |
| days_between_drug_tests           | Average number of days between drug tests while on parole |
| marijuana_positive_tests          | Proportion of drug tests positive for marijuana |
| cocaine_positive_tests            | Proportion of drug tests positive for cocaine   |
| meth_positive_tests               | Proportion of drug tests positive for methamphetamine |
| other_positive_tests              | Proportion of drug tests positive for other drugs |
| days_employed                     | Proportion of days employed while on parole     |
| jobs_per_year                     | Average number of jobs per year while on parole  |
| employment_exempt                 | Employment is not required                      |

### Reoffending (different target values)

| Feature                          | Description                                    |
|----------------------------------|------------------------------------------------|
| reoffended_within_3_years        | Whether the person reoffended within 3 years of the start of parole |
| reoffended_in_year_1             | Whether the person reoffended in year 1         |
| reoffended_in_year_2             | Whether the person reoffended in year 2         |
| reoffended_in_year_3             | Whether the person reoffended in year 3         |

