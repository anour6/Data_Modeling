# data modeling with Cassandra 
ETL Pipeline is created for Pre-Processing the data Files which will be used to populate Apache Cassandra tables.
The CSV file titled <font color=red>event_datafile_new.csv</font>, located within the Workspace directory.  The event_datafile_new.csv contains the following columns: 
- artist 
- firstName of user
- gender of user
- item number in session
- last name of user
- length of the song
- level (paid or free song)
- location of the user
- sessionId
- song title
- userId

 Create queries to ask the following three questions of the data

 1. Give me the artist, song title and song's length in the music app history that was heard during  sessionId = 338, and itemInSession  = 4


 2. Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
    

 3. Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'
