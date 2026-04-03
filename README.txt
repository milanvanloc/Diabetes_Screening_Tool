The diabetes dataset is from here: https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset

(WIP)

This is a XGBOOST decision tree focused on maintaining a high recall (90+%) for diabetic patient screening.

XGBOOST was chosen due to its superior handling of missing values, this is because patients may not be able
to provide all information and/or may not want to provide certain information.

It will also eventually rank feature importance and attempt to suggest possible measurements to input in order
to increase its confidence about the patients screening, and a user friendly UI so it is easily able to be used by doctors.

Important note: This is not a diagnosis tool, it is a screening tool to be used in cohesion with a medical professional.