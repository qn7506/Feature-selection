# Election Voting Feature Selection

This project analyzes factors influencing the percentage of votes for George Bush in the 2000 presidential election.

## Methods

Several feature selection approaches were used:

- Best subset selection
- Forward selection
- Backward elimination
- K-fold cross validation

Model performance was evaluated using:

- Adjusted R²
- AIC
- BIC
- Test set Mean Squared Error

## Final Model

The final selected predictors were:

- Male
- Male18
- Pop65
- NonMet
- Inc100

Regression equation:

Bush = -717.48 + 60.58Male – 45.36Male18 – 1.04Pop65 + 0.18NonMet – 1.79Inc100

## Conclusion

Feature selection methods consistently identified demographic variables and income distribution as key predictors of voting outcomes.

## Files
- "Analytical Report.docx" - analysis report
- "Code.ipynb" - code analysis
- "election2000-1.csv" - original dataset
- "election2000_test.csv" - test data
