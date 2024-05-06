# Loan-Approval-Dataset-Analysis 💰
This project focuses on the alaysis and exploration of the Loan Approval Data set.

## About the Data Set 📑
Data set is taken from : https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/
- *Attributes :* 13 features
- *Size :* 614 rows * 13 columns

### 🚀Project Stages

1. *Data Cleaning:* 🫧
   - Processed and cleaned the dataset to ensure consistency and remove any inconsistencies or missing values.
   - Total Number of missing values found = 149
   - Visulaized the Null Values using Heat Maps ->
   - Heat map Before removing NULL values -
     
     ![Hmap1](https://github.com/iam-harshitha/End-to-End-Data-Science-projects/assets/142524750/ccd75c83-16e3-4774-be61-107fcee7bd55)

   - Heat map after removing NULL values -

    ![Hmap2](https://github.com/iam-harshitha/End-to-End-Data-Science-projects/assets/142524750/75e8bedb-3b21-4109-b437-1d8f6d7e951a)


2. *Exploratory Data Analysis (EDA):* 📈
   - Conducted thorough EDA to gain insights into the distribution of features, relationships, and patterns within the cleaned data.
   - Visualized the features to get some key insights and identify patterns within the data ->
   - Bar Plot showing distribution of applicants based on their Location -
     
     ![Bar1](https://github.com/iam-harshitha/End-to-End-Data-Science-projects/assets/142524750/b074f351-d387-4f94-9094-df085af6d946)

   - Pivot table to count loan approvals by education status -
          
    ![Bar2](https://github.com/iam-harshitha/End-to-End-Data-Science-projects/assets/142524750/c4e49eda-5b43-4401-b0e6-2e019f399bc7)

   - Pivot table to count loan approvals by Gender -

    ![Bar3](https://github.com/iam-harshitha/End-to-End-Data-Science-projects/assets/142524750/dd1be32b-bbfe-4652-b5fd-328d82edbc39)

   - Pivot table to count loan approvals by Location -

    ![Bar4](https://github.com/iam-harshitha/End-to-End-Data-Science-projects/assets/142524750/25cbfb5d-b0b2-4584-943b-8b7d651444f6)

   - Scatter Plot showing the Apllicant's income and its correlation with Loan Amount Requested and the Approval status -

    ![Scatter1](https://github.com/iam-harshitha/End-to-End-Data-Science-projects/assets/142524750/24983597-d410-40ca-b1db-a50d1b63a16f)

   - Violin Plot to show the distribution of Loan Amount by Property Area and Loan Status based -

  ![Violin1](https://github.com/iam-harshitha/End-to-End-Data-Science-projects/assets/142524750/bf570a7b-fc57-41bc-a009-b4f075be5807)

   - Line plot to show the correlation between ApplicantIncome and LoanAmount -

    ![line1](https://github.com/iam-harshitha/End-to-End-Data-Science-projects/assets/142524750/bc5e4aca-4611-4241-ac55-443749eedaf6)

   - Pair Plot to show various relation ships -

    ![Pair1](https://github.com/iam-harshitha/End-to-End-Data-Science-projects/assets/142524750/bb76738c-54f7-4c90-b11a-b7bc280ca12d)

   - Box plot of LoanAmount by Education -

     ![Box1](https://github.com/iam-harshitha/End-to-End-Data-Science-projects/assets/142524750/979a6a25-b107-4f19-8041-59f06ba7a383)



## Tools and Libraries Used 🔎

- Google Colab 
- Pandas, NumPy, Matplotlib, Seaborn for data manipulation and visualization 📊
