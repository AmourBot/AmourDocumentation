---
description: A glimpse into the moderation commands for Amour.
---

# Moderation Commands

### /amgmute

Mutes all members in the voice channel of yourself or a specified user. Useful for Among Us.\
**Usage:**\
**/**amgmute (user)

![/amgmute usage](<../.gitbook/assets/Screen Shot 2022-03-21 at 1.22.00 PM.png>)

![Example usage](<../.gitbook/assets/amgmute (1).png>)

### /amgunmute

Unmutes all members in the voice channel of yourself or a specified user. Useful for Among Us.\
**Usage:**\
**/**amgunmute (user)

![/amgunmute](<../.gitbook/assets/Screen Shot 2022-03-21 at 1.23.47 PM.png>)

![usage response.](<../.gitbook/assets/amgunmute (1).png>)

### /ban

Bans the mentioned user with two methods.\
**Usage:**\
**/**ban \[user] (reason)\
/ban \[userid] (reason)

![Methods for /ban](<../.gitbook/assets/Screen Shot 2022-03-21 at 1.24.34 PM.png>)

![Works by ID or mention](<../.gitbook/assets/ban mention.png>)

### /kick

Kicks the mentioned user.\
**Usage:**\
**/**kick \[user] (reason)

![](<../.gitbook/assets/Screen Shot 2022-03-21 at 1.25.58 PM.png>)

![Usage example for kick.](<../.gitbook/assets/kick (1).png>)

### ;;nick

Sets your nickname or another member's nickname.\
**MANAGE NICKNAMES PERMISSION IS REQUIRED FOR BOTH THE MESSAGE AUTHOR & AMOUR.**\
**Usage:**\
****;;nick \[user @ or ID] \[nickname]\
;;nick \[username]

![If you specify a nickname, it will set it to that.](<../.gitbook/assets/Screen Shot 2022-01-30 at 1.55.56 PM.png>)

![Specifying reasoning "off" after the user mention will disable thier nickname.](<../.gitbook/assets/Screen Shot 2022-01-30 at 1.56.11 PM.png>)

![Audit logs message (one is also included in discord's audit logs)](<../.gitbook/assets/Screen Shot 2022-01-30 at 1.56.31 PM.png>)

### ;;purge

Purges the specified number of messages in the channel the command is executed in.\
**Usage:**\
****;;purge \[count max 100]

![You can purge a maximum of 100 messages. ](<../.gitbook/assets/Screen Shot 2022-01-30 at 2.10.36 PM.png>)

### ;;role

Assigns the mentioned user a role.\
**Aliases:**\
;;assignrole\
;;addrole\
**Usage:**\
****;;role \[user] \[role]

![To remove the role, you can re-run ;;role on any role.](<../.gitbook/assets/Screen Shot 2022-01-30 at 2.11.52 PM.png>)

To remove the role, run the command again.

![If a user already has the role, it will remove it from them.](<../.gitbook/assets/Screen Shot 2022-01-30 at 2.12.12 PM.png>)

### ;;rolecolor

Sets the color of a mentioned role.\
**Aliases:**\
;;colorrole\
;;rolecolour\
;;colourrole\
**Usage:**\
****;;rolecolor \[role] \[off | hex]

![You do not need to have a # before the hex code for it to set.](<../.gitbook/assets/Screen Shot 2022-01-30 at 2.12.40 PM.png>)

To turn the rolecolor off, use ;;rolecolor \[role] off

![You can disable the rolecolor by using off after the role name/mention.](<../.gitbook/assets/Screen Shot 2022-01-30 at 2.14.10 PM.png>)

### ;;unban

Unban the mentioned user.\
**Usage:**\
****;;unban \[user] \[reason]

![Unban only works for User IDs for Discord API reasons.](<../.gitbook/assets/Screen Shot 2022-01-30 at 2.14.45 PM.png>)

### ;;voicekick

Kick the specified user from a voice channel\
**Usage:**\
****;;voicekick \[user optional]

![](<../.gitbook/assets/Screen Shot 2022-01-30 at 1.49.56 PM.png>)

![](<../.gitbook/assets/Screen Shot 2022-01-30 at 1.48.09 PM.png>)

### ;;whois

Get data on a mentioned user\
**Aliases:**\
;;who\
;;userinfo\
;;user\
**Usage:**\
****;;whois \[user mention or ID]

![Get information on a user, from last messages, to account type & username.](<../.gitbook/assets/Screen Shot 2022-01-30 at 2.15.02 PM.png>)
