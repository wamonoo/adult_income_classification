# Predict whether income of adults in the US exceeds $50K / yr using census data.

This project utilizes MLlib, Apache Spark's scalable machine learning library to perform binary classification using a range of models on US census data. The aim is to predict the income class of individuals, i.e. if an individual earns <=50K or >50k a year given some specific socio-economic variables.

Attribute Information:

age: continuous

workclass: Private,Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked

fnlwgt: continuous

education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc...

education-num: continuous

marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent...

occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners...

relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried

race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black

sex: Female, Male , capital-gain: continuous, capital-loss: continuous, hours-per-week: continuous

native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany...

Income: <=50K, >50K

If github is unable to render the notebook as this happens sometimes, kindly use the link below to get an nbviewer static version
https://nbviewer.jupyter.org/github/wamonoo/adult_income_classification/blob/master/Binary_classification_proj.ipynb
