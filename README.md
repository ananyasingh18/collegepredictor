# collegepredictor
Predictor that displays the probability of qualifying for a college
Python Libraries
• Import pandas:

Using pandas to perform tasks like reading the csv file, slicing,
checking for null values and other data cleaning and filling jobs.

• Import NumPy:

Using features to calculate basic mathematical operations like
inverse, matrix multiplication etc.

• Import Matlplotlib:

Using plyplot to plot line graphs, bar graphs, scatter plots.

• Import Seaborn:

Depicting a Pearson correlation heat map, to form training and
testing data and calculating r2 score and other metric values.

• Import sklearn:

Using standardscalar to standardise features by removing the
mean and scaling to unit variance.

Overview of the Project
The aim of this project is to predict the probability of a student getting
admission into a particular university (University rated out of 5) using a set of
parameters like GRE Score, TOEFL Score, Statement Of Purpose Grade, Letter
of Recommendation Grade, CGPA and Research Experience (if any).

The model used for training and testing the data is Linear Regression using:

1. Least Squares Error: We apply ordinary Least Squares to get the values of
Beta matrix that is further reduced to optimised values using Gradient
Descent.
2. Gradient Descent along with L2 regularisation: Applying K-Fold using
L2 Regularisation, we get the best value of learning rate which gives us
least error. It is observed that regularisation parameter has no effect on
our model and thus it is ignored.
The best value of learning rate from K-Fold and Beta matrix from Least
Squares is used as starting value in Gradient Descent Optimisation
