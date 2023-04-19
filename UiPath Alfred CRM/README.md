# UIPATH-Alfred-Bot
Alfred – a robot built using UiPath. One of the software robots in the organization is to improve the handling of incoming email with list of excel worksheet attached new onboarding or existing customers details to be update from the Customer Relationship Management (CRM), estimated to be around 10.000 email a year globally.

![alt text](https://github.com/bacdillon/UiPath/blob/main/UiPath%20Alfred%20CRM/alfred-bot.jpg)

# CRM Operations
Django CRUD Operations with PostgreSQL

![alt text](https://github.com/bacdillon/UiPath/blob/main/UiPath%20Alfred%20CRM/main.JPG)
![alt text](https://github.com/bacdillon/UiPath/blob/main/UiPath%20Alfred%20CRM/01.JPG)

Here is a process overview of what Alfred will do

![alt text](https://github.com/bacdillon/UiPath/blob/main/UiPath%20Alfred%20CRM/Overview.jpg)

1.Open Email  
2.Download email excel customers attachment  
3. Open CRM browser  
4. Enter email address and password to login  
5. Select customer excel file  
6. Read range of customer file  
7. Add one customer record into CRM enterprise application with a simple framework  
8. Input all customer’s information into data table  
9. Follow by submit customer records from data table to CRM  
10.Input the results column within customer file  
11.Log a message activity what have being saved in the format as: <customer name>-<customer-email address>  
12.Error handling  
	– Prompt a message box showing an error exception if occurs   
	– Input result whether the job is (success or Failure / Not Completed)  
13. While handling errors that occur such as missing values or wrong input type within the spreadsheet but 
    somehow the robot still processes the rest of customers without interrupted  
14. Commit to master database  
15. Send the progress email with attachment to the sender once completed the task  
	
# Alfred Bot in action
video: https://youtu.be/Q4bai4yCoZw
