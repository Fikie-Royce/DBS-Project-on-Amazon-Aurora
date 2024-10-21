PROJECT TITLE: Linking an Amazon Aurora Relational Database to a Web Application

PROJECT DESCRIPTION: To develop and implement a web application that communicates with an Amazon Aurora relational database system.
Amazon Aurora was used as the backend database for the web application, which was developed with Node.js and Express and hosted on AWS EC2. 
Application data was managed and stored using Aurora's MySQL-compatible edition. 
In order to provide real-time data interaction and storage, it was intended to guarantee safe and effective data transfer between the web application and the database.


Selected Pillars of the AWS Well-Architected Framework that your work covered:
1. Security - IAM roles and policies were put into place to provide safe database access.
2. Reliability - Minimized downtime and guaranteed database availability by deploying Aurora in a multi-AZ configuration.
3. Performance Efficiency - Made effective use of Amazon Aurora's automated scaling capability to manage fluctuating demands and Optimized queries to guarantee reduced response times and quicker data retrieval.

What I Could Have Done Regarding the Selected Pillars?

1. I could have added multi-factor authentication (MFA) for more secure access to the database and used AWS Secrets Manager to store database credentials securely instead of hardcoding them.
