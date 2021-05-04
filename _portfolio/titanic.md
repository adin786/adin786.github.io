---
title: "Titanic passenger  survivor prediction"
excerpt: "Predicted survival status for passengers onboard the Titanic cruise ship."
header:
  image: /assets/images/titanic-header.jpg
---
Predicted survival status for passengers onboard the Titanic cruise ship. Dataset from www.kaggle.com

- Pandas and Seaborn for exploratory analysis
- Engineered features from text data like title and deck number. Engineered numerical features like family_size, ticket_frequency
- Trained, tuned and compared classifier models based on Logistic Regression, Decision Tree, and Random Forest
- Best model gave cross validated accuracy of 0.826 and AUC of 0.880.

Correlation matrix between numerical params

![Correlation matrix](images/titanic_corrmat.png)

Wanted to impute age with grouped medians, rather than drop rows (small dataset), so plotted distribution by sex.

![Sex vs Age](images/titanic_sex_vs_age.png)

This showed sex was not a big enough differentiator in median Age, so I grouped/pivoted the dataset by Pclass also.

|Sex|Pclass    |   ('Age', 'count') |   ('Age', 'median') |
|:-----|-|-------------------:|--------------------:|
|female|1|                144 |                36   |
|female|2|                106 |                28   |
|female|3|                216 |                22   |
|male|1|                179 |                42   |
|male|2|                171 |                29.5 |
|male|3|                493 |                25   |

I plotted the probability of survival according to which Deck each passenger was on.  No-one in deck T survived.

![Deck vs Survived](images/titanic_deck_vs_survived.png)

I plotted the how ticket frequency (shared ticket numbers) affected survival rates. Most traveled on unique ticket #s, but there is a small peak at frequency=7, so some larger groups had a better chance of survival, but mostly, it was individuals who survived rather than the groups with shared ticket#s

![Ticket freq vs survived](images/titanic_ticketfreq_vs_survived.png)

# Model performance
Trained and compared various classifiers.  Results tabulated below, showing progress by tuning each with GridSearchCV.  

- Models 0 --> 5 were trained only with ['Fare','Title','Deck', Sex']
- Models 6 --> 9 were trained with additional features ['Age','Embarked','familysize','Pclass','Ticket_Frequency','SibSp','Parch']

|  # | modelname            |   acc_train |   acc_test |   precision |   recall |       f1 |      auc |   cv_mean |    cv_std |
|---:|:---------------------|------------:|-----------:|------------:|---------:|---------:|---------:|----------:|----------:|
|  0 | logreg               |    0.796348 |   0.787709 |    0.743243 | 0.743243 | 0.743243 | 0.867181 |  0.776662 | 0.013828  |
|  1 | logreg_tune          |    0.792135 |   0.793296 |    0.760563 | 0.72973  | 0.744828 | 0.866409 |  0.78786  | 0.0200878 |
|  2 | tree                 |    0.926966 |   0.782123 |    0.753623 | 0.702703 | 0.727273 | 0.790927 |  0.793516 | 0.0328465 |
|  3 | tree_tune            |    0.926966 |   0.782123 |    0.753623 | 0.702703 | 0.727273 | 0.790927 |  0.793516 | 0.0328465 |
|  4 | forest               |    0.926966 |   0.776536 |    0.736111 | 0.716216 | 0.726027 | 0.859395 |  0.774471 | 0.0403078 |
|  5 | forest_tune          |    0.926966 |   0.765363 |    0.716216 | 0.716216 | 0.716216 | 0.852896 |  0.774471 | 0.037886  |
|  6 | logreg2              |    0.845506 |   0.826816 |    0.786667 | 0.797297 | 0.791946 | 0.881725 |  0.824914 | 0.0179236 |
|  7 | logreg2_tune         |    0.853933 |   0.815642 |    0.780822 | 0.77027  | 0.77551  | 0.879923 |  0.826044 | 0.0200473 |
|  8 | forest2              |    0.985955 |   0.815642 |    0.773333 | 0.783784 | 0.778523 | 0.896139 |  0.803565 | 0.0368746 |
|  9 | forest2_tune         |    0.933989 |   0.821229 |    0.8      | 0.756757 | 0.777778 | 0.897941 |  0.819315 | 0.0266063 |

Best performing classifier in cv_score was model 7.  
- Cross validated Accuracy score: 0.826
- ROC-AUC score: 0.880

ROC curve below

![Logreg2 chart](images/titanic_logreg2_charts.png)

