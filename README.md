# Telegram_Bot
A guide to host a telegram bot created using the python-telegram-bot library with heroku.

## Pre-Requisites
1. A heroku free account
2. A telegram account of course

## Getting Started
1. Create a new bot in telegram - 

   You need to go to botfather which is basically a bot himself that automate the process of creating your bot.  
   Type /newbot command which will take you to the flow of creating your bot
   Store the Token ID generated.
2. Create a new app in Heroku
3. Clone the repo
4. Replace the values in credentials.py file.
5. Execute following commands on cmd -
* heroku login
* git init
* heroku git:remote -a {heroku-project-name}
* git add .
* git commit -m "first commit"
* git push heroku master
6. Now go to the app page (the link of the domain you copied before) and add to the end of the link /setwebhook so that the address will be something like https://appname.herokuapp.com/setwebhook, if you see webhook setup ok then you are ready to go!
