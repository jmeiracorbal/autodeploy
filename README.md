# autodeploy-with-tags

Bash script to autodeploy creating tags per merged branch into master. 

# Requirements

* Synchronize your repo on your production server before first exec.
* Use a cron
* This script use a Slack bot to send messages, delete slack output if you dont want it
* `chmod u+x deploy`

Important:
* don't exec from local repository (into your development machine)
* this script is for add a lot micro changes every day into a project
