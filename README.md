# survey_in_progress
Get a friendly overview of a survey instrument while work is in progress

**_01_survey_script.Rmd_** This file reads _questions.xlsx_ and produces _01_survey_script.html_. This is the file you need to compile when you to have a look of the survey instrument

**_01_survey_script.html_** The questionnaire. 

**_01_survey_script.md_** Have a quick look of the survey instrument

**_02_survey_script.Rmd_** A helper file for compiling the html output. It's overwritten every time _01_survey_script.Rmd_ is knitted.

**_questions.xlsx_**  A spreadsheet with questions for the survey instrument. This is the only file that needs editing. More on that below.





Below a short description of columns in the excel file

**order**	define the order in which questions are listed within each section; it follows a numeric logic.

**sections** The number of hash signs determines the section level. Better to start off at level 2 (##) and keep increasing as needed. 
   "## Section 2"
   "### Section 3"

**Question_wording** No constraints or recommendations	

**Response_options**	Use semicolon to separate multiple response options.

**stub** Used to identify and link questions

**Role** 	What is the  question's role? (e.g. control, outcome). Helps to create a listing of types of questions hyperlinked.

**Role_2**




