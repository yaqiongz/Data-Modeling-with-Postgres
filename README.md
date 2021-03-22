Introduction: Sparkify is a music app that have a log file contains their user's song play activity in JSON format.

In this data modeling project, we build a Postgres database to facility the analysis work of sparkify's user activity based on the log file and another JSON file containing detailed information of the songs in the app.

We created a star schema for the database, with `songplays` talbe as the fact table and `users`, `songs`, `artists`, `time` as the dimension table. 

We developed the ETL process for each table in jupyer notebook first to test our code on dealing with the first row of the tables. And then, we developed another ETL process file named etl.py that deals with all the rows in the tables.



To set up the database and process the data, run: `python create_tables.py` first, then run: `python etl.py`.