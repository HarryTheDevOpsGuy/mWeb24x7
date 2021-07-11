#### What is mWeb24x7 ?
mWeb24x7 is small utility by which we can we monitor any website status. if site is down we can trigger email( mSend) or slack.  

#### How To Install/Setup mTrack Script on ubuntu.
it can be install on any linux machine.

##### Step 1: Install Script.
```bash
sudo curl -sL "https://github.com/HarryTheDevOpsGuy/mWeb24x7/raw/master/$(uname -p)/mweb24x7" -o /usr/bin/mweb24x7
sudo chmod +x /usr/bin/mweb24x7
```
##### Step 1: Install Script.
```bash
# mweb24x7 -h

-d domain_name   Domain to test ssl expiration
-x days          Certificate expiration interval (eg. if cert_date days)
-f domain_file   File with a list of FQDNs|domains
-e email         Send Email Notification
-s #devops       Send Slack Notification
-q               Do not print anything on the console
-b               Display header on the console
-r               Attach full csv report with combine report
-V               enable verbose
-h               Display this help
-v               Display version
```


Create Slack Bot for your Applications : https://slack.com/intl/en-in/help/articles/115005265703-Create-a-bot-for-your-workspace
