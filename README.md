# Capstone
 This Repository will be mainly used for the capstone project.

1.	Business Problem

In order to complete the IBM Applied Data Science Certificate, we want to explore the Collisions dataset, from Seattle SPOT Traffic Management Division and provided by Coursera, to evaluate which characteristics or features can be used to predict accident "severity". 
We will use machine learning and data science technics to develop a model to predict car accident "severity" in terms of human fatality. Our goal is to help Seattle residents to:

(i)	 Have a better transparency over the key accident “severity” drivers
(ii)	 Incorporate these factors in their travel decision making process
(iii)	 Act on them in order to reduce the risk of being involved in a severe accident in terms of human fatality.

2.	Data
All collisions data are provided by SPD and recorded by Traffic Records from 2004 to Present. All years Collisions dataset contains 194,673 observations samples and 38 attributes or features. The dataset includes all types of collisions (e.g. Bicycle, Car, Collisions, Pedestrian etc), accident location, collision type, number of people involved and circumstances in which the accident took place (weather conditions, road conditions, speeding, light conditions etc). 
These features and other relevant ones will be used as independent variables (X) to determine the key accident drivers and the associated severity level. In addition, the dataset includes accident severity rating code. For example, a code of 3 is assigned to accident classified as “fatal” while a code of 2 is assigned to accident with “injury”. We use the severity (SEVERITYCODE) as (Y), dependent variable or target.
There are also several missing values. We will identify these missing values and explore different methods to handle them. In addition, given the dataset size is quite substantial, they are several features that may be irrelevant for our analysis. We will identify these features by using different statistical technics and exclude them.
