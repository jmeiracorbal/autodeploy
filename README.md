# Autodeploy

Bash script to autodeploy creating tags per merged branch into master. 

# Requirements

* Synchronize your repo on your production server before first exec.
* Use a cron
* This script use a Slack bot to send messages, delete slack output if you dont want it
* `chmod u+x deploy`

Important:

* don't exec from local repository (into your development machine)
* this script is for add a lot micro changes every day into a project

# Recommended

* [Check if pull needed in Git](https://stackoverflow.com/a/3278427)
* [How to increment version number in a shell script?](https://stackoverflow.com/a/8653732)
* [Delete tags on local and remote to synchronize](https://stackoverflow.com/questions/5480258/how-can-i-delete-a-remote-tag)
* [How to only push a specific tag to remote?](https://stackoverflow.com/questions/23212452/how-to-only-push-a-specific-tag-to-remote)
