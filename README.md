# Consumer Preference in German Car Market 

## By: Will & Gaurav | 9 October 2022

### Background

We are a risk analyst for xyz Company in Berlin, Germany. We have been approached by one of the leading automotive used online car portal autoscout24 to understand the change in consumer preference while buying a used car in Germany from 2017 onwards. 

### Problem Description 

How should AutoScout24 adapt to shifting consumer preferences in German automarket?

## Research question 

**1)** Diesel less popular post-2017?
**2)** Electric cars more popular post-2017? 

### Data Set

Data from Kaggle: https://www.kaggle.com/datasets/ander289386/cars-germany was imported. It had 48,000 observations with 9 different features. 

**Year**: Respective year in which the car was sold

**Make**: Refers to the brand of the vehicle

**Model**: Refers to the specific vehicle model

**Gear**: Refers to automotive transmission (manual, automatic, etc.)

**Fuel**: Refers to different types of fuels used in a car (Diesel, Petrol, Electric)

**Offer Type**: Whether is is a new of used car

**Hp**: Refers to the power an engine produces

**Mileage**: How much kilometer the car has run before it was sold

**Price**: Price at which the car was sold

### Process

1) Exploratory Data Analysis and Visualizations using Python

2) Cleaning data (dealing with NaN values, empty values, duplicate rows, standardizing heading names, checking outliers, etc.)

3) Querying in SQL

4) Pre-processing data for modeling (X/y split, train/test split, encoding categoricals and scaling numericals)

5) Re-running model with each data balance technique and comparing their confusion matrix and metrics

6) Drawing conclusions about data from the model

7) Hypothesis testing : 

  a) For Research Q1: 
      One-sided test:
    # Null hypothesis or H0: count of diesel pre-2017 </= 845 (post)
    # Alternative hypothesis or H1: count of diesel pre-2017 > 845 (post)
    
    b) For Research Q2: 
      One-sided test:
    # Null hypothesis or H0: count of electric pre-2017 >/= 80 (post-2017)
    # Alternative hypothesis or H1: count of electric pre-2017 < 80 (post 2017)

8) Data visualizations in Tableau comparing demographics of customers who did and didn't take the offer

9) Preparation of presentation to explain findings, recommendations and future actions to be taken by the autoscout24 bank to optimise their inventory in case of shift in any consumer preference trend. 

10) 7-minute live presentation to 27 colleagues to present project and data-driven insights followed by 5-minute discussion

### Trello board to track project status: https://trello.com/b/Iffg6xj9/project-week

### Tableau Public page with visualizations: https://public.tableau.com/views/IronHack_German_Cars/GermanCarMarketShiftingConsumerPreferences?:language=en-US&:display_count=n&:origin=viz_share_link






