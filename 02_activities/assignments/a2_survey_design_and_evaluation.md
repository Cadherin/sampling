# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey (GSS) on Giving, Volunteering, and Participating (GVP), 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type: 
2. Sample size: 
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `1`

Describe the purpose of your survey:
```
The purpose of the survey is to determine the causes job dissatisfaction among entry- and lower-level employees and translate the insights into actions that could be taken to support retention efforts.  
```

Describe your target population, sampling frame, sampling units, and observational units:
```
1. Sample type: To ensure all employees in entry- and lower-lever roles are included in the survey, a stratified sampling approach will be taken to ensure all departments across the company are invited to participate in the survey.  

2. Sample size: Assuming the company has a total of 2,000 entry- and lower-level employees (N=2,000) and targeting a margin of error of no more than 5% (e=0.05), this translates to a Z-score of 1.96 (Z=1.96). I will also assume an expected distribution of responses to have a standard deviation of 0.5 or 50% (p=0.5). 

The ideal sample size (n0) could be determined by the formula: n0 = Z^2*p*(1-p)/e^2 = 1.96^2*0.5(1-0.5)/0.05^2 = 384.16 or 385. 

The adjusted sample size (n) based on known total population can be found using the formula: n = n0/(1+(n0-1)/N) = 385/(1+(385-1)/2000) = 322.99 or 323

3. Target population: All active entry- and lower-level employees across all departments within the company. 

4. Sampling frame: Active employee records from the company's HR system. A filter is to be applied to extract employee roles that align to the definition of entry- and lower level employees. These could include analysts, associates, junior developers, etc. HR team will be consulted on the proper filter to use.

5. Survey mode(s): A web-based survey using an company approved platform such as Microsoft Forms or Qualtrics are to be used. 

6. Timeline: The duration of the survey will last for 4 weeks. The first week will be devoted to the launch and raising awareness. The second and the third week will be focused on progress monitoring and sending out reminders to participants. The final week will be focused on data consolidation and last call to participants.

7. Response rate: We will target response rate to be 30-50%. This will ensure the number of respondents are beyond n0=323.

8. Weights: To ensure participation from all parts of the company is accounted for, weights referred to non-response are to be applied to departments that are underrepresented to ensure that a single department does not skew the overall results. 

9. Data processing: Quantitative and qualitative data will be handled differently. Quantitative data will be aggregated as appropriate. Qualitative data with text responses will be processed using theme clustering or natural language processing to extract key themes and keywords. For instance, clustering of causes of employee turnover could include:
- Training and feedback
- Trust
- Job stress
- Working environment
- Salary
- Leaders and manager
- Challenging work
- Family pressure
- Group size
, etc.

10. Cleaning, imputation: Export and consolidate survey data. Remove duplicates as necessary. Optional questions without responses will be treated as not answered instead of imputation to ensure that the results are not skewed.

11. Sources of error: There could be factors that lead to sources of errors such as employees who are readily disengaged and planning for an exit may either ignore the survey entirely or provide responses or comments that are on the extreme end of dissatisfaction. These could contribute to either the non-response rate or more severe dissatisfaction. Textual questions could lead to more ambiguous response from participants that may require more processing to extract meanings and for the textual information to be properly clustered or grouped appropriately. 

12. Limitations, known biases, etc.: While the survey is to be released to current employees, it may not capture sentiments from those who readily left the company. And these individuals may have insights that could not be captured from the intended survey population. 

13. Link to documentation and any additional sources used
https://doi.org/10.24018/ejbmr.2021.6.3.893
https://doi.org/10.1016/j.eswa.2025.126575


```
Your 5-10 question survey:
```
1. How strongly do you agree or disagree with the following statement? I feel valued by my department leadership for the contributions that I have made to the team. (Options include: Strongly agree, agree, neither agree nor disagree, disagree, strongly disagree)

2. Which of the following factors would most significantly improve your day-to-day satisfaction at the company? Select up to 3 factors.
(Options include: 
- Better health, wellness or mental health benefits
- Improved communication and transparency from leadership
- More opportunities to participate in professional development and training
- More flexibility in remote work and flexible work hours
- Clearer pathways for career progression and promotions
- Higher base compensation and bonuses 
)

3. Which of the following best describes your current career outlook in this company? 
(Options include: 
- I see myself staying with the company for the next 2+ years
- I see myself statying with the company for the next year but I am open to outside opportunities
- I am actively looking for new jobs outside the company
- I plan to leave the company in the near future regardless of whether I have the next opporunity confirmed.
)

4. How often have you felt burnout or overwhelmed by your workload? (Options include: Always, frequently, Sometimes, rarely, never)

5. What is a change that this company could make to prevent attrition from entry-level employees? (Qualitative question)

```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
 The **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada was reviewed. The sampling features are described below. [Source](https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234#a2)

1. Sample type: 
- This is a sample survey with a cross-sectional design.

2. Sample size: 
- A field sample of approximatively 50,000 units was used. Among them, about 40,000 invitation letters to the electronic questionnaire were sent to selected households across Canada. A completion of 24,000 questionnaires was expected.

3. Target population
-  The target population for the GSS Giving, volunteering and participating includes all persons 15 years of age and older living in the ten provinces of Canada. It excludes full-time (residing for more than six months) residents of institutions. 

4. Sampling frame
- This survey uses a frame that combines landline and cellular telephone numbers from the Census and various administrative sources with Statistics Canada's dwelling frame. Records on the frame are groups of one or several telephone numbers associated with the same address (or single telephone number in the case a link between a telephone number and an address could not be established). This sampling frame is used to obtain a better coverage of households with a telephone number. 

5. Survey mode(s) 
- The survey uses a combination of phone interviews and on-line questionnaires.

6. Timeline
- Data collection occured within 2018 from 2018-09-04 to 2018-12-28

7. Response rate
- The overall response rate was 41.9%.

8. Weights
- WGHT_PER: This is the basic weighting factor for analysis at the person level, i.e. to calculate estimates of the number of persons (non-institutionalized and aged 15 or over) having one or several given characteristics. WGHT_PER would range from 50 to 5,000 depending on where the participate resides.

- In addition to the estimation weights, bootstrap weights have been created for the purpose of design-based variance estimation. This weight hovers around the respective WGHT_PER.

9. Data processing
- Edits were performed both automatically and manually at macro and micro levels. For instance, family relationships were checked to ensure data integrity. The age of the respondents were also checked against their birthdates. Computer edits were performed to edit the flow of the questions to ensure that respondents answered the right questions to resolve errors. 

10. Cleaning, imputation, etc.
- Income information was obtained through linkage to tax data. Missing information was imputed. Family income was used instead of household income.

11. Sources of error
- Sources of errors include imperfect coverage and non-response; differences between target population and surveyed population. Response errors and processing errors are also pontential sources of errors. 

12. Limitations, known biases, etc
Biases could be stemmed from excluded population that differ from the rest of the population. Non-response could also introduce biases.

13. Link to documentation and any additional sources used
[General Social Survey - Canadians' Safety (GSS)](https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=1235019)


```

## Rubric
-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09 February 2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
