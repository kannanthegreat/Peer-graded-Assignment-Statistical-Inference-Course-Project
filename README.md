# Peer-graded-Assignment-Statistical-Inference-Course-Project
This project is a part of Coursera Statistical Inference course
Instructions

The project consists of two parts:

A simulation exercise.
Basic inferential data analysis.
A report answering the assignment questions is to be created using knitr and convert to a pdf. 
Each pdf report should be no more than 3 pages with 3 pages of supporting appendix material if needed (code, figures, etcetera).
Review criteria 
Did you show where the distribution is centered at and compare it to the theoretical center of the distribution?
Did you show how variable it is and compare it to the theoretical variance of the distribution?
Did you perform an exploratory data analysis of at least a single plot or table highlighting basic features of the data?
Did the student perform some relevant confidence intervals and/or tests?
Were the results of the tests and/or intervals interpreted in the context of the problem correctly?
Did the student describe the assumptions needed for their conclusions?
Part 1: Simulation Exercise Instructionsless 
In this project we will investigate the exponential distribution in R and compare it with the Central Limit Theorem. The exponential distribution can be simulated in R with rexp(n, lambda) where lambda is the rate parameter. The mean of exponential distribution is 1/lambda and the standard deviation is also 1/lambda. Set lambda = 0.2 for all of the simulations. We will investigate the distribution of averages of 40 exponentials. Note that we will need to do a thousand simulations.

Illustrate via simulation and associated explanatory text the properties of the distribution of the mean of 40 exponentials. It is requied to:

I. Show the sample mean and compare it to the theoretical mean of the distribution.
II. Show how variable the sample is (via variance) and compare it to the theoretical variance of the distribution.
III. Show that the distribution is approximately normal.
IV. In point 3, focus on the difference between the distribution of a large collection of random exponentials and the distribution of a large collection of averages of 40 exponentials.

Sample Project Report Structure

A sample set of headings that could be used to guide the creation of your report might be:

Title (give an appropriate title) and Author Name
Overview: In a few (2-3) sentences explain what is going to be reported on.
Simulations: Include English explanations of the simulations you ran, with the accompanying R code. Explanations should make clear what the R code accomplishes.
Sample Mean versus Theoretical Mean: 
i. Include figures with titles. 
ii. In the figures, highlight the means we are comparing. 
iii. Include text that explains the figures and what is shown on them, and provides appropriate numbers.
Sample Variance versus Theoretical Variance: 
i. Include figures (output from R) with titles. 
ii. Highlight the variances we are comparing. 
ii. Include text that explains oour understanding of the differences of the variances.
Distribution: 
Via figures and text, explain how one can tell the distribution is approximately normal.
Part 2: Basic Inferential Data Analysis Instructionsless

Now in the second portion of the project, we're going to analyze the ToothGrowth data in the R datasets package.
I. Load the ToothGrowth data and perform some basic exploratory data analyses
II.Provide a basic summary of the data.
III. Use confidence intervals and/or hypothesis tests to compare tooth growth by supp and dose. (Only use the techniques from class, even if there's other approaches worth considering)
Conclusions and the assumptions needed for your conclusions.

