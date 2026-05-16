# Exercise-Based-Prediction-of-Glucose-Events-in-Youth-with-Type-1-Diabetes

## Project Overview 
This is a group capstone project that analyzes real-world clinical data from the T1DEXIP pediatric dataset to forecast glucose events following physical activity, addressing an under-researched data science problem using data from a major hospital study of 250 youth with Type 1 Diabetes. The study explored how different pre-exercise time windows (2, 4, and 6 hours) impact predictive performance and compared multiple modeling approaches including:

 * Mixed Effects Random Forest (MERF)
 * Gaussian Process Boosted Trees (GPBoost)
 * Long Short-Term Memory Networks (LSTM)

## Our Data
* This project used the awesome T1DEXIP Pediatric Dataset from a real world clinical study. Data was collected under real-world free-living conditions using CGMs, Garmin wearables, and the Bant mobile application.
* More info on the clinical study:
  * https://search.vivli.org/doiLanding/studies/PR00008429/isLanding
  * https://helmsleytrust.org/request_for_proposal/improving-exercise-with-type-1-diabetes-moving-data-towards-solutions/
* We had access to Continuous Glucose Monitoring (CGM) data, Heart rate and wearable device metrics, Physical activity information, Meal data, Insulin dosage records, Demographic and contextual patient data.

## Results
* Discovered that a 2-hour window post-exercise is the most effective period for forecasting glucose fluctuations. 
* Longer pre-exercise windows consistently improved prediction accuracy. The GPBoost model achieved the best balance of performance and interpretability.
* Hypoglycemia prediction remained the most challenging due to severe class imbalance.
* Findings demonstrated the importance of contextual physiological and activity-based features for glucose forecasting.

