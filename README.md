<h1>Data Engineering Nanodegree Program</h1>
<br>
<h3>Project 1</h3>

1. The purpose of the database in the context of srartup, Sparkify, and their analytical goals.
* The database was created for the analysis of the Sparkify music streaming data logs on songs and user activity.
* Since the analytics team is interested in the users' music choises, this database helps to perform such analysis. This relational database is a perfect solution for ease of quering the data as apposed to getting the data from the files stored in JSON logs.

2. State and justify your db schema desing and ETL pileline
* The following image is our star schema
![Star Schema](/star_schema.png)
* An implemented star schema, consists of four dimension tables (users, songs, artists, time) and a fact table playsongs).
* Each of the dimension tables has a primary key (i.e., users: user_id, songs: song_id, artists: artist_id, and time: start_time). These dimension tables are referenced by the songplays table with the corresponding foreign keys.

3. [Optional] Provide example queries and results for song play analysis.
