# absenteeism-prediction

Data source: https://www.kaggle.com/kewagbln/absenteeism-at-work-uci-ml-repositiory

**Background information**
- Absenteeism is any failure to report for or remain at work as scheduled, regardless of the reason (Cascio & Boudreau, 2015). Absenteeism is one of the key factor determining the productivity of company. Absenteeism can have a severe impact on the workplace. The Center for Disease Control and Prevention (CDC) reports that absenteeism in the U.S. costs employers $225.8 billion annually in productivity losses. This is $1.685 per employee. In case of disease, having a prediction based on employee data could prevent absenteeism by giving a solution to its health problems.

**Problems** 
- as a company with tight financial. The company wants to provide health-mental wellness program and health examination program for employees that TENDS to absent. But it is hard for the company to indentify which employees that needs to be treated in the program

**Goals**
- Identifying the employee that TENDS to absent
- find the factors based on the data that affecting the healthiness of employee
- the manager is ready enough to handle if their employee are tends go absent


**Attribute information**
1. Individual identification (ID)
2. Reason for absence (ICD).
Absences attested by the International Code of Diseases (ICD) stratified into 21 categories (I to XXI) as follows:

I Certain infectious and parasitic diseases  
II Neoplasms  
III Diseases of the blood and blood-forming organs and certain disorders involving the immune mechanism  
IV Endocrine, nutritional and metabolic diseases  
V Mental and behavioural disorders  
VI Diseases of the nervous system  
VII Diseases of the eye and adnexa  
VIII Diseases of the ear and mastoid process  
IX Diseases of the circulatory system  
X Diseases of the respiratory system  
XI Diseases of the digestive system  
XII Diseases of the skin and subcutaneous tissue  
XIII Diseases of the musculoskeletal system and connective tissue  
XIV Diseases of the genitourinary system  
XV Pregnancy, childbirth and the puerperium  
XVI Certain conditions originating in the perinatal period  
XVII Congenital malformations, deformations and chromosomal abnormalities  
XVIII Symptoms, signs and abnormal clinical and laboratory findings, not elsewhere classified  
XIX Injury, poisoning and certain other consequences of external causes  
XX External causes of morbidity and mortality  
XXI Factors influencing health status and contact with health services.

And 7 categories without (CID) patient follow-up (22), medical consultation (23), blood donation (24), laboratory examination (25), unjustified absence (26), physiotherapy (27), dental consultation (28).
- Month of absence
- Day of the week (Monday (2), Tuesday (3), Wednesday (4), Thursday (5), Friday (6))
- Seasons
- Transportation expense
- Distance from Residence to Work (kilometers)
- Service time
- Age
- Work load Average/day 
- Hit target
- Disciplinary failure (yes=1; no=0)
- Education (high school (1), graduate (2), postgraduate (3), master and doctor (4))
- Son (number of children)
- Social drinker (yes=1; no=0)
- Social smoker (yes=1; no=0)
- Pet (number of pet)
- Weight
- Height
- Body mass index
- Absenteeism time in hours (target)
