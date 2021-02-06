---
description: Set the partnerships counter channel for your server using Amour.
---

# Partnerships

The partnerships function of Amour is to count how many partnerships each user has posted in the designated channel. This amount can be checked with ;;partners or ;;leaderboard to see a leaderboard of the top partnerships for the day, month, week, or all time.

### Usage:

;;setpartnerchannel \[channel\]  
\[channel\] can include:

* The channel ID,
* Or the \#channel with a \#.

#### Example:

![](../.gitbook/assets/setpartnerchannel.png)

To disable this feature, use ;;setpartnerchannel off and the settings will clear from the database.

![](../.gitbook/assets/setpartnerchanneloff.png)

![What the completed partner embed looks like.](../.gitbook/assets/screen-shot-2020-10-17-at-8.56.52-pm.png)



### How Partnerships Are Stored

*  Amour stores partnership COUNTS, nothing else. They are stored in our SQL database for a certain amount of time so they can be called to for ;;partners and ;;leaderboard as well as to tell you how many partners you've done after posting one.
* The SQL database is secured and can only be accessed by Bea.

