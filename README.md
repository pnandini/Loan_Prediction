# Loan_Prediction

Statistics & EDA 101 - Knowledge Evaluation Test
 “Torture the data, and it will confess to anything.” – Ronald Coase

Problem at Hand
Credence Housing Finance Ltd. deals in all home loans. They have presence across all urban, semi urban and rural areas. Customer first apply for home loan, after that the company validates the customer eligibility for loan. 
CEO Mr. Dubey hires you as a statistical analyst who wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. Before that, he wants you to present a detail EDA on the available data to identify potential factors.

Please solve these questions for Mr. Dubey -
Identify the variable types based on the data in them and describe them using appropriate central tendency measures (5) talk about which data and measure of sopread

Discuss few measures of spread for continuous variables (5) -- Look at the values and talk about them … quartiles ranges -- skewed ---  https://medium.com/datarunner/statistics-for-data-science-i-measures-of-central-tendency-using-r-and-python-6a20c25be7fe
https://medium.com/swlh/descriptive-statistics-measures-of-spread-6374abe2050c

https://machinelearningmastery.com/how-to-calculate-the-5-number-summary-for-your-data-in-python/


Perform a Univariate analysis on applicant income and loan amount. (Use both numerical and graphical representations) (10)
https://towardsdatascience.com/exploring-univariate-data-e7e2dc8fde80

Research various methods of missing value treatments. Perform missing value treatment on loan amount(mean, median, other variables to predict loan amount --- ) and marital status(mode imputation -- ) (10) 


Research various methods of outlier treatments. Perform outlier treatment on applicant’s income and co-applicant’s income (10) (Normalise, take it out completely, --- research )

Generate histograms for applicant’s income and loan amount for each of education type. Plot the histograms on same graph and specify the type of distribution they follow. (10) -- https://towardsdatascience.com/identify-your-datas-distribution-d76062fc0802


Answer these hypotheses with appropriate visualizations and tests (8 x 5 = 40) 
[Hint: For cont. vs cat relationship – use t-test/ANOVA; For cat vs cat relationship – use chi-sq] 
https://github.com/purebinary/Data-Analyst-Nanodegree/blob/e1d900a12df676ba5d8317cca7d541146f940536/P2%20Investigate%20a%20Dataset/Investigate%20Titanic%20Dataset.ipynb

https://medium.com/@athina.b/statistical-tests-and-their-importance-d56af9412630

https://www.pluralsight.com/guides/finding-relationships-data-with-python --


https://towardsdatascience.com/how-to-test-for-statistically-significant-relationships-between-categorical-variables-with-chi-66c3ebeda7cc (cat to cat) -- 

https://stats.idre.ucla.edu/spss/whatstat/what-statistical-analysis-should-i-usestatistical-analyses-using-spss/ - very good source -- 


https://stackabuse.com/statistical-hypothesis-analysis-in-python-with-anovas-chi-square-and-pearson-correlation/ -- has some python tests performed

https://statweb.stanford.edu/~kriss1/statistics-consulting-cheat.pdf - might be useful

Are males having a higher loan approval status?  -- graph with approva stats, males and females --  2nd questionhttps://www.pluralsight.com/guides/finding-relationships-data-with-python, or independent 2 sample t tests? chi squared test 
Are graduates earning more income than non-graduates?  -  one way anova with mean income values ? --- t tests?  box plot --- prefer t tests ()
Are self-employed applying for higher loan amount than employed? self, employed vs loan amount -- one way anova --  prefer t tests ()
Is there a relationship between self-employment and education status?   chi square 
Is urbanicity of loan property related to loan approval status?  chi squared 
How is applicant’s income related to the loan amount that they get? correlation pearsons -- scatter plot   https://towardsdatascience.com/the-search-for-categorical-correlation-a1cf7f1888c9
How helpful is previous credit history in determining the loan approval?  chi square test /  R squared  for categorical confusion matrix---   
Are people with more dependents reliable for giving loans? -- categories vs loan approval (cat ) chi squared  -- check on thing --- data in intervals--  anova (data is intervals … do we do anova) --- 

Explore the data further (only tables and visualizations) and identify any interesting relationship among attributes (5)  --- explore the pairplot,  scatterplotsand find correlations, etc 
https://towardsdatascience.com/a-z-of-exploratory-data-analysis-under-10-mins-aae0f598dfff
Summarize the key findings and write a 5-10 line short executive summary to Mr. Dubey (10) 

Data Dictionary:
Variable
Description
Loan_ID
Unique Loan ID
Gender
Male/ Female
Married
Applicant married (Y/N)
Dependents
Number of dependents
Education
Applicant Education (Graduate/ Under Graduate)
Self_Employed
Self employed (Y/N)
ApplicantIncome
Applicant income
CoapplicantIncome
Coapplicant income
LoanAmount
Loan amount in thousands
Loan_Amount_Term
Term of loan in months
Credit_History
credit history meets guidelines
Property_Area
Urban/ Semi Urban/ Rural
Loan_Status
Loan approved (Y/N)


