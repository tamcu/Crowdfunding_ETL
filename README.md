
# Crowdfunding_ETL 
Project 2


## Description 
**Crowdfunding_ETL** solution, due 12/12/2023


## Requirements 
### A Category DataFrame is Created (15 points)
- [X] The DataFrame contains a "category_id" column that has entries going sequentially from "cat1" to "catn", where n is the number of unique categories (5 points)
- [X] The DataFrame has a "category" column that contains only the category titles (5 points)
- [X] The category DataFrame is exported as _category.csv_ (5 points)


### A Subcategory DataFrame is Created (15 points)
- [X] The DataFrame contains a "subcategory_id" column that has entries going sequentially from "subcat1" to "subcatn", where _n_ is the number of unique subcategories (5 points)
- [X] The DataFrame contains a "subcategory" column that contains only the subcategory titles (5 points)
- [X] The subcategory DataFrame is exported as _subcategory.csv_ (5 points)


### A Campaign DataFrame is Created (30 points)
- [X] The DataFrame has the following columns: (25 points)
    * A "cf_id" column
    * A "contact_id" column
    * A "company_name" column
    * A "description" column
    * A "goal" column that is a _float_ data type
    * A "pledged" column that is a _float_ data type
    * An "outcome" column
    * A "backers_count" column
    * A "country" column
    * A "currency" column
    * A "launch_date" with the time formatted as "YYYY-MM-DD"
    * An "end_date" with the time formatted as "YYYY-MM-DD"
    * A "category_id" column that contains the unique identification numbers matching those in the "category_id" column of the category DataFrame
    * A "subcategory_id" column that contains the unique identification numbers matching those in the "subcategory_id" column of the subcategory DataFrame
- [X] The campaign DataFrame is exported as _campaign.csv_ (5 points)


### A Contacts DataFrame is Created (15 points)
- [X] The DataFrame has the following columns: (10 points)
    * A "contact_id" column
    * A "first_name" column
    * A "last_name" column
    * An "email" column
- [X] The contacts DataFrame is exported as _contacts.csv_ (5 points)

### A Crowdfunding Database is Created (25 points)
- [X] A database schema labeled, _crowdfunding_db_schema.sql_ is created (5 points)
- [X] A _crowdfunding_db_ is created using the _crowdfunding_db_schema.sql_ file (5 points)
- [X] The database has the appropriate primary and foreign keys and relationships (5 points)
- [X] Each CSV file is imported into the appropriate table without errors (5 points)
- [X] The data from each table is displayed using a SELECT * statement (5 points)


## Submission
You are required to submit the URL of your GitHub repository for grading.


## Credits 
* Received comments and guidance from Instructor, Teaching Assistant 
* Used StackOverflow and module documentation for specific details
