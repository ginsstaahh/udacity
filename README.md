# Intro
Song database is a program used for the latest and greatest music app created by Sparkify that acts as a backend framework* to store, insert, and provide you with songs, artist information, and albums.  The program consists of three python files and a data folder.  The sql_queries.py file creates and provides all the sql used for providing database table structure, deletion code and insertion statements. Create_tables.py is used as middleware that takes sql code from sql_queries.py for the purposes of creation and deletion of the database used and its tables.  The etl.py file contains the logic to process data insertion.  Data used for this project is found in the data folder consisting of log data and song data.  The two Jupyter notebooks show the rough work done with it's examples and entries into the databases.

*I use framework to mean the structure and baseline tables needed to support a working application.

There are five tables in the Sparkify database used as a backend resource: songplays, users, time, songs, and artists.  Each database table contain their own data columns and primary keys using int, float, varchar, text, and bigint data types.  Songplays table differs from other tables because it includes data from two foreign tables (songs and artists).

## Database Schema
Here is a diagram based off of the star schema that gives an overview of the tables and their data columns. 
![alt text](/db_schema.png?raw=true)

## How it Works
The ipynb Jupyter Notebooks were used to develop the working python code.  Once written out, a terminal can be used to run the python files to generate tables.  Use the terminal which can be found in the launcher tab, run create_tables.py to create the backend framework needed to assess the working code.  The etl.ipynb and test.ipynb Jupyter notebooks can then be run to insert data into the five tables and check the validity of the insertion respectfully.

### Prerequisites
No prerequisites are required for this project but can be run in the Jupyter Notebooks.
