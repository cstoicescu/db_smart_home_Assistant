# db_smart_home_Assistant
Smart Home Assistant Project For Uni  


<img src="https://i.imgur.com/vIF7LpH.png" />  


## Description:

  The present project consists in a database for a smart home assistant, where we keep important informations about users HEALTH PARAMETERS, shortly we monitor heart’s Beats Per Minute (BPM ) minimizing the risk of hearth attack of old pacients .   
  
  My idea was making a database that consists of USERS ( see USERS TABLE ) and using a personal DEVICE ( see DEVICES TABLE) we can track LOCATION in real time ( see LOCATIONS TABLE ), and ACTIVITIES ( see ACTIVITIES TABLE ) in each room of the house. Using the personal device, we monitor user HEARTH RATE in ENVIRONMENTALDATA TABLE.

As we all know, the normal hearth rate is between 60 – 100 BPM ( beats per minute ). If an old pacient let’s say has hearth problems, using a device ( phone, smartband, smartwatch, hearth rate monitor , see queryes), it can send an ALERT to DOCTOR and CAREGIVER when BPM value exceeded 100 BPM, to prevent hearth attack.  


Important: used NOT NULL for every datatype so that we can’t put null values in DB  
	-Used FK and PK to link tables (see ERD)  
	-Used TIMESTAMP for managing data types, because it extends date and we can do additions with those for calculating percentage  
	-Used: ONE TO MANY, ONE TO ONE relationship between tables  
Snapshots of reports and queries from homework mandatory checkpoints   


•	 Input data for a smart home assistant database which returns reports:  
<img src="https://i.imgur.com/taNFqyT.png" />  

•	Indoor Person Report report that computs the percentage spent at a certain location  

<img src="https://i.imgur.com/0953b4M.png" />    

*Percentage spend a certaing location:    
<img src="https://i.imgur.com/Vhh0w62.png" />  

•	Activity Report and report that  computes the activity percentage  
<img src="https://i.imgur.com/0H1ZBJH.png" />       

*Percentage of activity  
<img src="https://i.imgur.com/NK1zwqC.png" />     

•	Device Location Report   
<img src="https://i.imgur.com/xKEiUmF.png" />   

•	Environmental Data Report  
<img src="https://i.imgur.com/AGKruvP.jpg" />    

•	Alert Report  
<img src="https://i.imgur.com/Jcd9tqw.jpg" />  
 
• Every user who is monitored has a caregiver and a doctor who get announced in case of an emergency. Query that returns all the users along with their caregivers and doctors.  
<img src="https://i.imgur.com/HJhWgEp.png" />   

•	Query that returns the user who had the most frequent alerts during the last 3 days ( for statistics ).  
<img src="https://i.imgur.com/30qzZs4.jpg" />  

•	Query that returns the most active users, along with those who didn’t perform almost no activity during the last 24 hours (statistics).
<img src="https://i.imgur.com/iHeuvUG.jpg" />










 
 
 
