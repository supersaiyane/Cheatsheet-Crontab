![licence:free to use](https://img.shields.io/badge/licence-free--to--use-blue)  [![Linkedin Badge](https://img.shields.io/badge/-gurpreetsingh89-blue?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/gurpreetsingh89/)](https://www.linkedin.com/in/gurpreetsingh89/)  [![dev.to Badge](https://img.shields.io/badge/-@gurpreetsingh-000000?style=flat&labelColor=000000&logo=dev.to&link=https://dev.to/gurpreetsingh)](https://dev.to/gurpreetsingh) 


## What is Crontab?
The Cron daemon is a service that runs on all main distributions of Unix and Linux. Specifically designed to execute commands at a given time. These jobs are commonly refered as cronjobs and are one of the essential tools that should be present in every Systems Administrator's tool box. Cronjobs are used for automating tasks or scripts so that they can be executed at specific time.

```
# [minute] [hour] [day] [month] [week day] [command to be executed]
#    *       *      *      *        *
#    |       |      |      |        |
#    |       |      |      |        +------ day of week (0-6) (Sunday=0)
#    |       |      |      |
#    |       |      |      +--------------- month (1-12)
#    |       |      |
#    |       |      +---------------------- day of month (1-31)
#    |       |
#    |       +----------------------------- hour (0-23)
#    |
#    +------------------------------------- min (0-59)
```

# Example
```
0 * * * *	    every hour
*/15 * * * *	every 15 mins
0 */2 * * *	  every 2 hours
0 0 * * 0	    every Sunday midnight
@reboot	      every reboot
```


