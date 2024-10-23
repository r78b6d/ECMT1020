java c
Assignment
ECMT1020: Introduction to Econometrics
Due: 25 Oct 2024 23:59
Instruction
• In this project, you will apply statistical methodologies you have learned to analyze real data.
• Each question has a particular mark, which can be found at the beginning of the question.
• Each group should provide the code they use (e.g.,  do file if STATA, R file if R, m file if Matlab), and the results should be perfectly replicable.
•  Provide a peer review report at the end of the group project.
– A peer review link will be sent via email in Week 12.
– Your participation will be evaluated by other team members.
–  The average score received from others, scaled by 2 to reach the maximum, will be used as a participation mark.
– If your average mark is 0, I will investigate the case separately. If it turns out that you did not participate at all, your group assignment mark will be 0.
– If none of group members submits the peer review report, the group will receive 0 for the participation mark.
•  The total mark (10pts) = assignment mark (8pts) + participation mark (2pts)
•  Report Style. Guideline
–  Page limits: maximum 10 pages (including main estimation results)
–  Font size:  12
–  Line Spacing: double
•  The submission should be made on Canvas via “Assignment”.
•  No email submission is acceptable.
•  The estimation results should be clearly readable.
•  Suppose you are interested in studying the effect of attending lectures on students’ academic achievement. To begin, download the dataset "Attend.csv" from Canvas.  The dataset consists of the following variables:
–  attend: classes attended out of 32
– termGPA: GPA for term
– priGPA: cumulative GPA prior to term
– ACT: ACT score
– final: final exam score
– hwrte: percent homework turned in
–  missed: number of classes missed
•  The original source of the data is  “Introductory Econometrics:  A Modern Approach” by Jeffrey M. Wooldridge, but I introduced some random noise.


Questions
1.  (2pts; Simple Regression) As an initial step, you decide to run a simple linear regression model.
1.a  (0.5pts) Regress termGPA on attend.  Report the estimation result (including at least the coefficient estimates and their standard errors, t-statistics and p-values) and interpret the estimated slope coefficient of attend.
1.b  (0.5pt) We have learned about the classical assumptions for valid OLS estimation. Which condition is likely to be problematic in your regression model?  Relate your answer to the summary statistics of the dependent variable.
1.c  (1pt) Instead of termGPA, you have decided to use its standardized measur代 写ECMT1020: Introduction to EconometricsMatlab
代做程序编程语言e, denoted by stdGPA, as the dependent variable.  (You need to define the variable by yourself.) Redo 1.a with the new dependent variable. Compare the estimation results from 1.a.
2.  (2pts; Multiple Regression) Suppose that not only attend, but also hwrte and final may affect GPA. Hence, you decide to run a multiple linear regression model.
2.a  (1pt) Regress stdGPA on attend, hwrte and final.  Report the estimation result (including at least the coefficient estimates and their standard errors, t-statistics and p-values of each explanatory variable). Compare the coefficient of attend from your answer in 1.c.
2.b  (1pt) You want to add one more explanatory variable which is the number of classes missed, denoted by missed. Would it be possible to analyze the model below?
stdGPA = β1 + β2attend + β3final + β4missed + u
If not, explain why and how to resolve it.
3.  (2pts; Dummy Variables) Now, suppose you want to argue that students who submit home- work on time and/or attend lectures more than 90% of the time are likely to achieve higher academic performance.
3.a (0.5pt) Generate the following variables:

Suppose you want to test H0  : E[hwi] = 0.8 by using the regression model.  Provide steps to conduct the testing. Explain why you choose the approach.
You will answer the question 3.b and 3.c with the above dummy variables.


3.b  (0.5pt) We begin with the following model:
stdGPA i = β1 + β2 hai + β3 hwi + β4 hai * hwi + ui
Provide estimation results and find interpretation of each coefficient.  Provide the coef- ficient estimate of β4  and its interpretation.
3.c  (1pt) Now, you are estimating the model below.
stdGPA i = β1 + β2 hai * attend i + β3 attend i + ui
Provide estimation results and discuss the marginal effect of additional attendance on the standardized GPA among students with an attendance rate higher than 90%.
4.  (2pts; Nonlinear Regression) Now, we study the effect of previous GPA on current GPA along with the effect of attendance.
(a)  (1pt) Start from the following model:stdGPA i = β1 + β2 hwi + β3 attend i + β4 s_priGPAi + ui ,                 (2)where s_priGPAi  is the standardized measure of the previous GPA of individual i. You expect that the effect of s_priGPA i  on stdGPA i  would increase if students received higher marks in the last semester.  To answer this question, which variable needs to be additionally introduced to the regression model?  Include the variable of your choice and report the estimation result.
(b)  (1pt) Conduct Ramsey’s RESET test to the model you suggested. Interpret the testing result.







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
