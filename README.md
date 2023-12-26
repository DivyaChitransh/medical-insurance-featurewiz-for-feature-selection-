# medical-insurance-featurewiz-for-feature-selection-
**About this Dataset**<br>
Context<br>
Machine Learning with R by Brett Lantz is a book that provides an introduction to machine learning using R. As far as I can tell, Packt Publishing does not make its datasets available online unless you buy the book and create a user account which can be a problem if you are checking the book out from the library or borrowing the book from a friend. All of these datasets are in the public domain but simply needed some cleaning up and recoding to match the format in the book.

Content

* age: age of primary beneficiary

* sex: insurance contractor gender, female, male

* bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height,
* objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9

* children: Number of children covered by health insurance / Number of dependents

**ML Operations**<br>
1.imported basic python libraries and modules like numpy and pandas <br>
2.basic exploratory data analysis(check for null values, datatypes, unique data,etc)<br>
3.Scaled only numerical features<br>
4.label encoded categorical features using panda's factorizor<br>
5.made sure not to change 'children' as they are either numerical <br>
6.checked for skewness in numerical features by drawing distribution plot<br>
7.you can numerically check for skewness using wilk-shapiro test<br>
8.convert skewed features to normal distribution using QuantileTransformation<br>
9.make sure the datatypes for features are correct<br>
10.used featurewiz for feature-selection<br>
11.once the features were selected train and evaluate the desired model.<br>

