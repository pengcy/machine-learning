# What is Machine Learning?

Two definitions of Machine Learning are offered. Arthur Samuel described it as: "<b>the field of study that gives computers the ability to learn without being explicitly programmed.</b>" This is an older, informal definition.

Tom Mitchell provides a more modern definition: "<b>A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E.</b>"

### Example: playing checkers.

E = the experience of playing many games of checkers

T = the task of playing checkers.

P = the probability that the program will win the next game.

In general, any machine learning problem can be assigned to one of two broad classifications:

Supervised learning and Unsupervised learning.


# Supervised learning and unsupervised learning.

### Supervised learning

Given the data with an answer. Two types of problem in supervised learning, regression and classification.

#### Regression problems:

* Given data about the size of houses on the real estate market, try to predict their price.

* Given a large number of inventory, predict how many of them will sell over the next 3 months.

* Given a picture of a person, we have to predict their age on the basis of the given picture.

#### Classification problems:

* Given a patient with a tumor, we have to predict whether the tumor is malignant or benign.

* Given email labeled as spam/not spam, learn a spam filter.

* Given a dataset of patients diagnosed as either having diabetes or not, learn to classify new patients as having diabetes or not.

### Unsupervised learning

Given the data without an answer, let the computer to group things.

Given a set of news articles found on the web, group the into set of articles about the same story.

Given a database of custom data, automatically discover market segments and group customers into different market segments.

Clustering: Take a collection of 1,000,000 different genes, and find a way to automatically group these genes into groups that are somehow similar or related by different variables, such as lifespan, location, roles, and so on.

Non-clustering: The "Cocktail Party Algorithm", allows you to find structure in a chaotic environment. (i.e. identifying individual voices and music from a mesh of sounds at a cocktail party).
