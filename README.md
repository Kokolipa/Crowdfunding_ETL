# ETL project
### Project description:
Building an ETL pipeline using Python, Pandas, and other libraries and dictrionary methods.

### Data pipeline
**Extract:**
* Reading the xlsx files from the Starter_Code. 
**Transform:**
* Manipulating and cleaning the data to create the following DataFrames:
    * category df
    * subcategory df
    * contact df 
    * campaign df
* Using **QuickDBD** to create a SQL ERD for PostgreSQL and exporting the schema and the png output of the ERD file. 
**Load:**
* Loading the data into PostgreSQL based on the schema defined in QuickDBD.
* Querying each table to confirm data was imported correctly and successfully. 

### Python Libraries
1. Pandas
2. Numpy
3. json
4. sqlalchemy
5. Regex - re

### ERD Image
![erd](https://github.com/Kokolipa/Crowdfunding_ETL/blob/etl/Crowdfunding_ETL/ERD_and_schema/ERD.png)

#### Folder structure
``` yml
.
├── SurfsUp
│   ├── Crowdfunding_ETL    
│   |   ├── CSVs
│   |   |   ├── campaign.csv
│   |   |   ├── category.csv
│   |   |   ├── contacts.csv
│   |   |   ├── subcategory.csv
│   |   ├── ERD_and_schema      
│   |   |   ├── Images
│   |   |   |   ├── campaign_out.png
│   |   |   |   ├── category_out.png
│   |   |   |   ├── contacts_out.png
│   |   |   |   ├── subcategory_out.png
│   |   |   ├── ERD.png
│   |   |   ├── crowdfunding_schema.sql     
│   |   ├── Starter_Files      
│   |   |   ├── Resources
│   |   |   |   ├── contacts.xlsx
│   |   |   |   ├── crowdfunding.xlsx
│   |   |   ├── ETL_Mini_Project_Gal_Beeri.ipynb
│   |   |   ├── ETL_mini_project_manasa.ipynb  
│   |   |   ├── ETL_Mini_Project_YHara.ipynb      
|___.gitignore               
|___README.md
``` 
