# Get daily messages with the best deals and free stuff
Uses Reddit's praw API to look over subreddits that contains deals and/or free stuff to redeem and sends an email daily reporting all this information for easy access.
Sends an email at 7PM PST everyday with links to the top daily posts from r/deals, r/GameDeals, and r/eFreebies.
Now also added Discord webhook functionality to send an automated message at the same time.

Python script is executed daily via cron on a Raspberry Pi 4.
