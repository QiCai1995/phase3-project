# Terry Stop Arrest Predictor
!(https://images.unsplash.com/photo-1625449281218-cbb6183f0aec?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1170&q=80)


# Project Overview

## Key Business Problem

Build a classifier to predict whether an arrest was made after a Terry Stop, given information about the presence of weapons, the time of day of the call, etc. This is a binary classification problem.

## Stackholder

Civil rights organizations: people who work to protect civil liberties and ensure fair treatment of individuals by law enforcement. They can use this classifier’s predictions to highlight potential biases or disproportionate targeting during the Terry Stops.

Law enforcement agencies: police departments, law enforcement agencies, particularly street crime units, narcotics units that are responsible for conducting Terry Stops. They could use the predictions to evaluate the effectiveness of their practices and identify areas for improvement in terms of increasing successful arrests or reducing false positives.

The general public: Anyone who is interested in civil rights and law enforcement practcies. It could contribute to public discourse on policing methods and their impact on communities.

Data Scientists who are interested in working in law enforcement agencies.



## Data Understanding and Analysis
Overall goal is to come up with a binary classification model solution and to provide the top 2 features in this model.


## Source of data
[Terry Stops City of Seattle Open Data Portal](https://data.seattle.gov/Public-Safety/Terry-Stops/28ny-9ts8)
Description of Data:
This data represents records of police reported stops under Terry v. Ohio, 392 U.S. 1 (1968). Each row represents a unique stop.
Each record contains perceived demographics of the subject, as reported by the officer making the stop and officer demographics as reported to the Seattle Police Department, for employment purposes.


## Visualizations (the same visualizations presented in the slides and notebook)
![Stop Resolution](https://imgur.com/QIHetka)
![On-Site Physical Arrest Rate](https://imgur.com/Tu4UAPa)
![Logistic Regression Confusion Matrix](https://imgur.com/1rhuJUi)
![Logistic Regression ROC Graph](https://imgur.com/90tgyrj)
![Decision Tree Confusion Matrix](https://imgur.com/666nZyR)
![Decision Tree ROC Graph](https://imgur.com/uADJwfg)



## Conclusion
Decision Tree Classifier Model has the best performance to predict the arrest rate after a Terry stop. It yields a F1 score of 0.89.

The top features in this model are arrest flag and frisk flag.
