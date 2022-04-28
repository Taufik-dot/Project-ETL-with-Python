
# **Introduction of Project ETL with Python**

Extract, Transform and Load (ETL) is a collection of processes to "move" data from one place to another.
The place in question is from data sources (can be application databases, files, logs, databases from 3rd party, and others) to the data warehouse.

What is a data warehouse?

In short, a data warehouse is a database that contains data (tables) that are ready for analysis by Data Engineer and Data Scientists.

More details can be seen at:
https://en.wikipedia.org/wiki/Data_warehouse.

In this Project I will Practice each of these processes.

# Projects to be Done
In this project, I will process the registrant data for a hackathon organized by DQThon.

This dataset consists of 5000 rows of data (5000 registrants) in CSV (Comma-separated values) format and has several columns including:

- participant_id: ID of the participant/participant of the hackathon. This column is unique so each participant must have a different ID
- first_name: participant's first name
- last_name: participant's last name
- birth_date: participant's date of birth
- address: participant's residence address
- phone_number: participant's cellphone/phone number
- country: participant's country of origin
- institute: the current participating institution, can be the name of the company or the name of the university
- occupation: participant's current job
- register_time: the time participants register for the hackathon in seconds

However, in this project I will be asked to generate several columns by utilizing the existing columns, so that the end of this project is the result of data transformation with several new columns apart from the 10 columns above.

As a warm-up to this project, I will open the contents of the dataset and see the values.

