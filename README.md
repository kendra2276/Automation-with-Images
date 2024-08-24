# Automation-with-Images
This repository cotnains the Python script used to create the program that monitored the service level agreemnts (SLA) for the 5 most high profile clients. Once the data is extracted using SQL, it is cleaned and processed in Python. The cleaning process involves standardizing formats, removing duplicates, and ensuring data accuracy. To err on the side of caution, the SQL script will be omitted.

## Project Overview
The project was looking at the turn around time (tat), report age time (rat), volume for the month, along with the average tat. This project used visualtization  all through table and graphs to prove/disprove if we were within the sla. To take the program a step further, the tat graph for each client was embeded into the body of the email allowing for quick visualization to ensure we meet sla.  If for some reason we exceed the pre-defined tat, the lab managers then reached out to the lab to see why there was a delay.  

## Data Sources
The SQL script pulls data from the following tables:

Order Table: Contains information on  tat, rat, and volume. 

## Automation
Finally, once the data has been approved by the project manager the program is then automated using a batch file along with Task Scheduler. The program then ran and sent an email every morning.
