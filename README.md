## Final Project Team Members
Mark Yocum<br />
Hubert Cheng<br />
Amrit Perera<br />

## Data Sources:

Wine Quality Dataset for Vinho Verde red/white wine.

#### Model Used

<br />

## Attribute Information:

Input variables (based on physicochemical tests):<br />
1 - fixed acidity <br />
2 - volatile acidity <br />
3 - citric acid <br />
4 - residual sugar <br />
5 - chlorides <br />
6 - free sulfur dioxide <br /> 
7 - total sulfur dioxide <br />
8 - density <br />
9 - pH <br />
10 - sulphates <br />
11 - alcohol <br />
Output variable (based on sensory data): <br />
12 - quality (score between 0 and 10) <br />

Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).<br />

#### Reference:
P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties.

## Note:
In the above reference, two datasets were created, using red and white wine samples.<br />

The inputs include objective tests (e.g. PH values) and the output is based on sensory data
(median of at least 3 evaluations made by wine experts). Each expert graded the wine quality 
between 0 (very bad) and 10 (very excellent).<br />

Several data mining methods were applied to model
these datasets under a regression approach. The support vector machine model achieved the
best results. Several metrics were computed: MAD, confusion matrix for a fixed error tolerance (T),
etc. Also, we plot the relative importances of the input variables (as measured by a sensitivity
analysis procedure).

