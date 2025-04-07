# elevate-labs-internship-day1
Interview question related to in this task

Q1 What are missing values and how do you find handle them?
A. Select your data range.
   Go to Home > Conditional Formatting > New Rule.
   Choose "Format only cells that contain".
   Set rule: Cell Value → equal to → leave it blank.
   Choose a format (like a red fill) → click OK.


Q2 How do you treat duplicate records?
A. in excel open the data bar in that remove duplicate click then you have to select which column you want take it out
Q3 difference between dropna() and fillna() in pandas?
A.  dropna() :- This function is used to remove rows or columns that contain missing values (NaN).
    fillna() :- This function is used to replace missing values with something else like a constant, mean, or previous value.
Q4 What is outlier treatment and why is it important?
A. outlier:- An outlier is a data point that is significantly different from others in the dataset.
     Why is Outlier Treatment Important?
    📉 Skewed Analysis
    Outliers can distort statistical results like mean, standard deviation, or regression models.
    📊 Incorrect Insights
    Models might focus too much on outliers and miss the real trends in the data.
    🧠 Better Model Performance
    Removing or treating outliers often leads to more accurate and stable models.
Q5 Explain the process of standardizing data?
A. Standardization (also called Z-score normalization) is the process of rescaling the data so that it has:
   Mean = 0
   Standard Deviation = 1
   This makes features comparable even if they were originally on different scales.

Q6 How do you handle inconsistent data formats(e.g date/time)?
A.  i used this formula 
    =TEXT(DATEVALUE(LEFT(F2,10))+TIMEVALUE(MID(F2,12,8))+TIME(5,30,0),"dd-mmm-yyyy hh:mm:ss AM/PM ") 

Q7 What are the common data cleaning challenges?
A. 
 a.missing values
 b.Duplicates
 c.inconsistent formats
 d.outliers
 e.invalid values
 f.mixed types
 g.Unstructured data
 h.different units
 i.inconsistent categories
 j.irrelevent columns
Q8) How can you check data quality?
A. Accurate
   complete
   consistent
   timely
   valid
   unique
    

