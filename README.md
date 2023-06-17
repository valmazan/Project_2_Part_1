# Project 2 

## Stroke Prediction Dataset

Victoria Almazan

# Objective

### Our goal is to better help our partners understand what is most likley the highest leading causes that attriubte to strokes. We will be diving into understanding key features that will better explain such reason and how to proceed moving forward with better buiness actions.


 The Source of data was provided by Kaggle.
 
# Brief description of Dataset
 - This data set represented is based on a study on strokes being the leading cause of death globally per the World Health Organization. 
 - This data can be accessed here: https://docs.google.com/spreadsheets/d/e/2PACX('-1vRdlCBU471ijgzSbXzxQOsloENGNY4bKDRKn50EcCpq7iSCZPkk2N2l7PReD7xNiOJAK5brD5TKdK9x/pub?gid=1457616118&single=true&output=csv')


 What is the target?
 - The target of this data is to predict whether it is likley for a patient is likely to get a stroke based on the different attributes such as age, heart disease, smoking status. I will be showing a few visuals to better help undestand and what we can learn from our dataset. 
 

# For this Data, it was cleaned and prepared the data using the following processing was performed:

## Initial Insights 

- There are 5110 rows, and 12 columns.

## Explanatory Visiuals

- Figure 1, shows us a baseline of 'Male' and 'Female' participants. This helps us better understand the disparity between the two figures.  

Fig.1 

![image](https://github.com/valmazan/Project_2_Part_1/assets/126423326/c0a50c78-011b-4579-ab74-27a56836c25b)

- Figure 2, represents the amount of strokes . The number 1 if the patient had a stroke or 0 if not.

Fig. 2

![image](https://github.com/valmazan/Project_2_Part_1/assets/126423326/153f1aa6-39ed-4f8a-b26b-feb5700d40b3)


- Figure 3, shows the amount of strokes based on 'Age'. 

Fig. 3 

![image](https://github.com/valmazan/Project_2_Part_1/assets/126423326/22f95106-2ebb-4579-9ae4-e96066b5fde9)

- Figure 4, represents a count based on smoking status as this is one of our features.

Fig. 4 

![image](https://github.com/valmazan/Project_2_Part_1/assets/126423326/2f493a95-6db1-4212-8ef7-9e88fb01283a)

## Multivariate Viziualizations 

- Figure 5, represents features such as 'BMI', 'Age' and 'Gender'. 
- We can assume that the majority of the data has an average bmi of 20- 60. The majority seem to be more female than male. 

Fig. 5 

![image](https://github.com/valmazan/Project_2_Part_1/assets/126423326/f74c525d-a13d-42f7-8f71-a60e9bcb1004)

For figure 5.2, we can see a better representation of 'BMI'.

Fig. 5.2 

![image](https://github.com/valmazan/Project_2_Part_1/assets/126423326/7ecb7f7f-ff8e-4d53-b72b-1741a217e265)

Figure 6, represents smoking status including 'BMI' and 'Avg Glucose Level'.

Fig. 6

![image](https://github.com/valmazan/Project_2_Part_1/assets/126423326/3f555fd3-7e2d-4f92-b927-2811323797c6)



# ML Model Training Results

## KNN Model Evaluation

Model best score is 94%. 
![image](https://github.com/valmazan/Project_2_Part_1/assets/126423326/42e740c3-c653-4535-9265-5ec53ef7dbd0)


## KNN Model with GridSearch CV

Model improve to 95%
![image](https://github.com/valmazan/Project_2_Part_1/assets/126423326/a5dfc62e-5bb0-4117-a7aa-525b52556fce)


## Desicion Tree Classifier 

The Desicion Tree Classifier was the best model out of KNN and LogReg. 

![image](https://github.com/valmazan/Project_2_Part_1/assets/126423326/e8d2de4a-2c64-4a7f-b1f9-3c17e0e12430)

## Logistic Regression 

Modeling score 92% 

![image](https://github.com/valmazan/Project_2_Part_1/assets/126423326/9e1992b1-aad8-4bc4-aa3a-285793d7bafd)

![image](https://github.com/valmazan/Project_2_Part_1/assets/126423326/66012dcc-feea-474e-8a0d-473623cf1efb)


## Logistic Regression with GridSearch CV tuning

Modeling improved to 93%.

![image](https://github.com/valmazan/Project_2_Part_1/assets/126423326/171c4616-5f18-4220-909b-aa585b5c6093)

![image](https://github.com/valmazan/Project_2_Part_1/assets/126423326/386823b9-4fb6-44db-beaa-b2c9d870f0a0)


# Summary 

Based on all of our data, our modeling did have false negatives and false positive, but with tuning we were able to make sure that we adjusted our algoritims to be above 94% accuracy. The impacts of having false negatives and false positives means that any false information would greatly impact the overall health of patients with the recommendation of prescribing medicines and treatments that can interfere features such as heart disease, avg gluecose level, smoking status and bmi. Additionally taking into account other features such as gender and age help us better understand the stroke attributes. 

# Recommendation 

 - My recommendations are to continue to collect data to have continous understanding base line of changing data but additionally I recommend adding a column indicating if patient is on a medication plan. This would also help understand if certain medical treatments are effective in preventing strokes. 
 - Additionally, based on our models we can deduce that 93% of our data will predict the likley hood of patients will have a stroke based on features such as age, smoking status, bmi, heart disease and avg glucose level.
   


# Contact info for Collaboration 

### For any inquires regarding this data set or future collaboration please feel free to reach out via email at valmazan12@gmail.com. Visit my Github repository! 




