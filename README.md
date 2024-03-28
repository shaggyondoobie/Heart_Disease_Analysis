# Heart_Disease_Analysis
This folder contains the heart_disease_dataset in excel format along with the jupyter notebook which has the code for the various machinle learning algorithms. The data contains various attributes as mentioned below. The goal is to perform EDA and then pre-process data and perform ML algorithms to predict the 'output' column.
The dataset didnt contain any null values and upon performing EDA, there were some clear identifying patterns in the dataset. The chest pain column and maximum heart rate column had the highest postiive correlation with the output column whilst exercise induced angina and oldpeak had the highest negative correlation with the output column.
We got the best results with Random Forest model which had a 87% accuracy with only 8 cases being incorrectly predicted in the test dataset. Upon considering the important attributes which show a high correlation with the output column, the Random Forest and Logistic Regression model show the best results with only 7 cases being incorrectly predicted.

The attributes glossary:

Age : Age of the patient

Sex : Sex of the patient

exang: exercise induced angina (1 = yes; 0 = no)

ca: number of major vessels (0-3)

cp : Chest Pain type chest pain type

Value 1: typical angina
Value 2: atypical angina
Value 3: non-anginal pain
Value 4: asymptomatic
trtbps : resting blood pressure (in mm Hg)

chol : cholestoral in mg/dl fetched via BMI sensor

fbs : (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

rest_ecg : resting electrocardiographic results

Value 0: normal
Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
thalach : maximum heart rate achieved

output : 0= less chance of heart attack 1= more chance of heart attack
