# Income & Education Data Analysis

**Objective**: To explore the correlation between education level, age, and income, and to identify the key factors that most significantly impact income levels.

**Dataset**: This analysis is based on the [Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/Adult) from the UCI Machine Learning Repository, which contains demographic data related to income, education, and other attributes.

**Analysis Steps**:

- **Data Preprocessing and Feature Engineering**: Handle categorical features, manage missing values, and prepare the data for analysis.
- **Exploratory Data Analysis and Correlation**: Build visualizations and conduct correlation analysis to identify factors like education and age that influence income.
- **Modeling**: Build a simple regression model to predict income based on the identified key factors.

# **Dataset Information**

**Additional Information**

Extraction was done by Barry Becker from the 1994 Census database.  A set of reasonably clean records was extracted using the following conditions: ((AAGE>16) && (AGI>100) && (AFNLWGT>1)&& (HRSWK>0))
Prediction task is to determine whether a person makes over 50K a year.

**Has Missing Values?**

Yes

| **Variable Name** | **Role** | **Type** | **Demographic** | **Description** | **Missing Values** |
| --- | --- | --- | --- | --- | --- |
| age | Feature | Integer | Age | N/A | no |
| workclass | Feature | Categorical | Income | Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked. | yes |
| fnlwgt | Feature | Integer |  |  | no |
| education | Feature | Categorical | Education Level | Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool. | no |
| education-num | Feature | Integer | Education Level |  | no |
| marital-status | Feature | Categorical | Other | Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse. | no |
| occupation | Feature | Categorical | Other | Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces. | yes |
| relationship | Feature | Categorical | Other | Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried. | no |
| race | Feature | Categorical | Race | White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black. | no |
| sex | Feature | Binary | Sex | Female, Male. | no |
| capital-gain | Feature | Integer |  |  | no |
| capital-loss | Feature | Integer |  |  | no |
| hours-per-week | Feature | Integer |  |  | no |
| native-country | Feature | Categorical | Other | United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands. | yes |
| income | Target | Binary | Income | >50K, <=50K. | no |

# **Dataset Files**

| **File** | **Size** |
| --- | --- |
| adult.data | 4MB |
| adult.test | 2MB |
| adult.names | 5.2KB |
| old.adult.names | 4.3KB |
| Index | 140B |

# **License**

This dataset is licensed under a [**Creative Commons Attribution 4.0 International**](https://creativecommons.org/licenses/by/4.0/legalcode) (CC BY 4.0) license.

This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.