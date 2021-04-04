# Analyzing borrowers’ risk of defaulting

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
        <li><a href="#structure_notebook">Structure of Notebook</a></li>
        <li><a href="#executive_summary">Executive Summary</a></li>
        <li><a href="#accomplishments">Accomplishments</a></li>
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

The customers' credit worthiness [data](https://github.com/chuksoo/credit_rating_analytics/blob/main/Data/credit_scoring_eng.csv) is a real-life analytical case study provided by [Practicum by Yandex](https://practicum.yandex.com/). As a Data Scientist, we are to prepare a report for a client by analyzing the clients' customers and the risk of defaulting on a loan. Various data preprocessing steps were applied and used to analyze the borrower's risk of defaulting on a loan. The insight generated from this report is to be used when building a credit score of a potential customer. 

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

<ul>
    <li>Python</li>
    <li>Jupyter Notebook</li>
    <li>Pandas</li>
    <li>Numpy </li>
    <li>Matplotlib</li>
    <li>Seaborn</li>
    <li>NLTK</li>
    <li>WordNetLemmatizer</li>
    <li>SnowballStemmer</li>
</ul>

<div id="structure_notebook">
    <h2>Structure of Notebook</h2> 
</div>
<ol>
    <li>Open the data file and have a look at the general information</li>
    <li>Data preprocessing</li>
        <ul>
            <li>Processing missing values</li>
            <li>Data type replacement</li>
            <li>Processing duplicates</li>
            <li>Categorizing Data</li>
        </ul>
    <li>Answer the business question</li>
        <ul>
            <li>Is there a connection between having kids and repaying a loan on time?</li>
            <li>Is there a connection between marital status and repaying a loan on time?</li>
            <li>Is there a connection between income level and repaying a loan on time?</li>
            <li>How do different loan purposes affect on-time loan repayment?</li>
        </ul>
    <li>Conclusion</li>
</ol>

<div id="executive_summary">
    <h2>Executive Summary</h2> 
</div>

**Introduction**

In every business, having an idea about your customers' credit worthiness is an important metric in accessing customers' value to a business. This will later form a basis for measuring essential business metrics such as sales revenue, customer acquisition costs, estimated customer lifetime value, and customer churn. In this project, the bank’s loan division is trying to find out if a customer’s marital status and number of children have an impact on whether they will default on a loan. The goal is to apply data preprocessing and analytics in order to determine customers’ credit worthiness. The insight obtained from this project will enable the bank to determine the estimated customer lifetime value, and will be useful when building a **credit score** for a potential customer.

**Methods**

To accomplish this, I first inspected the data using the [pandas](https://pandas.pydata.org/) library to obtain general information about the data. I processed the missing values, changed data type, and processed duplicates. Next, I proceeded to categorized data and prepare the data for further analysis. To carry out *lemmatization* on the `purpose` column, I used the `WordNetLemmatizer` and `SnowballStemmer` to extract frequency of words in `purpose` column. I then proceeded to encode the categorical variables. In analyzing the data, I prepared various pivot tables and plotted various visualiztion using the [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/) libraries. Analysis using pivot table was important in annswering some of the business needs. 

**Key Findings**

Overall, we can see that people with more kids tends to have more debt. Statistically speaking, people with more than 5 kids and up to 20 kids are ~37% more likely to be in debt than people with no kid. This is a reasonable figure when you consider the fact that having more kid means you end up with more responsibility. 
<!--
<div> 
    <img src="https://github.com/chuksoo/credit_rating_analytics/blob/main/Image/debt_vs_children.JPG" /> 
    <img src="https://github.com/chuksoo/credit_rating_analytics/blob/main/Image/debt_vs_children_familystatus.JPG" /> 
    <img src="https://github.com/chuksoo/credit_rating_analytics/blob/main/Image/debt_vs_familystatus_education.JPG" /> 
    <img src="https://github.com/chuksoo/credit_rating_analytics/blob/main/Image/debt_vs_purpose.JPG" /> 
</div> 
-->
 
Solarized dark             |  Solarized Ocean
:-------------------------:|:-------------------------:
![](https://github.com/chuksoo/credit_rating_analytics/blob/main/Image/debt_vs_children.JPG)  |  ![](https://github.com/chuksoo/credit_rating_analytics/blob/main/Image/debt_vs_children_familystatus.JPG)
![](https://github.com/chuksoo/credit_rating_analytics/blob/main/Image/debt_vs_familystatus_education.JPG)  |  ![](https://github.com/chuksoo/credit_rating_analytics/blob/main/Image/debt_vs_purpose.JPG)


**Conclusion**



<div id="accomplishments">
    <h2>Accomplishments</h2> 
</div>
<ul>
    <li>Applied strategies for dealing with missing values.</li>
    <li>Converted data from one type to another.</li>
    <li>Identified duplicate data and processed it in several different ways.</li>
    <li>Categorized data.</li>
    <li>Final data export into pivot tables.</li>
    <li>Querying and using Pivot table for data manipulation and interpretation.</li>
    <li>Creating visualization using insights from pivot table.</li>
</ul>
 This project was able to answer the business questions. Using insights from this project, the client can classify customer's according to customers’ credit worthiness. 
