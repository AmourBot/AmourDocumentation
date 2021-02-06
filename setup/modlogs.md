---
description: The page to help you set up modlogs for your server using Amour.
---

# ModLogs

The modlogs channel function of Amour sends any modlog data for bans, kicks and unbans to this mentioned channel. This is optional of course and can be toggled.

### Usage:

;;modlogs \[channel \| off\]  
\[channel\] Can include using:

* The channel ID,
* Or, tagging the channel with \#

#### Example:

![](../.gitbook/assets/modlogs.png)

If you do not add arguments after ;;modlogs, it will return your modlogs channel.

![](../.gitbook/assets/modlogs0args.png)

Of course, to disable modlogs, you can use ;;modlogs off.

![](../.gitbook/assets/modlogsoff.png)

Whenever a punishment is issued, it will send the details in your modlogs channel. If no channel is set, it will not.

![](../.gitbook/assets/moderationlogs%20%281%29.png)

