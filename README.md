# Vaccination_Coverage_Children_US_StatisticalAnalysis
##Statistical Analysis of Childhood Vaccination Coverage in the United States
Project Overview
This project investigates the association between social determinants of health and childhood vaccination coverage using longitudinal National Immunization Survey-Child (NIS-Child) data (2010-2023) from the CDC across the United States. The analysis identifies disparities in vaccination coverage that may inform targeted policy interventions to address immunization gaps.
Research Team

###Ramya Keerthi Majji¹
###Felix Pabon Rodriguez¹²*
###Yan Zhuang¹

¹Luddy School of Informatics, Computing, and Engineering
²Indiana University School of Medicine
*Corresponding author
##Key Findings

1. Survey-weighted logistic regression on the 7-vaccine series revealed socioeconomic factors are significantly associated with vaccination coverage
2. School mandates and increased disease exposure drive positive association with vaccination coverage
3. Hispanic children show lower influenza (Flu) vaccination rates linked to reduced healthcare access and cultural/systemic mistrust
4. Socioeconomic barriers including household size, insurance status, income, and education create systemic obstacles limiting family healthcare resources and vaccine completion
5. A bimodal pattern in income distribution exists with peaks at low-income (0.7) and higher-income (3-5) levels, suggesting persistent socioeconomic stratification
6. Provider-verified vaccination documentation decreased during the pandemic years (2020-2022), with a rise in insufficient data reporting across all age groups
7. Despite the "Hispanic Paradox", representation in the NIS-Child survey may be declining due to language accessibility issues, with English interviews becoming increasingly dominant

##Data Details

####Source: National Immunization Survey-Child (NIS-Child)
####Coverage period: 2010-2023
####Sample size: Annual samples of 15,000-16,000 participants
####Age group: Children aged 19-35 months
####Data volume: Over 200,000 entries

##Methodology

###Data Acquisition: Downloaded NIS files from CDC website
###Data Cleaning: Filtered for provider-verified records and removed incomplete entries
###Data Standardization: Harmonized data types across years and restructured column names for clarity and consistency
###Exploratory Data Analysis: Calculated coverage using CDC thresholds, examined social determinants and their distribution
###Statistical Analysis: Used survey-weighted logistic regression to identify SDOH associations

##Vaccine Coverage Analysis
The following vaccines were analyzed with their recommended doses:

DTaP/DTP/DT: 4 doses
Polio: 3 doses
MMR: 1 dose
Hib: 3-4 doses
Hepatitis B: 3 doses
Varicella: 1 dose
PCV: 4 doses
Influenza: 1 dose (seasonal)
Hepatitis A: 2 doses
Rotavirus: 2-3 doses

##Vaccination Coverage Trends (2010-2023)
Annual coverage rates showed variations with impacts from the COVID-19 pandemic:
YearCoverage20100.70820110.73820120.71520130.72920140.75020150.75820160.73820170.74220180.75720190.70520200.75720210.77220220.77020230.745
Conclusion
The analysis highlights persistent disparities in childhood vaccination coverage linked to social determinants of health. These disparities were intensified by policy shifts and real-world disruptions such as the COVID-19 pandemic. The occurrence of MMR outbreaks emphasizes the public health risks of delayed immunization, underscoring the urgent need for targeted, culturally responsive interventions and policies that promote equitable vaccine access for underserved populations.
Public Health Impact
This study estimates that childhood vaccination prevents approximately 2-3 million deaths annually (Andre et al., 2008) while offering a return of $16 saved for every $1 spent on immunization programs. Despite this success, significant coverage gaps persist in the United States, with disparities linked to social determinants of health (Burdette et al., 2011).
##Requirements
###R studio
###CDC immunization data files (NIS-Child)
###Data cleaning and harmonization tools
###Data visualization libraries

###Project Date
May 1, 2025

###Institution
Indiana University
Luddy School of Informatics, Computing, and Engineering
Department of Biomedical Engineering and Informatics
Indianapolis
