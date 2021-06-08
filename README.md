# Student Query Automation

The main objective of this project is to check the subject line of each new email received in a dummy college support email for accepted issues, record this mail and finally send an automated response informing them about the ticket number for their issue and the department that will handle their problem

## Requirements to run the Project
+ First in gmail settings enable IMAP
+ In google account settings allow less secure apps to access
+ Create an excel file which will have two sheets. Rename sheet 1 resolved and sheet 2 Unresolved
+ In sheet one create the following columns- Ticket_Number, Email, Issue, Department,Description
Fill appropriate Values
+ No need to fill unresolved, it will be filled by automation

## In the project, the following changes need to be made for the program to run

+ In get password activity, provide the password for your Email
+ In Get IMAP mail messages and Send SMTP mail message activity provide your email address in property panel
+ In Both Excel Application Scope Activity, provide the path to the excel file we created before

### Now you can run the process
