# Analyzing borrowers’ risk of defaulting
## Credit Rating Analytics

Chukwuemeka Okoli <br>
Practicum by Yandex Project 1 <br>
April 2, 2021 

**Project description** <br>
Your project is to prepare a report for a bank’s loan division. You’ll need to find out if a customer’s marital status and number of children have an impact on whether they will default on a loan. The bank already has some data on customers’ credit worthiness.

Your report will be considered when building a **credit score** for a potential customer. A **credit score** is used to evaluate the ability of a potential borrower to repay their loan.

<!-- <hr> -->

## Table of contents

<div class="alert alert-block alert-info" style="margin-top: 20px">
    <ol>
        <li><a href="#objectives">Objectives</a></li>
        <li><a href="#data_source">Data Source</a></li>
        <li><a href="#technology_used">Technology Used</a></li>
        <li><a href="#general_conclusion">General conclusion</a></li>
        <li><a href="#project_readiness_checklist">Project Readiness Checklist</a></li>
    </ol>
</div> 
<br>
<!-- <hr>-->

<div id="objectives">
    <h2>Objectives</h2> 
</div>
The objective of this project is to:

- Prepare a report for a bank's loan division by analyze a borrower's risk of defaulting.
- Apply Data Preprocessing to a real-life analytical case study.

<div id="data_source">
    <h2>Data Source</h2> 
</div>
The [customers' credit worthiness](https://github.com/chuksoo/analyzing_borrowers_risk_of_defaulting/blob/main/credit_scoring_eng.csv) data is a real-life analytical case study provided by [Practicum by Yandex](https://practicum.yandex.com/). As a Data Scientist, we are to prepare a report for a client by analyzing the clients' customers and the risk of defaulting on a loan. Various data preprocessing was applied and used to analyze the borrower's risk of defaulting on a loan. The report is to be used when building a credit scoring of a potential customer. 

**Description of the data**
- `children`: the number of children in the family
- `days_employed`: how long the customer has been working
- `dob_years`: the customer’s age
- `education`: the customer’s education level
- `education_id`: identifier for the customer’s education
- `family_status`: the customer’s marital status
- `family_status_id`: identifier for the customer’s marital status
- `gender`: the customer’s gender
- `income_type`: the customer’s income type
- `debt`: whether the customer has ever defaulted on a loan
- `total_income`: monthly income
- `purpose`: reason for taking out a loan

<div id="technology_used">
    <h2>Technology Used</h2> 
</div>

- Python <br>
- Jupyter Notebook <br>
- Pandas <br>
- Numpy <br>
- Matplotlib <br>
- Seaborn <br>
- NLTK <br>
- WordNetLemmatizer <br>
- SnowballStemmer <br>

<div id="structure_notebook">
    <h2>Structure of Notebook</h2> 
</div>
1. Open the data file and have a look at the general information
2. Data preprocessing
- 2.1 Processing missing values <br>
- 2.2 Data type replacement <br>
- 2.3 Processing duplicates <br>
- 2.4 Categorizing Data <br>
3. Answer the business question
- Is there a connection between having kids and repaying a loan on time? 
- Is there a connection between marital status and repaying a loan on time?
- Is there a connection between income level and repaying a loan on time?
- How do different loan purposes affect on-time loan repayment?
4. Conclusion

<div id="executive_summary">
    <h2>Executive Summary</h2> 
</div>



<div id="accomplishments">
    <h2>Accomplishments</h2> 
</div>

- Applied strategies for dealing with missing values. <br>
- Converted data from one type to another. <br>
- Identified duplicate data and processed it in several different ways. <br>
- Categorized data. <br>
- Final data export into pivot tables. <br>
- Querying and using Pivot table for data manipulation and interpretation. <br>
- Creating visualization using insights from pivot table. <br>

This project was able to answer these questions:
- Is there a connection between having kids and repaying a loan on time?
- Is there a connection between marital status and repaying a loan on time?
- Is there a connection between income level and repaying a loan on time?
- How do different loan purposes affect on-time loan repayment?
