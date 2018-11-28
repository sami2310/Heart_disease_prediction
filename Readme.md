# Predicting heart disease using machine learning algorithms

# Acknowledgements
These professors are the ones who made the dataset available
University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D. V.A.
Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D

# Data Analysis:

**Age:**: age in years
**sex**: (1 = male; 0 = female)
**cp**: chest pain type
1. Value 1: typical angina
2. Value 2: atypical angina
3. Value 3: non-anginal pain
4. Value 4: asymptomatic

**trestbps:** resting blood pressure (in mm Hg on admission to the hospital)>
**chol:** serum cholestoral in mg/dl
**fbs:** (fasting blood sugar > 120 mg/dl)
1. 1 = true
2. 0 = false

**restecg:** (resting electrocardiographic results)
1.  Value 0: normal
2.  Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
3.  Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria

**thalach:** maximum heart rate achieved
**exang:** exercise induced angina
1.  1 = yes
2.  0 = no

**oldpeak:** ST depression induced by exercise relative to rest
**slope:** the slope of the peak exercise ST segment
1. Value 1: upsloping
2. Value 2: flat
3. Value 3: downsloping

**ca:** number of major vessels (0-3) colored by flourosopy<
**thal:** thalium heart scan
1. 3 = normal (no cold spots)
2. 6 = fixed defect (cold spots during rest and exercise)
3. 7 = reversible defect (when cold spots only appear during exercise)

**pred_attribute:** (the predicted attribute) diagnosis of heart disease (angiographic disease status)
1. Value 0: < 50% diameter narrowing
2. Value 1: > 50% diameter narrowing (in any major vessel: attributes 59 through 68 are vessels)

# Results
## Without feature engineering
 - **Logistic Regression :** 83.6 %
