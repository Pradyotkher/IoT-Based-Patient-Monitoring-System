# IoT-Based-Patient-Monitoring-System
An IoT based patient monitoring System with  application of Data Analytics
An IoT based system which uses a pulse oximeter sensor to take the values the SP02 level of the patient, Heart Rate of the patient and the Age of the patient.
The age is mannually entered by the patient.
The values taken from the Sensor are posted to ThingSpeak via HTTP post request.
From ThingSpeak the dataset is taken based on the sensor values. Now that we have the dataset we will go towards Data Analysis part of the project.
We use the Jupyter Notebook to perform the data analysis.
We have used the DecisionTreeClassifier model to train and perform the predictions.
The predictions are based on the values taken from the patient.
According to the patient's age, the model will predict if the patient is in normal condition or if he needs oxygen supply or if the heart rate is low or if the patient requires intense Care as his/her SP02 and heart rate are both low according to the patient's age.
