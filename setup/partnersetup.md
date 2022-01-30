---
description: Set the partnerships counter channel for your server using Amour.
---

# Partnerships

The partnerships function of Amour is to count how many partnerships each user has posted in the designated channel. This amount can be checked with ;;partners or ;;leaderboard to see a leaderboard of the top partnerships for the day, month, week, or all time.

### Usage:

;;setpartnerchannel \[channel]\
\[channel] can include:

* The channel ID,
* Or the #channel with a #.

#### Example:

![](<../.gitbook/assets/Screen Shot 2022-01-30 at 1.22.31 PM.png>)

To disable this feature, use ;;setpartnerchannel off and the settings will clear from the database.

![](<../.gitbook/assets/Screen Shot 2022-01-30 at 1.23.10 PM.png>)

![What the completed partner embed looks like.](<../.gitbook/assets/Screen Shot 2022-01-30 at 1.24.43 PM.png>)



### How Partnerships Are Stored

* &#x20;Amour stores partnership COUNTS, nothing else. They are stored in our SQL database for a certain amount of time so they can be called to for ;;partners and ;;leaderboard as well as to tell you how many partners you've done after posting one.
* The SQL database is secured and can only be accessed by Bea.
