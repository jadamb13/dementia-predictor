## Dementia Prediction Model (Logistic Regression)
This dementia prediction model was developed as a prototype for a project proposal to integrate 
a data product into existing CRM software used by primary care provider (PCP) clients. The goal 
of the project was to address a business need using machine learning and present the project proposal, 
prototype, and post-implementation report for a CS Capstone project. 

### Purpose and Overview

>#### Problem Statement
>Currently, two-thirds of all dementia and 91% of early dementia is missed in the primary care setting. 
>(Parmar et al., 2014) Research indicates this is due to many factors — some of which included time constraints 
>during PCP evaluations, lack of training and knowledge about dementia, and low physician confidence in identifying 
>symptoms of dementia. Current diagnosis typically requires referral to a specialist for additional costly, 
>invasive, or stigmatized testing and further delays diagnosis. 

>#### Proposed Solution and Impact 
>The logistic regression ML model was developed to automate dementia pre-screening to assist physicians with 
>decision-making, allocation of resources, and to target treatment and further evaluation to those most at risk. 
>With the insight to focus attention and evaluations, diagnosis rates at the PCP level will increase — reducing 
>the need for specialist referrals and additional testing, and improving early diagnosis rates so patients can 
>receive treatment and prepare for the future. 

>#### Dataset  
>The model was trained using the following dataset from Kaggle.com: https://www.kaggle.com/datasets/kaggler2412/dementia-patient-health-and-prescriptions-dataset 
>It has a 9.42/10 usability rating and was provided with an Apache 2.0 license. 
>
>For the goals and scope of this project, some features were not used in model training — such as `MRI_Delay` and 
>presence of the `APOE_ε4` gene variant associated with dementia — as they could only be obtained with additional 
>specialist testing. Comments on other omitted features are provided in the Dementia_Predictor jupyter notebook. 

### Project Structure


### Sources

Parmar, J., Dobbs, B., McKay, R., Kirwan, C., Cooper, T., Marin, A., & Gupta, N. (2014, May 1). Diagnosis and 
management of dementia in primary care. PubMed Central (PMC). Retrieved June 24, 2024, 
from https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4020652/