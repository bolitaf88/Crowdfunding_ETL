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

### Database Management
- **PostgreSQL**: We employed PostgreSQL, an open-source relational database management system, to create, store, and manage our structured data.

### Collaboration and Presentation
- **GitHub**: GitHub served as our collaborative platform for code sharing and version control. It also enabled us to present our work in a structured manner.

### Research and Problem Solving
- **Stack Overflow**: This platform proved invaluable for troubleshooting and finding solutions to specific coding challenges.
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

**Research Question**: *How can we effectively use Python, Pandas and Python dictionary in building ETL pipeline for transforming of data from Excel files into a structured PostgreSQL database, perform data manipulation techniques, and explore insights within the dataset?*

---

## 5. Syntax and Queries

### Data Loading and Transformation
- We used Python and Pandas to read Excel files and create CSV files.
- Data manipulation techniques included splitting columns, changing data types, and reordering columns.

### Database Schema
- SQL queries were used to create a well-defined database schema. We created tables for categories, subcategories, contacts, and campaigns.

### Data Analysis
- SQL SELECT statements enabled data retrieval for analysis from the PostgreSQL database.

### Data Export
- We exported the transformed data as CSV files, making it accessible for further analysis and sharing.

---

## 6. Relevance of the Activity

This activity holds relevance for a wide range of individuals and professionals, including:

- **Data Analysts**: Learning to clean and structure data from Excel files into a database is essential for performing further advanced data analysis.
- **Database Administrators**: Understanding how to create and manage a structured database schema is fundamental in database management.
- **Researchers**: Researchers across domains can benefit from these skills to efficiently manage and analyze data for their studies.
- **Students and Learners**: This activity serves as a valuable learning experience for those acquiring data analysis and database management skills.

---

## 7. Challenges Faced

During the completion of this activity, we encountered several challenges:

1. **Data Integrity**: Ensuring data consistency and integrity when importing from Excel files required meticulous data type conversions and cleaning.

2. **SQL Syntax**: Constructing SQL queries for creating complex schemas and retrieving specific data demanded precision and an understanding of database structures.

3. **Database Setup**: Setting up a PostgreSQL database and establishing connections can be challenging for beginners.

4. **Data Export**: Exporting data in the desired format for analysis or sharing presented some complexities.

5. **Python Syntax**: Developing and debugging Python code to manipulate and transform data also posed challenges, especially when dealing with complex data structures and transformations.
---

## 8. References

Our research and problem-solving efforts drew upon the following resources:

- **Class activity solutions** utilized codes from class activity solutions provided by the instructors. 
- **Stack Overflow**: This platform played a crucial role in troubleshooting and finding solutions to specific coding challenges.
- **General Internet Searches**: Extensive internet searches provided additional information and insights relevant to our project.

---

This README document has provided an extensive overview of ETL project, focusing on the use of Python, the tools used, data sources, research question, SQL syntax, relevance, challenges faced, and references. We hope this comprehensive guide proves helpful to those interested in similar data analysis endeavors.
