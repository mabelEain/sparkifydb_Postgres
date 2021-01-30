## Data Modeling with Postgres

**Project Summary**

This is the read me document for the Udacity course "Data Engineering Nano Degree", "Data Modelling with Postgres"
The aim of this project is to demonstrate a sufficient understanding of concepts of data modelling through modelling a star schema and building an ETL pipeline using python.
    
## Purpose of Database

The purpose of this database design is to: 
    1. Provide a database where JSON data can be safely and securely transferred to.
    2. To enable Sparkify to access this data in a straightforward and timely fashion to perform relevant analytical queries (eg "how many people are listening per day?", "How many songs are being played per day?", "What are the top 50 songs played in a given period?")

##  How to run the Python scripts

1. Open the console window and type "python create_tables.py"
2. Once the command line returns, type "python elt.py".  The console screen should then indicate each row being submitted to the database.
    