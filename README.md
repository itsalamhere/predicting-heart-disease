# predicting-heart-disease

We're predicting heart disease events using a machine learning model of k-Nearest Neighbors (kNN). The [dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction) we're using is from Kaggle by Fede Soriano which consist of 11 clinical features:

* `Age`            : Age of the patient (years)
* `Sex`            : Sex of the patient
  * M   : Male
  * F   : Female)
* `ChestPainType`  : Chest pain type
  *  TA : Typical Angina
  * ATA : Atypical Angina
  * NAP : Non-Anginal Pain
  * ASY : Asymptomatic
* `RestingBP`      : Resting blood pressure (mm Hg)
* `Cholesterol`    : Serum cholesterol (mg/dL)
* `FastingBS`      : Fasting blood sugar
  * 1   : if FastingBS > 120 mg/dL
  * 0   : otherwise
* `RestingECG`     : Resting electrocardiogram results
  * Normal : Normal
  * ST     : having ST T-wave abnormality (T-wave inversions and/or ST elevation or depression of > 0.05 mV),
  * LVH    : showing probable or definite left ventricular hypertrophy by Estes' criteria
* `MaxHR`          : Maximum heart rate achieved (numeric range of 60 to 202)
* `ExerciseAngina` : Exercise-induced angina
  * Yes    : Yes
  * No     : No
* `Oldpeak`        : oldpeak = ST (Numeric value measured in depression)
* `ST_Slope`       : the slope of the peak exercise ST segment
  * Up     : upsloping
  * Flat   : flat
  * Down   : downsloping
* `HeartDisease`   : output class
  * 1      : Heart disease
  * 0      : Normal
