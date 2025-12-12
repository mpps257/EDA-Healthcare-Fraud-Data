# Missing Values and Feature Engineering
We are going to list few notes as of why do we actually want to check with respect to missing values and further feature engineering.

Further we would list all the observations that we can have when we work for the same using given dataset.

## Missing Values
- What is the first question we need to ask when we encounter data?
    - Where is the data coming from? 
    - What is the source of data?
    - After we understand what is telling us about, if we encounter a missing value in any of the columns what do we need to do is the next question we need to ask.

- What is to be done when we encounter a missing value?
    - Check with the providers of the data.
    - Since some one would have formatted the data from its raw form to a uniform model, we need to go to source of the data and check if the data was actually missing in the raw data source. This would tell us if the null or a missing value is a legitimate one or no.
        - **Was there any issue while formatting the data?**
        - **Is it a true null or missing or was result of some error while collating data or collecting data?**
    - Further what can we do is to understand if the null value is pointing to some implicit information with respect to the given data.
        - **Does this null value carry some information?**
    - Further we can check if there is any patterns in the missing values. Questioning why and how are these missing values found will give further insights about why is there a missing value coming or can allow us to estimate in what cases can we find missing values.
        - **What pattern do they follow?**
        - **What is the proportion? - Allows us to simplify the task of imputation further.**
    - Before we get into the task of imputing or replacing these missing values with any value that can match well with the rest of the data distribution we can ask the question 
        - **How important is this column with the missing values to the target variable when we further go for prediction?**

