# Heart-Disease-Prediction
Heart Disease is one of the major concerns to be dealt with. It is very important to identify it and do the proper treatment. Machine learning proves to be effective in making decisions and predictions from the large quantity of data produced by the healthcare industry.
Here, various ML models have been applied for classifying whether a person is suffering from Heart Disease or Not. 

## Libraries :  Pandas, Matplotlib, Numpy, Seaborn and Sklearn.

## Dataset : https://www.kaggle.com/datasets/mragpavank/heart-diseaseuci
The dataset used in this project is sourced from Kaggle. It consists of 303 individuals data and there are 14 columns in the dataset.

    Age: displays the age of the individual.
    Sex: displays the gender of the individual using the following format :

    1 = male
    0 = female

    Chest-pain type: displays the type of chest-pain experienced by the individual using the following format :

    1 = typical angina
    2 = atypical angina
    3 = non — anginal pain
    4 = asymptotic

    Resting Blood Pressure: displays the resting blood pressure value of an individual in mmHg (unit)
    Serum Cholestrol: displays the serum cholesterol in mg/dl (unit)
    Fasting Blood Sugar: compares the fasting blood sugar value of an individual with 120mg/dl. If fasting blood sugar > 120mg/dl then : 1 (true) else : 0 (false)
    Resting ECG : displays resting electrocardiographic results

    0 = normal
    1 = having ST-T wave abnormality
    2 = left ventricular hyperthrophy

    Max heart rate achieved : displays the max heart rate achieved by an individual.
    Exercise induced angina :

    1 = yes
    0 = no

    ST depression induced by exercise relative to rest: displays the value which is an integer or float.
    Peak exercise ST segment :

    1 = upsloping
    2 = flat
    3 = downsloping

    Number of major vessels (0–3) colored by flourosopy : displays the value as integer or float.
    Thal : displays the thalassemia :

    3 = normal
    6 = fixed defect
    7 = reversible defect

    Diagnosis of heart disease : Displays whether the individual is suffering from heart disease or not :

    0 = absence
    1, 2, 3, 4 = present.

### Accuracy Comparision of Diff Models used - 

 	Model 	                        Training Accuracy % 	Testing Accuracy %
	Logistic Regression 	        87.603306 	        88.524590
	K-nearest neighbors 	        87.603306 	        90.163934
 	Decision Tree Classifier 	100.000000 	        85.245902
 	Random Forest Classifier 	100.000000 	        85.245902
 	Support Vector Machine 	        92.561983 	        90.163934
