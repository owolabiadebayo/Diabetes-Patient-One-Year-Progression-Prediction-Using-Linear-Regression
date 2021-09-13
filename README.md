## Diabetes Patient Dataset Using Regression/Machine Learning Intro

### In this section, we will work with a small dataset about diabetes that is built into Scikit-learn for learning purposes. Imagine that you wanted to test a treatment for diabetic patients. Machine Learning models might help you determine which patients would respond better to the treatment, based on combinations of variables. Even a very basic regression model, when visualized, might show information about variables that would help you organize your theoretical clinical trials

> In a new code cell, load the diabetes dataset by calling load_diabetes(). The input return_X_y=True signals that X will be a data matrix, and y will be the regression target.~

```javascript
X, (y = datasets.load_diabetes((return_X_y = True)));
print(X.shape);
print(X[0]);
```

_Ten baseline variables, age, sex, body mass index, average blood pressure, and six blood serum measurements were obtained for each of n = 442 diabetes patients, as well as the response of interest, a quantitative measure of disease progression one year after baseline._

#### Data Set Characteristic

> Number of instance 442
> Number of attributes: First 10 columns are numeric predictive values
> Target: Column 11 is a quantitative measure of disease progression one year after baseline

#### Attribute Information

```javascript
* age age in years

* sex

* bmi body mass index

* bp average blood pressure

* s1 tc, total serum cholesterol

* s2 ldl, low-density lipoproteins

* s3 hdl, high-density lipoproteins

* s4 tch, total cholesterol / HDL

* s5 ltg, possibly log of serum triglycerides level

* s6 glu, blood sugar level
```

linear regression model, created a prediction with it, and displayed it in a plot!
