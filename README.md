# slack-export

conversation and user data exported from [houstondatavis.slack.com](houstondatavis.slack.com) on July 31st, 2016

#### Here’s what’s included:

+ message history in channels
+ links to files shared in channels
+ archived channels
+ integration activity logs

#### What’s not included:

+ private group history and files
+ direct message history and files
+ edit and deletion logs

This export consists of a series of JSON files: one per channel per day with activity, plus a file containing information about all members of the [@houstondatavis](https://twitter.com/houstondatavis) Slack team. For information on the format of channel messages, please [consult Slack's API docs](https://api.slack.com/docs/messages).