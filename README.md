# SE762/INFOSYS300 Team 9 - Mail Extractor

This bot allows a user to extract their latest emails, sort them and extract them into a spreadsheet of their choice. 

## Requirements 
Being able to use this bot requires the user to set up their email account in a specific way in order to give the bot access. This bot will also only work for a Gmail account, but can easily be configured to use an Outlook account or any email service provider that uses IMAP servers. 

-  Enable IMAP and POP in their Gmail account. Go into Settings > Forwarding and POP/IMAP > Enable POP for all mail AND Enable IMAP 
-  The email must have 2 factor authentication set up 
-  Once two factor authentication is set up, the user will need to set up an "App password" Setting up an app password is quick and easy:
1. Go into "Manage your Google Account"
2. Go into "Signing in with Google"
3. Select "2 step verfication"
4. Select "App passwords"
5. Click generate
6. A unique password will now be generated

Keep in mind that this password is the one you use to log in to your account when using this bot, so please store it safely and securely.
[More details on App passwords can be found here.](https://support.google.com/mail/answer/185833?hl=en)

If you do not complete the steps above, the bot cannot access your emails and you will not be able to use this bot at all. 

## Excel Files
To use this bot, you must have an existing Excel file (.xslx, .xls, .xlb, .csv). This can be empty, but if you have a sheet called "Email Extraction", then the information in that sheet will be overwritten by the data collected by the bot.