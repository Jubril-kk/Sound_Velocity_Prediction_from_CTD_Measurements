###### \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* **BRIEF OVERVIEW** \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

The focus of this project is to predict the sound velocity from CTD Measurements. Professionals widely agree that the speed of sound in the seas and oceans significantly impacts the propagation of acoustic waves. This variation can be influenced by ocean properties like temperature, salinity, and pressure, among others. This sparked my curiosity to compare the sound velocity (computed from empirical formula: UNESCO  (Chen and Miller) with the values predicted by machine learning models. 



* Project Title: Sound Velocity Prediction from CTD Measurements
* Data: CTD Measurements
* Source: GEOMAR Helmholtz Centre (https://doi.pangaea.de/10.1594/PANGAEA.905471)
* Aim: Predict the sound velocity (in water) using ML models and compare with empirical formula.
* Models used: Random Forest, XGBoost, LightGBM, KNN
* Results: The computed sound velocity values (from empirical formula) were compared with the predicted values of sound velocity. The performance evaluation of the models are:

      RandomForest → 0.127, cross-validation (cv) accuracy → 0.986 ± 0.025,
      XGBoost → 0.071, cv accuracy → 0.981 ± 0.035,
      LightGBM → 0.068, cv accuracy → 0.979 ± 0.040, and
      KNN → 0.007, cv accuracy → 0.941 ± 0.042.



