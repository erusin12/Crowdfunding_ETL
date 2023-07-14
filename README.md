# Crowdfunding_ETL
 Project_2

This was a group project that was completed in class.  My group consisted of Francesca, Alexandra and myself.  

We started the project with a started code consisting of Crowdfunding excel document and a Contacts excel document.  For the first part, we started with the starter_code in jupyter notebook.  We created dataframes and split one column into two using str.split.  Wee assigned numerical values to the categories and subcategories with this code : cat_ids = ["cat" + str(ids) for ids in category_ids].  This data was then exported into two separate csv files for use in future parts of the project.  The campaign dataframe was created.  We changed some of the column names and data types, converted the dates, and then joined the category and subcategory dataframes to this campaign dataframe.  This data was exported to a csv.  Lastly the contacts.xlsx table was cleaned and the data was exported to a csv.

For the second step of the project, we used a starter schema to use in the website https://app.quickdatabasediagrams.com/ in order to create a ERD.  Using the starter schema, the ERD was created and a screenshot image was added to the repository as well as the final ERD schema used to create the diagram.

For the last part, the starter schema was used in Postgres to create a Crowdfunding_db.  The query was run and then the tables were imported that had been created in the jupyter notebook part of the project.  Because of constraints, the tables were added in the following order: 'category.csv', 'contacts.csv', 'subcategory.csv', and lastly the 'campaign.csv'.  Queries were run with SELECT * FROM (table); to ensure data was in the tables and screenshots were obtained for each table.

This project was created mainly during class hours with the support of the group and our wonderful teacher.
