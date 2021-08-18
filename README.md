# Get Ubuntu x86_64 on your terminal/termux via ssh
# 1) Register your account on ngrok.com
# 2) Login to your account and get/copy Authtoken(authentication token) in "Get started" option 
![Screenshots](https://raw.githubusercontent.com/mjuned47/GHActions_SSH/master/screenshots/ngrok_token.jpg)

# 3) fork this repo (https://github.com/mjuned47/GHActions_SSH)
#  If you are using mobile then , click to desktop site and fork :
![Screenshots](https://raw.githubusercontent.com/mjuned47/GHActions_SSH/master/screenshots/fork.jpg)

# 4) Now go to your repository settings and go to secrets
![Screenshots](https://raw.githubusercontent.com/mjuned47/GHActions_SSH/master/screenshots/settings.jpg)

# 5) Add the following secrets, see more at bottom page
![Screenshots](https://raw.githubusercontent.com/mjuned47/GHActions_SSH/master/screenshots/add_secrets.jpg)

# 6) after adding secrets , go to actions , select workflow (ubuntu-ssh) and run it
![Screenshots](https://raw.githubusercontent.com/mjuned47/GHActions_SSH/master/screenshots/select_ubuntu.jpg)
![Screenshots](https://raw.githubusercontent.com/mjuned47/GHActions_SSH/master/screenshots/run_workflow.jpg)

# 7) wait for some seconds ,you will see message like
#   "ssh runner@x.tcp.ngrok.io -p xxxxx"
![Screenshots](https://raw.githubusercontent.com/mjuned47/GHActions_SSH/master/screenshots/msg.jpg)

# 8) copy this and open termux/terminal and install openssh
#    For termux : apt update && apt install openssh

# 9) Paste and execute ! You will be asked to enter password which you have set in secrets

# Info About Secrets :
1) GITHUBMAIL = github gmail
2) GITHUBNAME = github username
3) NGROK_TOKEN = authentication token which you got from ngrok.com
4) SSH_PASSWORD = ssh password and it will be asked during login
5) TELEGRAM_BOT_TOKEN = telegram bot token id which you might got after creating bot
6) TELGRAM_CHAT_ID = telegram group chat id ( create a group , add your created bot, add IDBot(telegram official bot) , now message /getgroupid in that group 
                                               you will get group id)
