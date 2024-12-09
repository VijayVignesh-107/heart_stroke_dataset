# heart_stroke_dataset

Hi,

As part of My journey as Data scientist, i'm analysing various dataset to improve my skills and knowledge. In this repository, i'm planning to analyse a healthcare dataset that gives us information about multiple medical symptoms that may lead to heart stroke.

The dataset has 12 columns, each column gives us information about each symptoms based on unique records.

**Column explanation:**

ID: This column gives us the unique value of each record. 

gender: This column give us the gender of the each record.

Age: This column gives us the age of the each patient of the record.

Hypertension: This column gives us the value whether the patient has already diagonised with hypertension or not according to the records.

Hear_disease: This column gives us the value whether the patient has already diagonised with heart_disease or not according to the records.

Ever_married: This column indicates whether the patient is married or not.

Work_type: This column gives us information about which kind of work the patient does. 

Residence_type: This column gives us information about where the patient resides by according to the records.

avg_glucose_level:  This column gives us the average blood glucose level of the patient according to the records.

bmi: This column gives us the Body mass index value of the patient according to the records. Using this column we could identify obese people, which is one of the leading factors for stroke.

smoking_status: This column gives us the smoking status of the patient according to the records. Active smokers are most likely to get stroke.

stroke: With the use of all other column, this column gives us whether the patient has experienced a stroke or not.

**Dependent/Independent columns**

In the dataset, we have dependent and independent column. Independent columns are the ones which do not influence the other column based on its value. depndent columns are the ones in which the values are dependent on the values of other columns. PFA the dependent/independent columns presernt in the dataset.

Dependent columns: stroke

Independent columns: id,gender,age,hypertension,heart_disease,ever_married,work_type,Residence_type,avg_glucose_level,bmi,smoking_status.

# Supervised Learning:

This dataset is based on Supervised Learning. By calculating the independent columns, how they influence the dependent column. The model i'm trying to develop, is by using the independent column values, to predict whether the stroke will occur for a patient or not.









