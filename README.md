# Linux-Managing-Process-Task

## Setup:

cd /home ; mkdir company; cd company; mkdir /tmp/company.backups;


## Tasks:

- Create a cron job that will run every 1 minute. Each time the job runs it will create a folder inside company folder the name of the folder should contine date and time when the job ran to make unique folder name. At the same cron job add another command that will create a text file that will hold output of the processes in your machine. And of course the file name should should be unique so you should use date and time in the file name.

Example of unique folder name:

        company_2023_10_30_13_10
        company_2023_10_30_13_11
       
- Create another cron job that will run every 3 minute. Each time the job runs it will bundle and compress the company folder then it will move the compressed folder to /tmp/company.backups . 

## Submission:

- After finishing the task take screen shot of the /tmp/company.backups .
- Then decompress one of the backups folders then take screen shot of the content of the decompressed folder.
- Then take screen shot of the two cron jobs.
- Then upload the 3 pictures to the forked repo and then create a pull request.
