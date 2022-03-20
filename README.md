# Heart-Failure-Prediction
![image](https://user-images.githubusercontent.com/91767251/159140224-94d1219c-01ed-470a-8516-8e41b12aa7f9.png)

**Introduction:** 

According to Long Beach and Cleveland Clinic Foundation, cardiovascular diseases are the number one cause of death globally, taking a toll of eighteen million lives each year, and accounts for thirty-one percent of all deaths worldwide. In a simple sense, four out of five deaths in cardiovascular diseases are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under seventy years of age. Heart failure is a common event caused by cardiovascular diseases and this dataset contains twelve features that can be used to predict a possible heart disease:
  1. Age: age of the patient [years].
  2. Sex: sex of the patient [M: Male, F: Female].
  3. ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic].
  4. RestingBP: resting blood pressure [mm Hg].
  5. Cholesterol: serum cholesterol [mm/dl].
  6. FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise].
  7. RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria].
  8. MaxHR: maximum heart rate achieved [Numeric value between 60 and 202].
  9. ExerciseAngina: exercise-induced angina [Y: Yes, N: No].
  10. Oldpeak: oldpeak = ST [Numeric value measured in depression].
  11. ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping].
  12. HeartDisease: output class [1: heart disease, 0: Normal].

People with cardiovascular disease or who are at high cardiovascular risk is due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease. Therefore, machine learning can be a great asset to the early detection and mangement of people who have cardiovascular disease or who simply have high cardiovascular risk.

**Description Statistics:**

https://github.com/kim1806/Heart-Failure-Prediction/blob/main/Descriptive%20Statistics%20Heart%20Disease%20Prediction.ipynb

![newplot](https://user-images.githubusercontent.com/91767251/159189899-a732ce01-7983-4aaa-a12e-f69015f1620c.png)

Mean age: 53.510893246187365

Median age: 54.0

![newplot (1)](https://user-images.githubusercontent.com/91767251/159189924-930129c6-de35-4431-9058-4de3096f8878.png)

The values are concentrated between 200-300 but we see the range is 438. The reason is because of outliers in the data.

![newplot (2)](https://user-images.githubusercontent.com/91767251/159189941-7d80b08c-4b30-4d3f-965c-d3dba36cb492.png)

The numbers outside the range of 115.75 and 369.75 will be considered as outliers
The box plot verify our calculation. All the number greater than 369.75 are shown as outliers.

**Data Cleaning Problems:**

https://github.com/kim1806/Heart-Failure-Prediction/blob/main/Data%20Cleaning%20Heart%20Disease%20Prediction%20.ipynb

  1. Correcting the data types.
  2. Removing the unecessary columns or values.
  3. Handling missing values.

**EDA:**

https://github.com/kim1806/Heart-Failure-Prediction/blob/main/EDA%20Heart%20Disease%20Prediction.ipynb

![image](https://user-images.githubusercontent.com/91767251/159147825-87eabf42-ccbd-4355-844c-eb52f59d9ab2.png)

Adults age 50 and older are more likely than younger people to have heart disease.

![image](https://user-images.githubusercontent.com/91767251/159147839-1a675b40-3889-4f1f-80e2-57739a8c3010.png)

Asymptomatic is the most common type of chest pain among patients with heart disease.

![image](https://user-images.githubusercontent.com/91767251/159190789-e4f4d0dd-e88b-48fd-b272-a389c4f1d441.png)

A pairplot between heart disease with age, sex, chestPainType, restingBP, cholesterol, fastingBS, restingECG, maxHR ExerciseAngina, Old_Peak, and ST_Slope.
