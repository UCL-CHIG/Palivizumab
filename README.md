# Palivizumab

## Background
Palivizumab is a monoclonal antibody which can prevent infection with respiratory syncytial virus (RSV). Due to its high cost, it is recommended for high-risk infants only. Eligibility criteria in the UK are listed in 27a of the Green Book:  https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/458469/Green_Book_Chapter_27a_v2_0W.PDF

## Project aims:
We developed a cohort of children eligible for palivizumab (according to the criteria from the Green Book) to describe access to palivizumab in eligible children in England. More details on cohort derivation and validation will be published in:

Zylbersztejn A, De Stavola B, Smyth R, Standing JF, Tompsett D, Hardelid P. Access to palivizumab among children at high risk of respiratory syncytial virus complications in English hospitals. XXXXX (2021). DOI: 

## Repository description:
This repository covers methods for developing a cohort of children eligible for palivizumab treatment in Hospital Treatment Insights database:
- Script 0) covers code for indicating birth records in HTI database	
- Script 1) covers code for cleaning of hospital admissions in HES
- Script 2) covers code for indicating eligible conditions for palivizumab treatment
- Script 3) covers code for cleaning  HES outpatient records
- Script 4) uses HES inpatient and outpatient records to derive the most likely hospital of care
- Script 5) covers code for cleaning data on palivizumab prescribing from HTI database, outpatient records and inpatient records and derive one row per child per season
- Script 6) covers code of deriving the final cohort
- BW GA centiles do-file replaces implausible combinations of birth weight and gestational age as missing. 

See the appendix of Zylbersztejn et al. (2021) for more detailed description of steps described in each do-file.


## Data:
We used the Hospital Treatment Insights (HTI) database, which links pharmacy dispensing records for 43/152 hospitals in England and patient’s hospital records from Hospital Episode Statistics (HES). HTI is maintained by IQVIA (https://www.iqvia.com/). 

## Software
This code was developed using R.

## Authors
Ania Zylbersztejn - [github](https://github.com/AniaZylb) [twitter](https://twitter.com/zylberek)

## Acknowledgments:
Matthew Jay -   [twitter](https://twitter.com/mattjayresearch)


