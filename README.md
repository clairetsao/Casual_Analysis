# Identifying causality using experiments
Techniques Utilized: R, T-Test, Linear Regression

In this project, I explore methods for identifying causality using experiments. Leveraging R, I implement T-Tests and Linear Regression to analyze relationships and infer causality between variables.

## Question 1 - Use data_Q1.csv
Platforms use various methods to stimulate user’s content creation. This includes paying users for reviews and providing awards and badges to users. Reddit is one of the largest platforms for creating and sharing content. On Reddit, users can recognize other contributions by providing gold to each other. However, does getting Reddit gold actually increase the receiver’s content generation?
To find out, researchers gave 905 random users reddit gold. Data is included for a similar number of users in the control group who did not receive gold during the time of the experiment. Import the data and examine:

a) If the control and treatment groups are similar across tenure, premium_user, and num_posts_before metrics.

b) Does getting reddit gold increase likelihood that the user will post (use the posted metric as the dependent variable and treated as the independent variable)? Use a simple linear model (not a logit) for the analysis.

c) What sorts of users are more likely to increase their contribution? (use the tenure and the first_timer variables)

d) Is the SUTVA assumption likely to be violated in the experiment?

## Question 1 - Use data_Q2.csv
In 2019, Esther Duflo and Abhijeet Banerjee won the Nobel Prize in Economics for their research on experiments on education and poverty. In one of their experiments, they aimed to increase the academic performance of children in public schools in Vadodara (a town in India).
Duflo and her co-authors examined the impact of the Balsakhi program. In the program, the weakest academic students in Grade 3 were pulled out of their classroom and provided with supplementary classes, during school hours, provided by a Balsakhi, a young woman from the community who would work with the children on basic skills. Schools that did not receive the program formed the comparison group.
Data is provided for the period prior to the introduction of Balsakhis. This is known as the pre-period. Data is provided for math and language tests.
Using the data provided:

a) Use a t-test to see if there is a statistical difference in the pre-period between schools in the treatment (bal = 1) and control (bal = 0). This will check if randomization has been done correctly. To do this, calculate the average normalized test score(norm) for the pre period (pre = 1) for math (test_type = 0). Is there a statistical difference between students who got the Balsakhi program and did not get the program? Perform the same test for language (test_type = 1).

b) Calculate the average test scores for the post period (post = 1) for math for treatment and control. Is there a statistical difference between students in the two groups of schools? Use a t- test model to test the increase. Perform the same analysis for language test scores.

c) Can you conclude if the Balsakhi program increase test scores in reading and mathematics?

d) Is the SUTVA assumption violated in the example?
