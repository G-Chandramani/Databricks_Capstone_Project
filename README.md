Databricks Project 
we haave data from iot device that is smartwatch it will send data about users registration user profile
bpm data of user, workout session data of user, login/logout user from gym, etc. frequently
we are loading that data using kafka framework , doing transformation on that data using different methods.

**Platform Design**
![Screenshot 2024-05-19 180836](https://github.com/G-Chandramani/Databricks_Capstone_Project/assets/98181696/e8cc3784-28cc-4b88-8b7d-d0fee5514da0)

**As shown in above diagram we have **5 storage layer directories in the DLS**. then we have **databricks unity catalog** we created dev catalog to implement security for the development environment, behind the dev catalog we are creating 3 databases we have setup dev, qa, and production environment according to the design shown above.**

**flowchart:**
![Screenshot 2024-05-19 183748](https://github.com/G-Chandramani/Databricks_Capstone_Project/assets/98181696/1c0e7dcf-38a8-4c7e-8cda-71959176fc29)

**The above image shows the flow of working**
