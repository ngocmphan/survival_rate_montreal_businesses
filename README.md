# survival_rate_montreal_businesses
- Discontinued project - 
## Problem statement
The topic is to explore the challenges affecting survival rate during the pandemic and financially difficult situation. The challenges include operational factors and financial support & subsidy awareness. 

## Data sources and variables
The data was collected by Ville de Montreal and represented only a sample of businesses in Montreal. The data was collected using direct calls to the businesses with follow-up calls separated by waves to update on the status. The data includes the following variables: 
* Date of the call
* Type of territory
* Borough name
* Status of the business (open or closed)
* Challenges incur relating to: financial support, maintaining operations, tax challenges, human resources, regulation, marketing challenges, health and security, sanitary equipment, space management, terrasse permit
* Presence on social media: facebook, twitter, instagram, linkedin
* If the business conduct sales online
* Awareness of urban delivery services
* If business is interested in urban delivery services
* if business is interested in digital shift
* If business is interested in urban delivery services provided by Ville de Montreal? 

## Deliverables
Factors affecting the survival rates
* If there is relationship between qualitative factors (challenges) and risk of closure using Chi-square test
* Factors/challenges that have high indication of closure. Classification methods: KNN, Logistic regression, LDA, and QDA
* If locations of the establishment have significant effects on closure rates
* if there is indication that certain factors affect the commerce more on the first wave

## Tools: 
The following Python libraries below: 
* Pandas
* Scikit-Learn
* Scipy
* Category_encoders
* WordCloud

## References
J'informe les commercants. Ville de Montreal, Économie et entreprises. Data extracted via the following link: 
https://donnees.montreal.ca/dataset/informe-commercants


