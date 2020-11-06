# Analyze AB Test - 3 methods to analyze AB Test results

## Version Notes
* First version of the file was as it was submitted in Udacity.
* Following versions are an effort to re-familiarize myself with the Statistical 
  concepts while editing the file to look more like a stakeholder facing project instead of an assignment

## Jupyter EDA template observations
GOOD PRACTICE
* Include and INDEX
* Use readme to capture any on going attempts to solve 'warnings'
DATA PREP
* 'Data preparation' should include 'Assessment Report' with observations and actions
* Within 'Data preparation' also perform actions on clean-up and test cleanup with code comment 'DATA HEALTH'
* Make sure to identify 'clean up' as steps in order to distinguish as action oriented vs being general exploration or assessment


## DATA 
(in local) - CONTACT ME to collaborate


## INTRODUCTION
Jupyter notebook is written to identify the statistical analysis utlized to determine if the variation is viable


## DEBUGGING and LEARNINGS

1. (PENDING) REF: # Drop duplicates | README
- tried my best to use loc to indentify index but I couldn't figure it out
df2.drop(df2.loc[2893])
- Got same error when using
df2.drop(2893, inplace = True)

2. (SOLVED) Better way to calculate probability
(df2.converted == 1).mean()
-is better and cleaner than
df.query('converted == 1').count()[1]/df.count()[1]

----------------------------------------------------------------------------------------------------------------------------------------------------
#### LOG and JOURNAL
11/4/2020
- Started editing project file
- Continue with Probability section- Marked on Jupyter notebook
- GITHUB: Signed up for 'Next Journal' to allow run env for jupyter notebook and R without any download. 
- GITHUB: Also sync'd with 'ReviewNB' to allow for more readable version control as without it it is difficult to render the JSON file changes
- GITHUB: This is markup
11/6/2020
- Just finished up the probability part. Main sections till pending
