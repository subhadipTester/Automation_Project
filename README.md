# Automation_Project
Preparing a bash shell script to automate different workflows -Hosting a web server , Archiving logs and scheduling cron jobs 
This automation project repository contains a bash script which automates the following tasks: 
1) Check if the apache2 server is running and active 
2) tar the logs in /var/log/apache2 folder and place in /tmp/ directory 
3) copy the tar files and place in the AWS S3 bucket
4) This script will also schedule cron job based on given cron expression 
