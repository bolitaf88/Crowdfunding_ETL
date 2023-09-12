# Crowdfunding_ETL
Project 2
**Readme**

# ETL Project

*Authors: HMosa and TBolima*

---

## Table of Contents

1. [Introduction](#introduction)
2. [Tools Used](#tools-used)
3. [Data Sources](#data-sources)
4. [Research Question](#research-question)
5. [Syntax and Queries](#syntax-and-queries)
6. [Relevance of the Activity](#relevance-of-the-activity)
7. [Challenges Faced](#challenges-faced)
8. [References](#references)

---

## 1. Introduction

  - This ETL project includes building of an ETL pipeline using Python, Pandas, and Python dictionary methods to extract and transform the data. After the tranforamtion, four CSV 
    files created and uploaded to Psotgres database. 
---

## 2. Tools Used

### Tools for ETL
- **Python**: Python, the programming language, served as the foundation for our data analysis project.
- **Pandas**: We harnessed the power of the Pandas library for data manipulation, including reading, cleaning, and transforming data.
- **NumPy**

### Database Management
- **PostgreSQL**: We employed PostgreSQL, an open-source relational database management system, to create, store, and manage our structured data.

### Collaboration and Presentation
- **GitHub**: GitHub served as our collaborative platform for code sharing and version control. It also enabled us to present our work in a structured manner.

### Research and Problem Solving
- **StackOverflow**: This platform proved invaluable for troubleshooting and finding solutions to specific coding challenges.
- **General Internet Searches**: We conducted extensive internet searches to gather additional information and insights relevant to our project.

---

## 3. Data Sources

We utilized two Excel files, namely `contacts.xlsx` and `crowdfunding.xlsx`, as the primary sources of our data. From these files, we performed ETL and created created four CSV files as per the requirements.

1. `category.csv`: Contains category data extracted from `crowdfunding.xlsx`.
2. `subcategory.csv`: Contains subcategory data extracted from `crowdfunding.xlsx`.
3. `contacts.csv`: Contains contact information extracted from `contacts.xlsx`.
4. `campaign.csv`: Contains campaign data derived from `crowdfunding.xlsx`.

These CSV files were subsequently loaded into a PostgreSQL database.

---

## 4. Research Question

- **Research Question**: *How can we effectively use Python, Pandas and Python dictionary to build ETL pipelines to transform xlsx files into PostgreSQL databases ?  
---

## 5. Syntax and Queries

### ETL 
- We used Python and Pandas, Python dictionary to read Excel files and transform and create CSV files.
   - Data manipulation techniques included splitting columns, changing data types, and reordering columns.


### ERD
- used QuickDBD to generate Entity-Relationship Diagram (ERD)
![ERD](https://github.com/bolitaf88/Crowdfunding_ETL/blob/main/crowdfunding_ERD.png)

### Database Schema
- Wrote SQL queries to create a well-defined database schema. We created tables for categories, subcategories, contacts, and campaigns.

#### Verification
- Run SELECT SQL statements to verify if the table schema created. 

### Data loading
- Four csv files loaded into Postgresql using Import/Export wizard.
  
#### Verification
- Run SELECT SQL statements to verify if the data loaded to the respective tables.
    - Campaign table
![campaign](https://github.com/bolitaf88/Crowdfunding_ETL/blob/main/campaign.png)

  - Category, Subcategory and Contacts tables
![cat_subcat_contactstables](https://github.com/bolitaf88/Crowdfunding_ETL/blob/main/cat_subcat_contact.png)

## 6. Relevance of the Activity

This activity holds relevance for a wide range of individuals and professionals, including:

- **Data Analysts**: Learning to clean and structure data from Excel files into a database is essential for performing further advanced data analysis.
- **Database Administrators**: Understanding how to create and manage a structured database schema is fundamental in database management.
- **Researchers**: Researchers across domains can benefit from these skills to efficiently manage and analyze data for their studies.
- **Students and Learners**: This activity serves as a valuable learning experience for those acquiring data analysis and database management skills.

---

## 7. Challenges Faced

During the completion of this activity, we encountered several challenges:

- **Python code**: Developing and debugging Python code to manipulate and transform data posed challenges.
- **Github**: github collboration (creating branches, sharing codes...).  
---

## 8. References

Our research and problem-solving efforts drew upon the following resources:

- **Class activity solutions**: utilized codes from class activity solutions provided by the instructors. 
- **StackOverflow**: This platform played a crucial role in troubleshooting and finding solutions to specific coding challenges.
- **General Internet Searches**: Extensive internet searches provided additional information and insights relevant to our project.

---

This README document has provided an overview of ETL project, focusing on the use of Python, the tools used, data sources, research question, SQL syntax, relevance, challenges faced, and references. We hope this guide proves helpful to those interested in similar data analysis endeavors.
