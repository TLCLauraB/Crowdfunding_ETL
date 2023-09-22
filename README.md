# Project 2, Group 3: Crowdfunding_ETL
### Team: 
Esther Baumgartner (EstherBaum), Laura Bishop (TLCLauraB), Jake Moen (JacobMoen) and Logan Severson (LSever32)

### Description:
In this ETL mini-project, Group 3 will work to build an ETL pipeline using Python, Pandas and and either Python dictionary methods or regular expressions to extract and transform the data. 

For 'Create the Contacts DataFrame', we created two contacts dataframes using using both Option 1: Python dictionary and Option 2: regular expressions. In the main body of work, we utilized Option 1, leaving Option 2 as 'extra credit'.

After transforming the data, we will create four CSV files an duse the CSV file data to create an ERD and table schema. Finally, we will upload the CSV file data into a Postgres database.

### Delieverable Leads:
* [ETL_Mini_Project_Starter_Code_Esther.ipynb](https://github.com/TLCLauraB/Crowdfunding_ETL_Group_3/blob/main/ETL_Mini_Project_Starter_Code_Esther.ipynb) -- Esther creating the Category, Subcategory and Campaign dataframes

* [ETL_Mini_Project_Starter_Code_Esther_Laura.ipynb](https://github.com/TLCLauraB/Crowdfunding_ETL_Group_3/blob/main/ETL_Mini_Project_Starter_Code_Esther_Laura.ipynb) -- Laura building the Regex Contacts Dataframe from Esther's original work

* [ETL_Mini_Project_Starter_Code_Logan.ipynb](https://github.com/TLCLauraB/Crowdfunding_ETL_Group_3/blob/main/ETL_Mini_Project_Starter_Code_Logan.ipynb) -- Logan building the Pandas Contacts Dataframe from Esther's original work

* [Crowdfunding Database]() -- Jake building the Crowdfunding database, using Logan's Contacts, built from Esther's original dataframes

* Category and Subcategory DataFrames: category.csv, subcategory.csv -- Esther

* ECampaign DataFrame: campaign.csv -- Esther

* Contacts DataFrame: contacts.csv, contacts_regex_clean.csv -- Logan and Laura

* Crowdfunding Database: CHANGE_NAME.csv -- Jake

### Resources Used:
Our group used the following link as a reference when changing the format of a pandas column to datetime:

* https://stackoverflow.com/questions/51587468/datetime-defaulting-to-1970-in-pandas

In googling the error 'ValueError: pattern contains no capture groups', our group used the following: 

* https://cumsum.wordpress.com/2021/06/06/pandas-valueerror-pattern-contains-no-capture-groups/#:~:text=This%20errors%20out%20because%20there's,be%20kept%20in%20the%20result

* https://docs.python.org/3/library/re.html

* https://www.regular-expressions.info/refcapture.html
