---
description: A glimpse into the moderation commands for Amour.
---

# Moderation Commands

### ;;amgmute

Mutes all members in the voice channel of yourself or a specified user. Useful for Among Us.  
**Usage:**  
;;amgmute \[user\]  
;;muteall \[user\]  
;;amongus \[user\]  
Including a user is optional.

![Any users in a voice channel of the user or user mentioned will be muted.](../.gitbook/assets/amgmute.png)



### ;;amgunmute

Unmutes all members in the voice channel of yourself or a specified user. Useful for Among Us.  
**Usage:**  
;;amgunmute \[user\]  
;;unmuteall \[user\]  
Including a user is optional.

![Any users in the voice channel of the user or user mentioned will be unmuted.](../.gitbook/assets/amgunmute.png)



### ;;ban

Bans the mentioned user.  
**Usage:**  
;;ban \[user\] \[reason\]

![You can ban a user by ID or mention.](../.gitbook/assets/ban.png)

### ;;kick

Kicks the mentioned user.  
**Usage:**  
;;kick \[user\] \[reason\]

![You can kick a user by ID or mention.](../.gitbook/assets/kick.png)

### ;;nick

Sets your nickname or another member's nickname.  
**MANAGE NICKNAMES PERMISSION IS REQUIRED FOR BOTH THE MESSAGE AUTHOR & AMOUR.**  
**Usage:**  
;;nick \[user @ or ID\] \[nickname\]  
;;nick \[username\]

![If you specify a nickname, it will set it to that.](../.gitbook/assets/screen-shot-2021-01-03-at-3.30.26-pm.png)

![Specifying reasoning &quot;off&quot; after the user mention will disable thier nickname.](../.gitbook/assets/screen-shot-2021-01-03-at-3.31.19-pm.png)

![Audit logs message \(one is also included in discord&apos;s audit logs\)](../.gitbook/assets/screen-shot-2021-01-03-at-3.30.58-pm.png)

### ;;purge

Purges the specified number of messages in the channel the command is executed in.  
**Usage:**  
;;purge \[count max 100\]

![You can purge a maximum of 100 messages. ](../.gitbook/assets/purge.png)

### ;;role

Assigns the mentioned user a role.  
**Aliases:**  
;;assignrole  
;;addrole  
**Usage:**  
;;role \[user\] \[role\]

![To remove the role, you can re-run ;;role on any role.](../.gitbook/assets/addrole.png)

To remove the role, run the command again.

![If a user already has the role, it will remove it from them.](../.gitbook/assets/removerole.png)

### ;;rolecolor

Sets the color of a mentioned role.  
**Aliases:**  
;;colorrole  
;;rolecolour  
;;colourrole  
**Usage:**  
;;rolecolor \[role\] \[off \| hex\]

![You do not need to have a \# before the hex code for it to set.](../.gitbook/assets/rolecolor.png)

To turn the rolecolor off, use ;;rolecolor \[role\] off

![You can disable the rolecolor by using off after the role name/mention.](../.gitbook/assets/rolecoloroff.png)

### ;;unban

Unban the mentioned user.  
**Usage:**  
;;unban \[user\] \[reason\]

![Unban only works for User IDs for Discord API reasons.](../.gitbook/assets/unban.png)

### ;;whois

Get data on a mentioned user  
**Aliases:**  
;;who  
;;userinfo  
;;user  
**Usage:**  
;;whois \[user mention or ID\]

![Get information on a user, from last messages, to account type &amp; username.](../.gitbook/assets/whois%20%281%29.png)

