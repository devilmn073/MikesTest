This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

Below you will find basic information about the S-Curve Locator workflow<br>


# S-Curve Locator Diagnostic
The S-Curve Locator diagnostic is a survey with 22 questions that use a Likert scale to rate user's answers.
The answers range from "Strongly Disagree" to "Strongly Agree" and are scored on a numeric scale fomr 1-5.
The individual answers are tallied at the end of the survey to create the S-Curve Locator score. Scores are categorized 
as low (20-49), medium or the "Sweet Spot"(50-75), and high (76-100). At the end of the survey, users see their 
total S-Curve Locator plotted on a graphic and some content describing the meaning of their score with a list of resources
they can use, the questions of the survey with their responses, and a thank you page from Whitney.


# S-Curve Locator Users
There are two types of S-Curve Locator users: Managers/Leaders and Employees

#### Managers/Leaders can setup the S-Curve Locator for their employees by adding the following:
1. Entering the company name
2. Setting the start date for the survey
3. Setting the end date for the survey

The S-Curve Locator diagnostic will generate a unique ID for the company and display this back to the user with the start 
and end dates so that this information can be shared with employees

#### Employees can do the following:
1. Entering the company name and UID for their company
2. Take the survey
3. See the results in the web view
4. Generate a PDF of their results and download it


The S-Curve Locator diagnostic will generate a unique ID for each employee and provide this and their company's UID in the generated report

# S-Curve Scoring
Answers are scored on a numeric range from 1-5. Ordering of the scoring can vary based on the question. For example, 
in some questions, "Strongly Disagree" will be scored a '5' while in other questions it will be scored as a "1".
Individual answers are tallied at the end of the survey to create the S-Curve Locator score. Scores are categorized 
as low (20-49), medium or the "Sweet Spot"(50-75), and high (76-100).

# S-Curve Results
S-Curve results include the following:
1. Employee UID and company UID
2. Date the survey was taken
3. S-Curve score result with the S-Curve graphic, content associated with their score, the questions with their recorded responses, and a Thank You page. 

# S-Curve Content and User Experience
Most of the S-Curve content is static. This includes:
1. The questions and answer options
2. The content associated with low range, medium range, and high range scores including the S-Curve graphic
3. The Thank You page

Questions are presented individually in a "slider" like view with radio buttons to select answer options.  Answers are tallied
and results are presented at the end of the survey.  Historical user feedback has shown that users prefer to see a progress bar indicating percent done. 

All answers are required and users are not allowed to progress to the next question without providing an answer. Error messages 
must be presented indicating that a questions has not been answered.

