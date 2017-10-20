# kelvinang25.github.io

Approaches utilized Capstone Project (EDA):

1) Search through several sites like:
  - Kraggle
  - UCI
  - Data.sg
  - Alibaba
  
2) Identified consumer behavior log dataset from Alibaba and decided to download for EDA.

3) Initial EDA findings:
  - 3 dataset:
       i)   User view information (5,556,714, 3)
       ii)  User pay information (69,674,109, 3)
       iii) Shop information (2000 x 10)

Checked Missing and NaN Data Replacement:
The data was clean and did not fine any missing information.

Combined User view and User pay to create a single data frame

Down sample for easy analysis and data experimentation because after combination the data frame ballooned to 75 million.


Capstone Update 2:

1) Approach to exploratory data analysis
- Check for null
- Identify categorical or continuous features that can predict price 
- Replace categorical
- Break the date
Step 3: Impute NaN values to -99 
Step 4: Standardise all numeric values 
Step 5: Binarise year and month 
Step 6: Get dummy variables for all descriptive values

2) Initial results
- 

3) Any roadblocks, setbacks, or surprises
- Have issue installing Unicode and translate 


Perform initial descriptive and visual analysis of your data.

4) Identify outliers

5) Summarize risks and limitations

6) Proposed next steps
- Try the logistic regression, KNN (K - Nearest Neighbour)
- Evaluate classifier model performance

Describe how your EDA will inform your modeling decisions
What are three concrete actions you need to take next?


