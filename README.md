# AKASH-GUPTA
I am a graduate student at University of Texas at Dallas pursuing my Masters in Business Analytics.

Logistic Regression
Ledoitte, a management consulting firm, is studying the roles played by experience and
training in a system administrator’s ability to complete a set of tasks in a specified
amount of time. Ledoitte is interested in figuring out which administrators can
complete given tasks within a specified time and those who are not.
Data are collected on the performance of 75 randomly selected administrators. They are
stored in the file SystemAdministrators.csv (available on eLearning).
The variable Experience measures months of full-time system administrator experience,
while Training measures the number of relevant training credits. The outcome variable
Completed is either Yes or No, according to whether or not the administrator completed
the tasks.

1. Using ggplot2 package, create a scatter plot of Experience vs. Training using
color or symbol to distinguish programmers who completed the task from those
who did not complete it. Which predictor(s) appear(s) potentially useful for
classifying task completion?
2. Run a logistic regression model with both predictors using the entire dataset
as training data. Generate a confusion matrix and answer the following:
among those who completed the task, what is the percentage of programmers
incorrectly classified as failing to complete the task?
3. How much experience must be accumulated by a programmer with 6 training
credits before his or her estimated probability of completing the task exceeds
0.6? (Hint: in a logistic regression you can write the left hand-side of the
regression equation as the log of odds).
